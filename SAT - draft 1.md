## Old idea
### Ethics
- Real critical part
- Environmental sustainability
  - Longevity of a product
  - Sourcing of the product
  - Function of a product that has environmental factors
  - Cradle to cradle, renewable
- Economic sustainability
  - Add a economical benefit
  - Does the time, material and effort viable financially``
- Social sustainability
  - How does this project support human rights and society
### Factors
|                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Factors**                             | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Function                                | This is what the system will be used for or what it will need to do.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| User needs, requirements and parameters | The system is designed to meet the needs and preferences of users or customers (the market). This involves not only ensuring that the system functions well and performs its tasks effectively but also prioritising factors such as longevity and durability. Considerations such as the size and portability of the system should also be taken into account to ensure suitability for the user. System parameters need to be identified so that they are optimised for system performance.                                            |
| Materials and components                | Appropriate materials and components must be selected that will meet user requirements and performance expectations.<br><br>This may include considerations such as aesthetics – such as colour, shape and surface finish of the covering/housing – and ensuring that components are neatly joined, wires are tied and trimmed, and connections are secured.<br><br>It is important to know what types of tools are available to allow for efficient production of the system and how these tools are used.                              |
| Environment use                         | This is where the system will be used and the conditions to which it will be subjected.                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Safety                                  | Safety must be considered at all stages of creation and use of the system. The risk assessment and management process is used to identify and minimise risk or harm for the maker or user.<br><br>This may include adherence to quality standards related to the physical characteristics and safety features of the system being created. It is essential to ensure compliance with guidelines, legal requirements or restrictions, including those pertaining to the materials used, and safety regulations, such as age restrictions. |
| Cost                                    | The system should be cost-effective. Users or customers expect both quality and value. The cost of components, housings and ongoing running and maintenance costs must be considered.                                                                                                                                                                                                                                                                                                                                                    |
| Waste and energy                        | Waste produced during creation and use should be minimised. Energy used in the production of the system and running costs also need to be kept to a minimum. This can include using the cradle-to-cradle (C2C) analysis for design development and construction and/or deconstruction.                                                                                                                                                                                                                                                   |
### Project ideas
- Tennis analyser 
  - Finds speed, spin and force applied
  - 
- Sun tracking solar panel
#### Factors for Solar panel
##### Function
- To efficiently capture the most sunlight possible throughout the day, through the use of electronic processing systems and a mechanical rotation. Be able to generate more energy than traditional solar panels, whilst the electricity usage does not offset the gain in energy. 
##### User needs
- This is a product that people who are looking into adding a solar panel system into their house or need one for whatever. This offers a better output to price ratio compared to traditional solar panels, while being slightly taller than traditional systems. This must be able to survive the elements as it is situated outside.
##### Materials
- Needs to be able to be 3d printed so that its cheap, and be able to cover all the internals such that no water and debris get in. 
##### Environmental use
- It will be used outdoors, and be exposed to heat, moisture and dust, and also weather.
##### Cost 
- $50
  - 20 - li ion battery
  - 10 - 
##### Waste and energy
- The manufacturing process will 
### Energy
### Wheel and Axle
#### Definitions
- Used to add mechanical advantage to systems
- Wheel
  - A circular object that revolves around a axel to move loads
- Axle
  - a pin or rod passing though the centre of a wheel
- Torque
  - The measurement of a force that causes a object to rotate around a object. 
#### Content
- torque is force times distance
- meaning radius times force
- Wheels can rotate each other
- RPM
#### Types
- Belts
  - v/vee belt, bunch of grooves to increase the amount of friction belt and wheel
  - Round belt
  - Toothed belt, bunch of teeth between the wheel and stuff
### Pulleys
#### Definitions
- Pulley efficiency
  - percentage of input power that is converted into actually useful power
- Tension
  - pulling force that is transmitted by a rope or cable.
#### Content
- 2 typeadws, fixed and moveable
- trading force and speed for distance 

## Things to talk about
- What type of servos 
- How will i make the system use less power?
  -  The servos need constant power to stay still
    - use of a counter weight to balance it out
    - Make the frictional force in the joint high enough such that it doesnt move.


