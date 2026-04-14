# Section 3: Generating and Designing

## 3.1 Design Thinking Process

The generation of design options applied creative, critical, and speculative thinking to address the design brief's requirement for an affordable, low-mass, integrated system that provides real-time biomechanical feedback to tennis players.

| Thinking Mode | Application to Design Brief |
|---------------|---------------------------|
| **Creative** | Explored unconventional form factors and feedback mechanisms beyond existing commercial solutions |
| **Critical** | Evaluated each option against measurable constraints (mass, cost, latency) identified in Section 1 |
| **Speculative** | Considered future scalability, such as multi-user detection and cloud analytics |

---

## 3.2 Design Options Generated

Three distinct design options were developed to address the core problem: providing affordable, real-time tennis stroke feedback. Each option differs in system architecture, particularly in how feedback is delivered to the user.

### 3.2.1 Option A: Wearable Sensor with Physical Flag Feedback

**Concept:** A compact module attached to the racquet throat transmits accelerometer data via BLE to a separate Base Station positioned near the court. The Base Station uses a servo-driven mechanical flag to provide immediate visual feedback.

#### Block Diagram (IPO Model)
```
┌─────────────────────────────────────────────────────────────────────────┐
│                         OPTION A: PHYSICAL FLAG                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   INPUT              PROCESS                OUTPUT                     │
│   ═════              ══════                ══════                     │
│                                                                         │
│  ┌─────────┐        ┌──────────┐         ┌─────────────┐              │
│  │ Racquet │   →    │ ESP32-C6 │   →     │ Servo Motor │             │
│  │Motion   │        │ MCU +    │   →     │ (Flag Pos.) │             │
│  │         │        │ BNO055   │   BLE   │             │             │
│  └─────────┘        └──────────┘         └─────────────┘              │
│      │                  │                      │                       │
│      │                  │                      │                       │
│      ▼                  ▼                      ▼                       │
│  Accelerometer     Quaternion        Mechanical Flag                    │
│  Data (200Hz)      Processing       Position: Up/Down                 │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

#### Schematic Concept
```
                    ┌─────────────────┐
                    │   Li-Po 250mAh  │
                    │      (3.7V)     │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │    ESP32-C6     │
                    │  (XIAO Board)    │
                    │                 │
                    │  ┌───────────┐  │
                    │  │   BLE    │  │
                    │  │ Antenna  │  │
                    │  └───────────┘  │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │    BNO055       │
                    │   (9-DOF IMU)   │
                    │                 │
                    │ SDA/SCL (I2C)   │
                    └─────────────────┘
```

#### Specifications
| Parameter | Value |
|-----------|-------|
| Racquet Module Mass | ~12g |
| Base Station Mass | ~180g |
| Total System Cost | ~$45 AUD |
| Feedback Latency | ~0.8s |
| Power Consumption | ~45mA active |

#### Evaluation Against Design Brief
| Criterion | Performance |
|-----------|-------------|
| **Mass Constraint (≤15g)** | ✓ Exceeds - 12g total |
| **Cost Constraint (<$60)** | ✓ Exceeds - ~$45 total |
| **Feedback Speed (≤1.5s)** | ✓ Exceeds - ~0.8s |
| **Accessibility** | ✓ Low cost; visual feedback visible to player |
| **Ethical Alignment** | ✓ Promotes skill over power |

---

### 3.2.2 Option B: Wearable Sensor with Audible Chime Feedback

**Concept:** A compact module attached to the racquet throat contains both the sensing system and a miniature speaker. Upon detecting stroke quality, the module itself produces a distinct tone (high pitch = good, low pitch = poor form).

#### Block Diagram (IPO Model)
```
┌─────────────────────────────────────────────────────────────────────────┐
│                      OPTION B: AUDIBLE CHIME                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   INPUT              PROCESS                OUTPUT                     │
│   ═════              ══════                ══════                     │
│                                                                         │
│  ┌─────────┐        ┌──────────┐         ┌─────────────┐              │
│  │ Racquet │   →    │ ESP32-C6 │   →     │ Piezo       │             │
│  │ Motion  │        │ MCU +    │   →     │ Speaker     │             │
│  │         │        │ BNO055   │  Audio  │             │             │
│  └─────────┘        └──────────┘         └─────────────┘              │
│      │                  │                      │                       │
│      │                  │                      │                       │
│      ▼                  ▼                      ▼                       │
│  Accelerometer     Onboard       Tone Frequency:                       │
│  Data (200Hz)      Processing    880Hz (good) / 220Hz (poor)           │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

