## 1. The Ethical Problem & Context
### 1.1 The Systemic Divide: 
Explain the exact financial barrier to entry for current tennis telemetry (e.g., SwingVision subscriptions, $200+ dedicated sensors). Explain how this creates a purely financial ceiling for amateur athletes
Many Tennis players aim to get better
### 1.2 The Ethical Intervention:** 
Document how your proposed system (open-source architecture, 3D-printed gears, low-cost microcontrollers) directly dismantles this paywall.

### 2. Research and Factor Investigation

The 9-10 band requires you to conduct research and use it to _explain_ how these factors influence the creation of the system. You cannot pull numbers out of thin air.

- **2.1 Biomechanical Factors:** Research the maximum G-force of a tennis racquet at impact. (If a racquet hits 50Gs, your chosen 16G accelerometer is useless). Use this research to justify your sensor choice.
    
- **2.2 Environmental & Wireless Factors:** Research Bluetooth Low Energy (BLE) attenuation. A tennis court is 23.77m long. Document how body-blocking and outdoor interference dictate the need for a specific antenna or transmission protocol on your Base Station.
    
- **2.3 Weight & Kinematic Factors:** Research racquet swingweight (I=∑mi​ri2​). Document that adding more than 15g to the frame fundamentally ruins the player's biomechanics, which explicitly justifies _why_ you moved the mechanical systems (the cam and rack) off the court to a Base Station.
    

### 3. The Design Brief

Now you define the "integrated and controlled system".

- **3.1 System Architecture:** Clearly define the two distinct sub-systems.
    
    - _Sub-system A (Data Acquisition):_ The sub-15g electronic module on the racquet.
        
    - _Sub-system B (Mechanical Output):_ The Base Station housing the rack-and-pinion slider and the cam-driven chime.
        
- **3.2 The Feedback Loop:** Document exactly how data flows from the accelerometer, through the microprocessor, across the BLE protocol, and into mechanical actuation.
    

### 4. Constraints and Considerations

You must _explain and document_ these. Use a table, but do not use vague adjectives.

- **Constraints (Non-negotiable limits):**
    
    - _Cost:_ Total BOM (Bill of Materials) must be < $60 AUD to satisfy the ethical brief.
        
    - _Mass:_ Racquet module must be ≤ 15g.
        
    - _Latency:_ Mechanical actuation must occur within ≤ 1.5 seconds of impact.
        
- **Considerations (Flexible targets):**
    
    - _Aesthetic:_ The Base Station should be highly visible in outdoor sunlight (e.g., using high-contrast yellow 3D filament for the slider).
        
    - _Power:_ Ideally rechargeable via USB-C rather than relying  on disposable batteries.
        

### 5. Evaluation Criteria Alignment

This is where students lose marks. You cannot just list parameters; the 9-10 band states you must **develop evaluation criteria and link them to relevant parameters, explaining how they align with the design brief**.

Your table needs these exact columns:

| Criterion             | Target Parameter            | Testing Method                      | Alignment/Justification (The "Why")                                                                                                                            |     |
| --------------------- | --------------------------- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| **Weight Compliance** | Racquet module ≤ 15g        | Digital scale measurement           | _Alignment:_ Ensures the system remains unobtrusive, adhering to the biomechanical research (Section 2.3) and fulfilling the user requirement for normal play. |     |
| **Actuation Latency** | ≤ 1.5s from impact to chime | High-speed camera/timestamp logging | _Alignment:_ Average time between strokes in a rally requires near-instant auditory feedback to be useful for behavioral correction.                           |     |