## Intro
### 1. Investigation of a system 
#### Problem that references ethical design 
- Tennis analysers built to stay on racquets are overpriced, bulky and are not a viable product for most tennis players. It is usually made for the top 1% of people, and thus the price matches. Not only does this make such products a luxury, it creates a a systemic divide of tennis players based off financial power. 
#### Design Brief
- This system will provide feedback to tennis players regarding how they play.
- In this system, there are many smaller systems.
  - A Electronic system that manages battery level, takes data from a accelerometer and sends it via Bluetooth to a external analyser. 
  - There is a programmed system that takes the accelerometer data and uses it to understand if the shot last played was bad, okay or good. 
  - Then a Mechanical system exists to provide near instant feedback on the quality of the shot using flags hoisted near the net. 
- These systems are used to make a controlled system where the sensor, the accelerometer is used 
- A system that takes the physics behind a tennis shot and then analyses it and provides feedback in a controlled loop. Accelerometers provide data regarding the quality of the shot to a external device, which analyses it and wirelessly provides visual feedback to the player using physical flags, which the user takes in make makes their shots better over time. 
- For this to be a viable product
  - This must be affordable to most tennis players, especially amateurs and avid tennis players
  - This must be light enough such that the device isn't noticed during playing 
  - This must be strong enough to survive the stress of being continuedly processing data, and being subject to vibrations
  - This must be able to last a full tennis session
  - This must be able to wirelessly transmit data across the while tennis court. 
  - System must operate safely without any exposed elements.

| Constraints                | Requirements                                                                                                                                               |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Detection of type of swing | - Detect the type of stroke within a ±10% accuracy<br>- The accuracy must not degrade over time, and a straight linear accuracy variation must be recorded |
| Classify swing performance | - Identify the quality of a shot with >= 80% accuracy during testing<br>- Retain level of accuracy variation over testing period                           |
| Mechanical activation      | - Must be able to provide the visual feedback within seconds of a shot detection                                                                           |
| Battery Life               | - Be able to operate continuedly for a whole tennis session                                                                                                |
| Working distance           | - Must be able to transmit data wireless along the whole length of a tennis court                                                                          |
|                            |                                                                                                                                                            |
|                            |                                                                                                                                                            |


| Criterion             | Testing Method           | Success Standard             |
| --------------------- | ------------------------ | ---------------------------- |
| Detection accuracy    | Controlled swing trials  | ≥ 85% correct classification |
| Response time         | Time measurement         | ≤ 1.5 s                      |
| Mechanical durability | Repeated activation test | ≥ 100 cycles                 |
| Weight compliance     | Digital scale            | ≤ 150 g                      |
| Wireless reliability  | Range testing            | ≥ 10 m stable transmission   |
#### Research
- How long is a average tennis session
  - 2 hours - Expert Tennis player (Alex Tong )




## Research - Suggested questions
### 1. Design Brief & Constraints (Foundation Problems)
- What measurable performance variables define “stroke quality”?
  - Stroke
- What is the acceptable added mass on a tennis racquet before swing feel changes?
- What is the maximum allowed cost?
- What runtime is realistically required (training session length)?
- What safety standards apply to small LiPo-powered wearables?
- What environmental conditions will it operate in (heat, sweat, impact)?
### 2. Mechanical System Research Problems
#### Mounting & Structural
- What peak acceleration does a racquet head experience during a serve?
- What retention force is required to prevent detachment?
- How does added mass affect moment of inertia?
- Where should the device be mounted (throat, frame, handle)?
- What materials absorb vibration without distorting sensor data?
- How to design a clip that fits multiple racquet thicknesses?
#### Durability
- Impact shock tolerance required?
- 3D print material choice (PLA vs PETG vs ABS)?
- Screw fastening vs snap-fit vs clamp?
### 3. Sensing & Measurement Problems
#### Measurement Definition
- What exact variables must be captured?
    - Angular velocity?    
    - Linear acceleration?
    - Impact impulse?
    - Spin rate?
#### Sensor Requirements
- Minimum sampling rate to capture tennis impact (~1–5 ms event)?
- Required accelerometer range (±16g? ±32g? ±100g?)
- Gyroscope range (±2000°/s?)
- Noise density tolerance?
- Need for magnetometer?
#### Signal Processing
- How to filter high-frequency noise?
- What filtering method (low-pass? complementary filter? Kalman filter?)
- How to detect impact from raw data?
- How to calibrate IMU drift?
### 4. Processing System Problems
- How much RAM is required to buffer high-frequency data?
- Can the MCU process data in real-time?
- Should processing occur on-device or on phone?
- Required clock speed?
- Interrupt handling requirements?
- Power consumption vs performance tradeoff?
### 5. Power System Problems
- What is total current draw (MCU + IMU + BLE + servo)?
- What battery capacity gives 2–3 hours runtime?
- Peak current during servo actuation?
- Charging circuit requirements?
- Over-discharge protection needed?
- Heat dissipation inside enclosure?
You should calculate:  
Total mAh required.
### 6. Communication Problems (Bluetooth)
- BLE vs Classic — which is lower power?
- Required data rate for 1000 Hz streaming?
- Acceptable latency for “real-time” feedback?
- Packet loss risks?
- Antenna orientation effects?
- Interference from body or racquet frame?
### 7. Feedback System Problems (Critical for Part 2)
- What type of mechanical movement?
    - Servo-driven flag?
    - Rotating dial?
    - Sliding indicator?