#### Schematic Concept
```
                    ┌─────────────────┐
                    │   Li-Po 180mAh  │
                    │      (3.7V)     │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │    ESP32-C6     │
                    │  (XIAO Board)   │
                    │                 │
                    │  ┌───────────┐  │
                    │  │  BLE 5.3  │  │
                    │  │ Antenna   │  │
                    │  └───────────┘  │
                    └────────┬────────┘
                             │
              ┌──────────────┴──────────────┐
              │                             │
     ┌────────▼────────┐          ┌─────────▼────────┐
     │    BNO055       │          │  Piezo Speaker    │
     │   (9-DOF IMU)  │          │  (12mm, 5V)       │
     │                │          │                   │
     │ SDA/SCL (I2C)  │          │ GPIO → PWM Out    │
     └─────────────────┘          └───────────────────┘
```

#### Specifications
| Parameter | Value |
|-----------|-------|
| Racquet Module Mass | ~14g |
| Base Station Mass | None required |
| Total System Cost | ~$38 AUD |
| Feedback Latency | ~0.4s |
| Power Consumption | ~38mA active + 12mA audio |

#### Evaluation Against Design Brief
| Criterion | Performance |
|-----------|-------------|
| **Mass Constraint (≤15g)** | ✓ Meets - 14g total |
| **Cost Constraint (<$60)** | ✓ Exceeds - ~$38 total |
| **Feedback Speed (≤1.5s)** | ✓ Exceeds - ~0.4s |
| **Accessibility** | ✓ Audible; works during movement |
| **Ethical Alignment** | ✓ Very low cost; immediate feedback |

**Critical Analysis:** While Option B offers the lowest latency and eliminates the need for a separate base station, the audible feedback may be impractical in noisy court environments. Additionally, the speaker adds complexity and potential points of failure.

---

### 3.2.3 Option C: Wearable Sensor with Smartphone App Integration

**Concept:** The racquet module transmits raw accelerometer data via BLE to a smartphone application. The app processes the data, displays stroke analytics, and provides visual feedback through the phone screen.

#### Block Diagram (IPO Model)
```
┌─────────────────────────────────────────────────────────────────────────┐
│                      OPTION C: SMARTPHONE APP                           │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   INPUT              PROCESS                OUTPUT                     │
│   ═════              ══════                ══════                     │
│                                                                         │
│  ┌─────────┐        ┌──────────┐         ┌─────────────┐              │
│  │ Racquet │   →    │ ESP32-C6 │   →     │ Smartphone  │             │
│  │ Motion  │        │ MCU +    │   →     │ App Display │             │
│  │         │        │ BNO055   │  BLE    │             │             │
│  └─────────┘        └──────────┘         └─────────────┘              │
│      │                  │                      │                       │
│      │                  │                      │                       │
│      ▼                  ▼                      ▼                       │
│  Accelerometer     Raw Data       Graphical UI:                         │
│  Data (200Hz)      Streaming      Stroke Quality Score                 │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

#### Schematic Concept
```
                    ┌─────────────────┐
                    │   Li-Po 180mAh  │
                    │      (3.7V)     │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │    ESP32-C6     │
                    │  (XIAO Board)   │
                    │                 │
                    │  ┌───────────┐  │
                    │  │  BLE 5.3  │  │
                    │  │ Streaming │  │
                    │  └───────────┘  │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │    BNO055       │
                    │   (9-DOF IMU)   │
                    │                 │
                    │ SDA/SCL (I2C)   │
                    └─────────────────┘
                             │
                             ▼ BLE 5.3
                    ┌─────────────────┐
                    │   Smartphone    │
                    │   (iOS/Android) │
                    │                 │
                    │  Custom App     │
                    │  (Flutter/Dart) │
                    └─────────────────┘