- Required torque for visible motion?
- Actuation time?
- Power spike during movement?
- Visibility distance?
- Is feedback immediate or post-stroke?
Also
- Human factors: can players see feedback mid-rally?
- Does it create distraction risk?
### 8. Software Architecture Problems
- How to structure firmware (state machine)?
- Calibration mode?
- Data logging structure?
- Error handling?
- Fail-safe behaviour if Bluetooth disconnects?
### 9. System Integration Problems
- EMI between servo and IMU?
- Vibration affecting sensor accuracy?
- Wire strain relief?
- Enclosure space constraints?
- Thermal buildup?
### 10. Validation & Testing Problems
- How will you validate accuracy?
- What baseline will you compare against?
- Repeatability testing?
- Controlled lab test vs field test?
- How many trials for statistical reliability?
### 11. Ethics & Risk Problems (Often Overlooked)
- Lithium battery safety
- Risk of distraction causing injury
- Data privacy (if app used)
- Competitive fairness
### 12. Manufacturing & Practicality Problems
- Can all parts be 3D printed?
- Assembly sequence?
- Maintenance access?
- Component replacement?
- Cost of prototyping iterations?
### 13. Economic Feasibility
- BOM cost breakdown
- Is <$50 realistic?
- Are parts locally available?
- Shipping time risk?
## 1. 
### 1.1 The Design Brief
#### 1.1.1 Problem Identification (Define and document a specific problem that requires a systems engineering response.)
Tennis players often lack access to objective real time feedback during training. As a way to counter this, professionals often opt to utilise commercially or custom made stroke-analysis systems, which are predominantly engineered for the elite, high-income demographics. These existing solutions are not only cost-prohibitive but often physically intrusive; their excessive mass and volume directly alter the racquet's moment of inertia and swing weight, which corrupts the player’s biomechanical kinetic chain. There is a critical engineering need to develop a localized, integrated and controlled mechatronic system, that is low mass and has a negligible footprint so the execution of the stroke is not degraded. This system must capture kinetic data and provide immediate, open-loop feedback, while being financially accessible to the socioeconomically disadvantaged end of the spectrum. 
#### 1.1.2 Ethical Considerations: (Explicitly address an ethical dimension related to the problem (environmental, economic, social, psychological, or accountability).
The development of this system is driven by the ethical principle of distributive justice within sporting. Currently biomechanical feedback is a luxury commodity, which creates a stratification of technology where athletes of a lower socio-economic standing, will be severely disadvantaged compared to people who can afford this level of analysis. 
- Existing similar proprietary systems such as the Koolang Smart tennis sensor [5] cost $120 and similar products cost upwards of $200. Professionals and high end players use a variety of high speed camera sensors and $5000+ smart racquets. If optimal form can only be verified though expensive sensors, the tennis ability of players becomes a function of their wealth. This project addresses the accountability of engineers to design for the greater majority of the people, ensuring that tennis ability does not become a tool for further social divide based of purchasing power 
- There is a psychological dimension to a open loop feedback system, often provided by coaches. Human feedback is often subject to bias and subjective views; a coach may state that a shot is bad even though it is perfectly fine because it isn't "their method". Tennis is a game where everyone brings a different playstyle to the table and this can only be helped through a impartial analysis of play style. By providing a integrated system that provides unbiased feedback on a shot by instead basing it on smoothness and flow, athletes gain physical autonomy by being a active analyst of of their own mechanical data. 
- From a sustainability lens, the system must adhere to goals 11, 12 and 13 of the UNSDGs [6]. This means that the entire system must be replaceable and repairable with discarding the whole assembly, minimising the overall environmental impact. It must also try to use sustainable and recycled sources when it can, and avoid wastage of electricity. 
- Additionally, the system will need to minimise injury and physiological damage. This means that the system should not reward the raw power, but 'mechanical efficiency' which is sustainable to the human body to protect the user's wellbeing when using the system. This shifts the view of the player from trying to hit harder, to trying to hit with better form, which is better for the physical health of the athlete [7].
#### 1.1.3 Context and Factors
The system proposed is a tennis analyser with it's intended audience being both amateur and experienced tennis players. This means that it will need to survive the Environment of many different types of tennis courts and the stress from tennis rallies, all whilst being accurate, reliable and not a nuisance to the player. 
##### Biomechanical and Anthropometric Factors (Mass and Volume Constraints)
- The system will directly interact with the racquet or the player, where the components of the system might interfere with the tennis being played. Furthermore, players utilise various playstyles, and grip alignments, that require unobstructed physical access to the handle's base levels.
- Any localised additions of mass or volume at certain masses reduces Maneuverability, increases muscle fatigue and causes diminished power [8], [9]. This alter the static balance of the player and will cause ergonomic discomfort over time. 
- To fix this, the physical dimensions and total mass of the integrated system must remain functionally imperceptible to the user, seamlessly integrating with the existing spatial geometry of the racquet and player. 
##### Kinetic and Environmental Factors (Durability Constraints)
- The system will be deployed in a environment, categorised by many repetitive violent kinetic impacts. The collision between the tennis ball and the strings generates severe, high frequency shockwaves that travel down the racquet and through the arm. Tennis players also sweat a lot, and if the electronic components are exposed to human sweat, it's corrosive nature may degrade or even break the components. 
- Whilst the soft nature of the human body is generally quite good at absorbing and dissipating vibrations, hard wired and soldered electronics are quite hard and will break and not work properly after impacts, especially special geometry sensors which are pivotal for this system. Additionally sweat or water can damage the electronics
- To fix this, the internal architecture of the system must incorporate mechanical shock attenuation to isolate the delicate microcontrollers and sensors, and guarantee survivability from fluids. 
##### Operational and Temporal Factors (Power and Latency Constraints)
- Tennis is played in off grid environments for extended periods of time, and the system must act as a immediate, unbiased surrogate for a human coach
- The system cannot rely on external power infrastructure, and cannot afford processing bottlenecks. If the feedback takes too long, the telemetry is useless for immediate biomechanical correction. 
- The onboard power supply must possess the endurance for continuous, high-frequency data polling and wireless transmission for the entirety of a standard training macrocycle. The system must process and transmit kinetic information with near-zero latency, ensuring the feedback is delivered instantaneously to the user interface. 
### 1.2 Research and Investigation  
#### 1.2.1 Factor Analysis: Conduct research to investigate how specific factors influence the use and creation of an integrated and controlled system.
- At max, players add up to 27g [4] of extra weight to their racquets and barely any on their body. The 17g comes from the addition of "heat shrink sleeves" and 5-10g of "lead weights" meaning that any proprietary systems should not weigh much more than existing alterations.
- A good stroke is a rather objective analysis, however, we can define it as
  - If the acceleration vector aligns with the desired shot path [2]. Hence the direction of impulse on the racquet must be in the same or similar plane of direction as the velocity vector right before impact
  - If the player has racquet lag [2], [3] . This Is registered as a period of near zero net acceleration on the racquet, followed by a sudden increase in acceleration. 
  - If the peak angular velocity happens within +-15 ms of the impact with the ball [2].
- The collision between a tennis ball and the string bed at velocities exceeding 100 km/h generates high-frequency impacts[10]. The racquet handle acts as a primary conduit for these shockwaves, subjecting the butt cap to instantaneous deceleration forces frequently exceeding 30g [11].
  - Because rigid microelectronics will fracture under repetitive 30g loads, the system’s physical architecture must incorporate mechanical shock attenuation to decouple the PCB from peak impact frequencies, preventing zero-calibration drift in the inertial sensors.
#### 1.2.2 System Analysis
- Peak angular velocity occur within a highly localized ±15ms  window surrounding ball impact [12], [13]
  - Any viable microcontroller and IMU subsystem must communicate via a high-bandwidth protocol capable of sustaining a minimum data sampling rate of 100Hz (10ms intervals), with an optimal target of ≥200Hz (5ms intervals) for high-fidelity stroke digitization.
 ### 1.3 Evaluation Criteria
- **1.3.1 Criteria Construction:** Develop a set of criteria to evaluate the operational system and your use of the systems engineering process.
- **1.3.2 Linking Parameters:** Link each criterion to the parameters, constraints, and considerations identified in the design brief.
- **1.3.3 Operationalization:** Document how each criterion will be checked or tested during the development and realization of the system.
- **1.3.4 Justification of Relevance:** Provide a justification for the relevance of the criteria to the design brief and the engineering process. 
## 2. Research
In 1.1 to 1.2, the key considerations for this project were discussed. From this it is evident that the system must perform a few major functions; take data from a tennis shot, process it, Transmit it (perhaps via Bluetooth), and then provide feedback to the player. Then more limitations arise, where it must be imperceivable, long lasting, durable, accurate, and fast. To solve all these issues, proper research must be done, to identify the components, processes and pathways required to meet the criterion. 
### 2.1 - Components
For this project to work, that basic components that make up the project need to be analysed. 
#### 2.1.1 - Processor
First the microcontroller that we need to use should be discussed. The baseline limitations for what microcontroller we use comes down to power consumption and size. It needs to be small and be able to last a long time. We need to choose between 4 possible options that match these requirements. 
##### SEEED Studio XAIO ESP32-C3
- 400KB ram
- BLE 5.0
- 4MB flash
- Lithium battery charging chip
- single core
##### SEEED Studio XAIO ESP32-C6
- 512KB SRAM
- 4MB Flash
- 2 cores, High performance and low power
- 
##### Silicon Labs SiWx91
##### Arduino Nano ESP32
##### Comparison
###### Table 2.2.1