```

#### Specifications
| Parameter | Value |
|-----------|-------|
| Racquet Module Mass | ~11g |
| Base Station Mass | None required |
| Total System Cost | ~$32 AUD |
| Feedback Latency | ~0.6s (includes phone processing) |
| Power Consumption | ~35mA active |

#### Evaluation Against Design Brief
| Criterion | Performance |
|-----------|-------------|
| **Mass Constraint (≤15g)** | ✓ Exceeds - 11g total |
| **Cost Constraint (<$60)** | ✓ Exceeds - ~$32 total |
| **Feedback Speed (≤1.5s)** | ✓ Meets - ~0.6s |
| **Accessibility** | ⚠ Requires smartphone ownership |
| **Ethical Alignment** | ⚠ Smartphone dependency may exclude some users |

**Critical Analysis:** Option C is the lowest cost solution and offers the richest data visualisation. However, it introduces smartphone dependency, which contradicts the ethical requirement for accessibility. Players without smartphones or with incompatible devices would be excluded.

---

## 3.3 Comparative Analysis of Design Options

### 3.3.1 Multi-Criteria Comparison Matrix

| Criterion | Weight | Option A (Flag) | Option B (Chime) | Option C (App) |
|-----------|--------|-----------------|------------------|----------------|
| **Mass Compliance** | 25% | 12g ✓ | 14g ✓ | 11g ✓✓ |
| **Cost Effectiveness** | 25% | ~$45 ✓ | ~$38 ✓✓ | ~$32 ✓✓ |
| **Feedback Speed** | 20% | 0.8s ✓✓ | 0.4s ✓✓ | 0.6s ✓✓ |
| **Environmental Robustness** | 15% | High ✓✓ | Medium ✓ | Low ⚠ |
| **User Accessibility** | 15% | High ✓✓ | High ✓✓ | Medium ⚠ |

### 3.3.2 Weighted Scoring

| Option | Score Calculation | Total |
|--------|-------------------|-------|
| **Option A** | (25×4)+(25×3)+(20×4)+(15×4)+(15×4) | **3.85/4** |
| **Option B** | (25×3)+(25×4)+(20×4)+(15×2)+(15×4) | **3.50/4** |
| **Option C** | (25×4)+(25×4)+(20×4)+(15×1)+(15×2) | **3.25/4** |

### 3.3.3 Design Option Comparison Summary

| Feature | Option A | Option B | Option C |
|---------|----------|----------|----------|
| **Complexity** | Medium | Low | Medium |
| **External Dependencies** | None | None | Smartphone |
| **Outdoor Visibility** | Excellent | Good | Poor (screen glare) |
| **Privacy** | High | High | Low (data collection) |
| **Maintenance** | Low | Low | Medium (app updates) |
| **Scalability** | High | Medium | High |
| **Manufacturing Difficulty** | Medium | Low | Low |

---

## 3.4 Preferred Design Selection

### 3.4.1 Selection Rationale

Based on the comparative analysis, **Option A (Physical Flag Feedback)** is selected as the preferred design. This selection is justified through critical evaluation against the design brief's ethical considerations and practical requirements.

### 3.4.2 Justification

1. **Ethical Accessibility:** Option A operates independently of smartphones, ensuring all tennis players can access feedback regardless of technology ownership. This directly addresses the distributive justice concern identified in Section 1.1.2.

2. **Environmental Robustness:** The physical flag provides unambiguous feedback visible from any position on the court, functioning reliably in bright sunlight, rain, and noisy environments where Options B and C would struggle.

3. **Scalability:** The modular architecture (separate sensor module and base station) allows for future expansion, such as connecting multiple units to a central hub for group training sessions.

4. **Balance of Cost and Function:** While Option A has a higher component count than Options B and C, it remains within budget at ~$45 AUD, satisfying the cost constraint while providing superior reliability.

### 3.4.3 Trade-offs Acknowledged

| Trade-off | Mitigation Strategy |
|-----------|---------------------|
| Higher cost than Option C | BOM optimisation; bulk component purchasing |
| Base station required | Base station housed in durable, weather-resistant enclosure |
| Slightly higher latency than Option B | Latency (0.8s) remains well within requirement (1.5s) |
| Additional assembly complexity | Clear assembly documentation; 3D-printed mounting brackets |

---

## 3.5 Detailed System Architecture (Preferred Option)

### 3.5.1 Integrated System Block Diagram

```
┌────────────────────────────────────────────────────────────────────────────────┐
│                        TENNIS ANALYSER SYSTEM ARCHITECTURE                     │
│                              (Integrated & Controlled)                         │
├────────────────────────────────────────────────────────────────────────────────┤
│                                                                                │
│   ┌─────────────────────────────────────────────────────────────────────┐    │
│   │                      SUBSYSTEM A: DATA ACQUISITION                   │    │
│   │                              (On-Racquet Module)                     │    │
│   │                                                                     │    │
│   │   ┌──────────┐     ┌──────────────┐     ┌──────────────────┐         │    │
│   │   │ BNO055  │────▶│  ESP32-C6    │────▶│   BLE 5.3 TX    │         │    │
│   │   │ (9-DOF) │     │   MCU        │     │   Antenna       │         │    │
│   │   │         │     │  Processing  │     │                 │         │    │
│   │   └──────────┘     └──────────────┘     └────────┬─────────┘         │    │
│   │        │                   │                     │                    │    │
│   │        │                   │                     │                    │    │
│   │        ▼                   ▼                     ▼                    │    │
│   │   Quaternion    ───▶   Stroke Class ───▶    Wireless                  │    │
│   │   Data                   (Good/Poor)        Transmission              │    │
│   │                                                                     │    │
│   │   ┌──────────────────────────────────────────────────────────────┐   │    │
│   │   │                     POWER DOMAIN                             │   │    │
│   │   │  Li-Po 250mAh ──▶ MCP73831 Charger ──▶ 3.3V LDO Regulator  │   │    │
│   │   └──────────────────────────────────────────────────────────────┘   │    │
│   └─────────────────────────────────────────────────────────────────────┘    │
│                                      │ BLE 5.3                                 │
│                                      │ (10m range)                            │
│                                      ▼                                        │
│   ┌─────────────────────────────────────────────────────────────────────┐    │
│   │                      SUBSYSTEM B: FEEDBACK OUTPUT                   │    │
│   │                             (Base Station)                          │    │
│   │                                                                     │    │
│   │   ┌──────────────┐     ┌──────────────────┐     ┌───────────────┐  │    │
│   │   │  BLE 5.3 RX  │────▶│  ESP32-C6        │────▶│  SG90 Servo  │  │    │
│   │   │  Antenna     │     │   MCU            │     │   Motor       │  │    │
│   │   │              │     │  Decision Logic  │     │               │  │    │
│   │   └──────────────┘     └──────────────────┘     └───────┬───────┘  │    │
│   │                                                          │          │    │
│   │                                                          ▼          │    │
│   │                                                     ┌─────────┐     │    │
│   │                                                     │  Flag   │     │    │
│   │                                                     │(Up/Down)│     │    │
│   │                                                     └─────────┘     │    │
│   │                                                                     │    │
│   │   ┌──────────────────────────────────────────────────────────────┐   │    │
│   │   │                     POWER DOMAIN                             │   │    │
│   │   │  USB-C 5V ──▶ MCP73831 Charger ──▶ Li-Po 500mAh ──▶ 5V/3.3V │   │    │
│   │   └──────────────────────────────────────────────────────────────┘   │    │
│   └─────────────────────────────────────────────────────────────────────┘    │
│                                                                                │
└────────────────────────────────────────────────────────────────────────────────┘
```

### 3.5.2 Control System Analysis

The system operates as an **open-loop control system** with the following characteristics:

| Control Element | Implementation |
|-----------------|----------------|
| **Sensor (Input)** | BNO055 IMU measuring acceleration and angular velocity |
| **Controller** | ESP32-C6 processing quaternion data and classifying stroke |
| **Actuator (Output)** | SG90 servo motor driving flag position |
| **Feedback** | Flag position provides visual confirmation of stroke quality |

#### Control Loop Timing
```
t=0ms     → Tennis ball impacts racquet
t=0-5ms   → BNO055 captures impact spike (200Hz sampling)
t=5-50ms  → ESP32-C6 processes quaternion data
t=50-100ms → Stroke classification algorithm executes
t=100ms   → BLE packet transmitted to Base Station
t=200ms   → Base Station receives packet
t=200-800ms → Servo actuation (flag movement)
t=800ms   → Player sees feedback
```

Total system latency: **≤800ms** (well within 1.5s requirement)

### 3.5.3 Mechanical Subsystem Design

```
┌─────────────────────────────────────────┐
│           FLAG MECHANISM ASSEMBLY        │
├─────────────────────────────────────────┤
│                                         │
│         ┌───────────────────┐           │
│         │      FLAG         │ ← RED/GREEN
│         │   (3D Printed)     │   SURFACE
│         └────────┬───────────┘           │
│                  │                       │
│                  │ (Rotation Axis)        │
│           ┌──────┴──────┐                │
│           │  Servo Horn  │                │
│           └──────┬──────┘                │
│                  │                       │
│           ┌──────┴──────┐                │
│           │  SG90 Servo │                │
│           │   Motor     │                │
│           └──────┬──────┘                │
│                  │                       │
│         ┌────────┴────────┐              │
│         │   BASE PLATE     │              │
│         │   (3D Printed)   │              │
│         └──────────────────┘              │
│                                         │
│   Flag States:                           │
│   ┌─────────┐  ┌─────────┐              │
│   │   UP    │  │  DOWN   │              │
│   │  GOOD   │  │  POOR   │              │
│   │  STROKE │  │  STROKE │              │
│   └─────────┘  └─────────┘              │
│                                         │
└─────────────────────────────────────────┘
```

---

## 3.6 Engineering Concepts and Principles Applied

### 3.6.1 Mechanical Principles

| Principle | Application |
|-----------|-------------|
| **Leverage (Moments)** | Servo horn acts as a first-class lever; flag position amplified by lever arm length |
| **Rotational Kinematics** | Flag rotation (θ) controlled by servo angle; angular velocity determines feedback speed |
| **Potential/Kinetic Energy** | Flag stores gravitational potential energy when raised; releases on lowering |

### 3.6.2 Electrical Principles

| Principle | Application |
|-----------|-------------|
| **Ohm's Law (V=IR)** | Used to calculate current limiting resistors for status LEDs |
| **Power Consumption** | P = V × I calculated for battery life estimation (250mAh ÷ 45mA = 5.5h runtime) |
| **Signal Conditioning** | BNO055 provides pre-filtered quaternion data, reducing processing overhead |

### 3.6.3 Systems Principles

| Principle | Application |
|-----------|-------------|
| **Input-Process-Output (IPO)** | Block diagrams model system data flow at all levels |
| **Integrated System** | Mechanical (flag) and electrotechnological (MCU, IMU, BLE) subsystems operationally linked |
| **Control System** | Open-loop with user as feedback interpreter |

---

## 3.7 Compliance with Australian Standards

| Standard | Requirement | Design Compliance |
|----------|-------------|-------------------|
| **AS/NZS 62368.1** | Audio/video equipment safety | Low-voltage circuit (≤5V); no hazardous components |
| **AS/NZS 60950** | Information technology equipment | USB-C charging complies with limited power source requirements |
| **AS/NZS 4268** | Radio equipment | BLE 5.3 module certified; frequency band 2400-2483.5 MHz |
| **AS/NZS CISPR 11** | EMC emissions | ESP32-C6 certified module; PCB layout minimises interference |

---

## 3.8 Summary

Three design options were generated using creative, critical, and speculative thinking processes. Each option was evaluated against the constraints and considerations derived from the design brief, with particular attention to the ethical requirement for accessibility.

**Option A (Physical Flag Feedback)** was selected as the preferred design due to:
- Independence from external devices (smartphones)
- Robust outdoor performance
- Unambiguous visual feedback
- Compliance with all measurable constraints

The selected design achieves an integrated and controlled system through:
- Mechanical subsystem (servo-driven flag)
- Electrotechnological subsystem (IMU, MCU, BLE)
- Open-loop control architecture
- Estimated total cost of ~$45 AUD
- On-racquet module mass of ~12g

---

## References

[1] Seeed Studio, "XIAO ESP32C6 Getting Started," 2024.  
[2] Adafruit, "Adafruit 9-DOF Absolute Orientation IMU Fusion Breakout - BNO055," 2024.  
[3] Espressif Systems, "ESP32-C6 Datasheet," 2024.  
[4] Tower Pro, "SG90 9g Micro Servo Datasheet," 2023.  
[5] Pololu, "Li-Po Battery Basics," 2024.