| Feature        | ESP32-C3 (XIAO)                                                              | ESP32-C6 (XIAO)                                  | SiWx917 (Module)                                                              | Arduino Nano ESP32                                    |
| -------------- | ---------------------------------------------------------------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------- | ----------------------------------------------------- |
| Dimensions     | 21 x 17.5 mm                                                                 | 21 x 17.5 mm                                     | 7 x 7 mm <font color="#ff0000">(SoC only)                             </font> | <font color="#ff0000">45 x 18 mm</font>               |
| Idle Power     | <font color="#ff0000">~43.5 µA (Deep Sleep)</font>                           | <font color="#2DC26B">~15 µA (Deep Sleep)</font> | <font color="#2DC26B">< 1 µA (Deep Sleep)</font>                              | ~7–10 µA (Chip only)                                  |
| Bluetooth?     | Yes (5.0 LE)                                                                 | Yes (5.3 LE)                                     | Yes (5.4 LE)                                                                  | Yes (5.0 LE)                                          |
| Power Mgmt?    | <font color="#00b050">Yes (LiPo Charger)                             </font> | <font color="#00b050">Yes (LiPo Charger)</font>  | <font color="#ff0000">No (Internal LDO only)</font>                           | <font color="#ff0000">No (Buck converter only)</font> |
| Price (Approx) | $8 – $11 AUD                                                                 | $10 – $13 AUD                                    | $12 – $15 AUD (Module)                                                        | <font color="#ff0000">$32 – $38 AUD</font>            |
| Additional     | RISC-V; hobbyist fave                                                        | Wi-Fi 6, Matter, Efficiency cores                | Ultra-Low Wi-Fi Keep-Alive                                                    | Dual-core S3; official support                        |
| Weight         | ~2g                                                                          | ~2g                                              | >1g                                                                           | <7g                                                   |
From the table we can see a breakdown of the positive qualities and the negative qualities of each board. Firstly we can immediately cut out the SiWx917. The SiWx917 only exits as a chip, meaning that we would need to design a board and everything for it, which would drive up the price. Next, we can remove the Arduino Nano ESP32. This esp32 is firstly way too large to be justified and may interfere with the player, it is too expensive and is we use this, the project cannot fit the budget. It is also the heaviest on the list. We we can also justify not using the SiWx917 and the Arduino Nano Esp32 as they are the only boards that don't have a onboards power management system, meaning that a additional board if needed to facilitate power management.  
This leaves us with the ESP32-C3 and ESP32-C6. The ESP32-C3 is cheaper, however to retain a longer battery life it is more beneficial to choose the system with the lower power draw. Both systems weigh approximately the same, and have the same dimensions. So now its a matter of comparing the lower price of the ESP32-C3 to the more advanced Bluetooth of the ESP32-C6 and its lower power draw. I believe that the extra ~$2 is worth the upgrades, especially with the efficiency cores. This is why the ESP32-C6 will be chosen as the main microcontroller of the system. 
#### 2.1.2