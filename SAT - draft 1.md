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
  - Does the time, material and effort viable financially
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
#### 1.3.1 & 1.3.2 Criteria Construction and Linking Parameters
The following criteria have been developed to evaluate the system's performance against the constraints identified in 1.1 and 1.2.
##### Table 1.3.1: Evaluation Criteria and Parameter Linkage

| Evaluation Criterion       | Linked Parameter / Constraint    | Success Standard (Metric)                                                                                  |
| -------------------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| System Mass - C1           | Biomechanical / Anthropometric   | Total mass added to the racquet must be ≤30g.                                                              |
| Sensing Accuracy - C2      | Functional / Data Fidelity       | ≥85% accuracy in identifying "Good" vs "Bad" strokes compared to coach analysis.                           |
| Feedback Latency - C3      | Operational / Temporal           | Feedback must be given within ≤500ms of ball impact.                                                       |
| Mechanical Durability - C4 | Operational / Temporal           | System must maintain structural integrity after 100 high power shots                                       |
| Economic Viability - C5    | Social / Economic Sustainability | Total cost for the sensor unit must be ≤$50 AUD.                                                           |
| longevity - C6             | Operational / Temporal           | System must last at least 2 hours of playing, and constantly provide feedback for the duration of playing. |
#### 1.3.3 Operationalisation (Testing Methods)
To verify that the system was successful, the following testing measures will be taken. 
- (C1) The integrated sensor unit and its mounting bracket will be weighed using a digital scale. This ensures accuracy and helps us understand if the system is obtrusive. 
- (C2) 50 controlled strokes will be recorded using a camera, and then judged by a professional tennis coach. The software's classification output will be compared against the coach's evaluation to calculate the success percentage.
- (C3) Using a camera, the number of frames between the moment of ball-string contact and the final actuation of the mechanical flag will be counted.
- (C4) The system will be subjected to a stress test consisting of 100 consecutive smashes or a selection of very kinetically heavy shots. Then after the test, the 9DOF calibration data will be checked for any kind of drift.
- (C6) The system will be used constantly for 2 hours straight in a tennis match, and the battery, and operation will be analysed.
#### 1.3.4 Rubric for testing

| Test | 3            | 2            | 1            | 0               |
| ---- | ------------ | ------------ | ------------ | --------------- |
| C1   | under 20g    | under 25g    | under 30g    | Over 30g        |
| C2   | 90% Accuracy | 80% Accuracy | 70% Accuracy | under 70%       |
| C3   | Under 150ms  | Under 200ms  | under 250ms  | more than 250ms |
| C4   | 90% Accuracy | 80% Accuracy | 70% Accuracy | under 70%       |
| C5   | Under 40$    | under 45$    | Under 50$    | Over 50%        |
| C6   | >2 Hours     | 1.5-2 Hours  | 1-1.5 hours  | <1 hour         |
To be successful, the System must get a combined score of over 78%, or 14/18 total available points. This does not leave much room for leniency. 
#### 1.3.5 Justification of Relevance
The relevance of these criteria is rooted in the engineering requirement for a "seamless" user experience.
1. C1 (Mass) - A racquet's "feel" is sensitive to even minor weight changes. Exceeding 30g shifts the balance point toward the handle, which could cause a player to swing "early," effectively corrupting the very biomechanics the system is trying to analyse.
2. C2 & C4 (Accuracy) - If the system isn't accurate, it serves no purpose to its intended audience to tennis players. 
3. C3 (Latency) -  In high-intensity training, feedback must be immediate to allow for "muscle memory" adjustment. If the flag raises after the player has already reset for the next shot, the cognitive link between the action and the result is severed.
4. C5 (Ethics/Sustainability) - Since this project aims to address "distributive justice" in sports, the system must remain affordable and repairable. A device should be cheap to buy and viable, as if it, creates long-term costs that the intended "socioeconomically disadvantaged" user cannot sustain.
5. C6 (Usability) - If the system doesn't even last a hour, it once again serves no purpose to tennis players, as tennis training lasts way longer than a hour.
## 2. Research
In 1.1 to 1.2, the key considerations for this project were discussed. From this it is evident that the system must perform a few major functions; take data from a tennis shot, process it, Transmit it (perhaps via Bluetooth), and then provide feedback to the player. Then more limitations arise, where it must be imperceivable, long lasting, durable, accurate, and fast. To solve all these issues, proper research must be done, to identify the components, processes and pathways required to meet the criterion. 
### 2.1 - Components
For this project to work, that basic components that make up the project need to be analysed. 
#### 2.1.1 - Processor
First the microcontroller that we need to use should be discussed. The baseline limitations for what microcontroller we use comes down to power consumption and size. It needs to be small and be able to last a long time. We need to choose between 4 possible options that match these requirements. 
##### SEEED Studio XAIO ESP32-C3 - [18]  [19]
- 400KB ram
- BLE 5.0
- 4MB flash
- Lithium battery charging chip
- single core
##### SEEED Studio XAIO ESP32-C6 - [18]
- 512KB SRAM
- 4MB Flash
- 2 cores, High performance and low power
- Lithium Battery charging chip
##### Silicon Labs SiWx91 - [17]
- 8MB flash
- 8MB PSRAM
- 22 µA current draw
- WIFI 6
- Dual core
##### Arduino Nano ESP32 - [16]
- Dual core 240Hz
- WIFI 4
- 14 Digital pin 
- 16Mb external flash
##### Comparison
###### Table 2.1.1

| Feature        | ESP32-C3 (XIAO)                                                              | ESP32-C6 (XIAO)                                  | SiWx917 (Module)                                                              | Arduino Nano ESP32                                    |
| -------------- | ---------------------------------------------------------------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------- | ----------------------------------------------------- |
| Dimensions     | 21 x 17.5 mm                                                                 | 21 x 17.5 mm                                     | 7 x 7 mm <font color="#ff0000">(SoC only)                             </font> | <font color="#ff0000">45 x 18 mm</font>               |
| Idle Power     | <font color="#ff0000">~43.5 µA (Deep Sleep)</font>                           | <font color="#2DC26B">~15 µA (Deep Sleep)</font> | <font color="#2DC26B">< 1 µA (Deep Sleep)</font>                              | ~7–10 µA (Chip only)                                  |
| Bluetooth?     | Yes (5.0 LE)                                                                 | Yes (5.3 LE)                                     | Yes (5.4 LE)                                                                  | Yes (5.0 LE)                                          |
| Power Mgmt?    | <font color="#00b050">Yes (LiPo Charger)                             </font> | <font color="#00b050">Yes (LiPo Charger)</font>  | <font color="#ff0000">No (Internal LDO only)</font>                           | <font color="#ff0000">No (Buck converter only)</font> |
| Price (Approx) | $8 – $11 AUD                                                                 | $10 – $13 AUD                                    | $12 – $15 AUD (Module)                                                        | <font color="#ff0000">$32 – $38 AUD</font>            |
| Additional     | RISC-V; hobbyist fave                                                        | Wi-Fi 6, Matter, Efficiency cores                | Ultra-Low Wi-Fi Keep-Alive                                                    | Dual-core S3; official support                        |
| Weight         | ~2g                                                                          | ~2g                                              | >1g                                                                           | <7g                                                   |

From the table we can see a breakdown of the positive qualities and the negative qualities of each board. Firstly we can immediately cut out the SiWx917. The SiWx917 only exits as a chip, meaning that we would need to design a board and everything for it, which would drive up the price. Next, we can remove the Arduino Nano ESP32. This esp32 is firstly way too large to be justified and may interfere with the player, it is too expensive and is we use this, the project cannot fit the budget. It is also the heaviest on the list. We  we can also justify not using the SiWx917 and the Arduino Nano Esp32 as they are the only boards that don't have a onboards power management system, meaning that a additional board if needed to facilitate power management.  
This leaves us with the ESP32-C3 and ESP32-C6. The ESP32-C3 is cheaper, however to retain a longer battery life it is more beneficial to choose the system with the lower power draw. Both systems weigh approximately the same, and have the same dimensions. So now its a matter of comparing the lower price of the ESP32-C3 to the more advanced Bluetooth of the ESP32-C6 and its lower power draw. I believe that the extra ~$2 is worth the upgrades, especially with the efficiency cores. This is why the ESP32-C6 will be chosen as the main microcontroller of the system. In the case that the system starts to creep above budget, this will be reverted to the ESP32-C3
#### 2.1.2 - Accelerometer
Next, the accelerometer that will be used needs to be finalised. While there are not many specifications required for our accelerometer, we still need it to be cheap, largely accurate, and fit within our system. For a metric, we can assume that the maximum size of the accelerometer is the size of the SoC chosen, namely the ESP32-C6, with a size of 21 x 17.5 mm. 
##### GY-91 (MPU-9250 + BMP280) [20]
- 20.5 x 14.3 mm
- 9-axis (Accel/Gyro/Mag) plus a Barometer (10-DOF total).
- ~$7.60 – $8.50
##### BNO085 (9-DOF AHRS) [21]
- ~20 x 15 mm
- 9-axis with an onboard ARM Cortex-M0 processor
- ~$9.40 – $12.00
##### BNO055 (Absolute Orientation) [22]
- ~20 x 12 mm
- 9-axis Absolute Orientation
- ~$10.30 – $14.50
- It outputs Euler angles and Quaternions directly
##### Comparision
###### Table 2.1.2
| Module                            | Dimensions                                  | Key Features                                                                | Price (AUD)                                 |
| --------------------------------- | ------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------- |
| **GY-91 (MPU-9250 + BMP280)**     | <font color="#00b050">20.5 x 14.3 mm</font> | 9-axis (Accel/Gyro/Mag) + Barometer (10-DOF total)                          | <font color="#00b050">~$7.60 – $8.50</font> |
| **BNO085 (9-DOF AHRS)**           | <font color="#00b050">~20 x 15 mm</font>    | 9-axis with onboard ARM Cortex-M0 processor                                 | ~$9.40 – $12.00                             |
| **BNO055 (Absolute Orientation)** | <font color="#00b050">~20 x 12 mm</font>    | 9-axis; <font color="#00b050">outputs Euler angles and Quaternions directly | ~$10.30 – $14.50          </font>           |
All of the options for IMUs are perfectly viable for the project. So the decision of what IMU to use goes down to Price and additional features. The feature that caught my eye was the automatic Quaternion output of the BNO055. This feature helps reduce the amount of software that needs to be built to help analyse the tennis stroke, and this will help in the production. However it is nearly double the cost of the GY-91. The question arises weather the extra up to 7 dollars are worth the ease of software development. 
The tie-breaker here would be overall power draw. As there will be limited battery capacity, we should look at the option that minimises total power usage. On paper, the BNO085 draws marginally less power on average usage, however, the BNO055 has onboard quaternion synthesis. If the task of the quaternion processing was given to the SoC instead, the computation would take significantly more power than onboard the BNO055, as the BNO055 has its components specialised to to compute quaternions in the most efficient manner. This is why the BNO055 will be selected.
#### 2.1.3 - Battery
For the battery, we need to both decide what kind of battery we will be, and how big it'll be. The limitations that need to be met are the limited space available, minimising the total mass of the battery, and making sure that it lasts long. A few options for the type of battery were:
##### Li-ion (Cylindrical - 14500)
- Standard "AA" size but 3.7V.
- Extremely durable steel casing protects against impact.
- Mass: ~20g. This leaves almost zero budget for the PCB, housing, and sensor.
- Capacity: ~800mAh.
##### Li-Po (Pouch - 402030)
- Flexible flat vacuum-sealed pouch
- Highest energy-to-weight ratio.
- Mass: ~5g.
- Capacity: ~250mAh.
- Requires a rigid 3D-printed "exoskeleton" to prevent puncture during racquet vibrations.
##### Li-Po (Coin Cell - LIR2450)
- Rechargeable button cell.
- Very compact and easy to mount flush.
- Mass: ~4g.
- Capacity: ~120mAh.
- Drawback: Low discharge rate (C-rate) may cause the ESP32-C6 to brown out during BLE transmission peaks.
##### Comparison
###### Table 2.1.3

| Battery Type | Dimensions (mm)                                                   | Weight (g)                        | Capacity (mAh) | Suitability                                                          |
| ------------ | ----------------------------------------------------------------- | --------------------------------- | -------------- | -------------------------------------------------------------------- |
| Li-ion 14500 | <font color="#ff0000">50 x 14                             </font> | <font color="#ff0000">~20g</font> | 800            | <font color="#ff0000">Low - Too heavy; ruins racquet balance.</font> |
| Li-Po Pouch  | 30 x 20 x 4                                                       | <font color="#00b050">~5g</font>  | 250            | <font color="#00b050">High - Ideal weight/power balance.</font>      |
| LIR2450 Coin | <font color="#00b050">24.5 x 5</font>                             | <font color="#00b050">~4g</font>  | 120            | Medium - Risk of power failure under load                            |
|              |                                                                   |                                   |                |                                                                      |
From the data we can see that the LI-Ion Battey is definitely out of the picture as it does not fit. This leaves the coin battery and the Li-Po pouch. The major difference is the capacity, as the weight is basically the same. As the Li-Po pouch is more than double the capacity of the coin, the Pouch will be chosen.

#### Modelling
To model how the system will be configured, multiple stages of design will have to be produced. First, a flow diagram of the system must be created. This is seen in the below figure.
##### Figure 2.1.3
![[Pasted image 20260419180657.png]]
Then a basic circuit diagram was developed.
![[Pasted image 20260419180724.png]]
This basic circuit will form the basics of the electronic system.
### 2.2 - Structure
The way this project will be structured will need to be analysed. 
#### 2.2.1 - Placement
The system can be placed at various locations, each with its own weaknesses and strengths. The placement dictates the quality of the data and the mechanical stress on the hardware.

##### Comparison
###### Table 2.2.1

| Location                 | Weight/Balance Impact                 | Data Fidelity                                | Durability Risk                               | Complexity                    |
| ------------------------ | ------------------------------------- | -------------------------------------------- | --------------------------------------------- | ----------------------------- |
| **Hilt (Base of Grip)**  | Low - Near hand center.               | **High** - Captures pure racquet rotation.   | Low - Protected by hand.                      | Simple clamp mount.           |
| **Throat (Above Grip)**  | Medium - Shifts balance slightly.     | **High** - Stable orientation data.          | **High** - Risk of impact during transitions. | Custom V-mount needed.        |
| **Internal (Butt Cap)**  | Medium - Changes swing weight.        | **Medium** - Potential signal interference.  | Low - Encased in handle.                      | Requires handle modification. |
| **Lateral Frame (Hoop)** | **High** - Distorts racquet symmetry. | **Extreme** - High resolution but noisy.     | **Critical** - High vibration & ball impact.  | Minimal (Adhesive/Tape).      |
| **Wristband/Sleeve**     | **Zero** - No change to racquet.      | **Low** - Does not track racquet face angle. | **Very Low** - Safest for electronics.        | Fabric integration.           |

##### Analysis
The Lateral Frame and Internal Integration are the first to be dismissed. Mounting on the hoop creates a unbalanced weight that would ruin the player's mechanics, and the vibration at the frame risks sensor clipping and hardware failure. While internal mounting looks visually clean, the SOC’s signal would be severely affected by the handle, and the shift in the balance point (making the racquet more head-light) would change the user's existing swing timing, which doesn't align with the criterion. 
Next, we evaluate the Wristband/Sleeve option. A wrist-mounted sensor tracks the arm, not the racquet. Because of "wrist lag" and racquet flex, the arm's orientation does not perfectly map to the racquet face's orientation at the point of contact. This would lead to inaccurate spin and power analysis.
This leaves the Hilt and the Throat. The throat offers excellent data stability, but it occupies the space used by the non-dominant hand during a two-handed backhand, posing a safety risk to the player and the system.
The Hilt remains the most viable location. It provides the most accurate "raw" data of the racquet’s movement with the least amount of mechanical interference or risk of physical impact. By mounting at the base of the grip, we ensure the sensor survives high-intensity play while maintaining a linear relationship between the hand's torque and the racquet's response. Therefore, the Hilt will be the best mounting location, with a secondary focus on a low-profile 3D-printed housing to minimize the "weight" felt by the player.
#### 2.1.2 - Feedback Loop System
The player needs a system that provides instantaneous feedback. Rather than integrating feedback into the racquet—which adds weight and mechanical noise—an external mechanical "Flag" system will be analysed. 
##### Flag Hoist (Servo-Actuated)
- Uses servo motor to physically raise a coloured flag or "arm."
- **Logic:** Provides a clear, binary "Success/Fail" visual that doesn't require the player to look at their hand.
- **Drawback:** Requires a second microcontroller and power source on the sidelines.
##### Digital Text-Based Display
- A large-scale digital display that shows specific metrics like quality or speed.
- **Logic:** Provides quantitative data rather than just qualitative.
- **Drawback:** High cost and low visibility in direct sunlight unless using expensive high-nit flip-disc or E-Ink displays.
##### Speaker/Siren
- A sideline speaker that calls out stats or plays a tone.
- **Logic:** Keeps the player's eyes 100% on the ball.
- **Drawback:** Massive power requirements and potential to annoy players on adjacent courts.
##### Comparison
###### Table 2.2.4

| Feedback System           | Visibility/Clarity       | Portability | Response Latency  | Power Requirement |
| ------------------------- | ------------------------ | ----------- | ----------------- | ----------------- |
| **Flag Hoisting Machine** | **High** (Mechanical)    | Medium      | Low (Servo speed) | Medium (AA/Li-Po) |
| **LED Text Display**      | Medium (Sunlight issues) | Low         | Low               | **High**          |
| **Auditory Siren**        | **High**                 | Medium      | Instant           | **High**          |

##### Analysis
The Auditory siren seems like one of the best options, however, the location that this system is going to be needs to be understood. In a high stakes tennis environment, a siren is not going to be the most effective form of communication as auditory input will most likely be ignored by players during rallies. Additionally, the use of a siren may interfere with the mind-body connection that is perceived when hearing the ball bounce, throwing the player off. 
Then, the text display also looks promising, however, for this project we must be practical. The system will be used outdoors in broad daylight, where leds will struggle to output enough light to be visible, especially with glare. And even if they do output enough, it would be distracting. 
This leaves the flag system, which utilises various colours to indicate what the shot quality was. The only problem with this, is that the servos responsible for hoisting the flag will take time, which is something that needs to be worked on.
#### Diagram of flag system
##### figure 2.2.4
![[Pasted image 20260420084815.png]]
The flags will be controlled by 2 servos, which will pull up either a red or green flag, to indicate the quality of the shot. 
### 2.3 - Physical Structure.
Since, a racquet placed butt mount was decided, new complications arise. First, the structure of the system must be durable, waterproof and able to survive the elements, dissipate heat effectively, and stay attached to the racquet at all times. 
#### 2.3.1 - Housing material
The housing of the system needs to be able to dissipate vibrations, be sturdy enough to not damage the system upon scenarios such as dropping the racquet and water and dust resistant to a certain extent. It also needs to be light as possible.
##### TPU
##### PLA
##### PETG
##### ABS
##### Comparison
###### Table 2.3.1 – Material Properties and Suitability

| Material  | Price (AUD/kg) | Hardness / Flexibility      | Tensile Strength | Impact / Fatigue Resistance  | Heat Resistance | Water / Sweat Resistance | Print Difficulty | Key Problems                         |
| --------- | -------------- | --------------------------- | ---------------- | ---------------------------- | --------------- | ------------------------ | ---------------- | ------------------------------------ |
| PLA       | $15–$25        | High stiffness, brittle     | Medium (~60 MPa) | Low (cracks under vibration) | Low (~60°C)     | Poor–Moderate            | Very Easy        | Brittle failure, poor fatigue life   |
| PLA+      | $20–$35        | Slightly more ductile       | Medium–High      | Medium                       | Low–Medium      | Moderate                 | Easy             | Still degrades under repeated shock  |
| PETG      | $25–$40        | Moderate stiffness, ductile | Medium (~50 MPa) | **High** (absorbs impact)    | Medium (~80°C)  | **High**                 | Easy–Medium      | Slight flex (less rigid than PLA)    |
| ABS       | $25–$40        | Tough, semi-flexible        | Medium           | High                         | High (~100°C)   | Moderate                 | Hard             | Warping, poor dimensional accuracy   |
| TPU (95A) | $35–$60        | **Flexible (rubbery)**      | Low–Medium       | **Very High (damping)**      | Medium (~80°C)  | **High**                 | Medium–Hard      | Too flexible → unstable sensor frame |


Our goal is to minimise the amount of vibrations that pass through the racquet into the 



While TPU is the preferred damping material, TPE can be utilised as an alternative by restricting its use to a thin, mechanically constrained interface layer. This ensures effective vibration reduction while preventing excessive deformation that would otherwise degrade IMU accuracy.
#### 2.3.2 - Mounting method
Now the way the system will be attached to the racquet will need to be finalised. It needs to be as small as possible, secure, lightweight and non-intrusive.

#### 2.3.3 - Design Software

## 3 - Planning
### 3.1 - Baseline timeframe
First we need to create a baseline timeframe for the project. Since this project is due around the start of October. So we set a baseline final submission date of the end of term 3 holidays, or 4th of October 2026. Additionally, part 1, 2 and 3 are due around the first of June. To ensure that we stay on track, we can assume that the submission of this is earlier and is around the end of May. It is evident that the logical ordering of the project is the order of the parts, such that to do part 2, part 1 must be done and so on. However, since each part has many overlap, we can work on a few adjacent parts at once. 


# to add
- Layout of thing
- Sketch of thing
- Sizes and dimensions
- More like sketching
- Material justification
- Testing of materials
- 

















'' # Section 3: Generating and Designing

## 3.1 Design Thinking Process

The generation of design options applied creative, critical, and speculative thinking to address the design brief's requirement for an affordable, low-mass, integrated system that provides real-time biomechanical feedback to tennis players.

| Thinking Mode   | Application to Design Brief                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------- |
| **Creative**    | Explored unconventional form factors and feedback mechanisms beyond existing commercial solutions  |
| **Critical**    | Evaluated each option against measurable constraints (mass, cost, latency) identified in Section 1 |
| **Speculative** | Considered future scalability, such as multi-user detection and cloud analytics                    |

---

## 3.2 Design Options Generated

Three distinct design options were developed to address the core problem: providing affordable, real-time tennis stroke feedback. Each option differs in system architecture, particularly in how feedback is delivered to the user.

### 3.2.1 Option A: Wearable Sensor with Physical Flag Feedback

**Concept:** A compact module attached to the racquet throat transmits accelerometer data via BLE to a separate Base Station positioned near the court. The Base Station uses a servo-driven mechanical flag to provide immediate visual feedback.

#### Block Diagram (IPO Model)
```
┌─────────────────────────────────────────────────────────────────────────┐
│                         OPTION A: PHYSICAL FLAG                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   INPUT              PROCESS                OUTPUT                      │
│   ═════              ══════                ══════                       │
│                                                                         │
│  ┌─────────┐        ┌──────────┐         ┌─────────────┐                │
│  │ Racquet │   →    │ ESP32-C6 │   →     │ Servo Motor │                │
│  │Motion   │        │ MCU +    │   →     │ (Flag Pos.) │                │
│  │         │        │ BNO055   │   BLE   │             │                │
│  └─────────┘        └──────────┘         └─────────────┘                │
│      │                  │                      │                        │
│      │                  │                      │                        │
│      ▼                  ▼                      ▼                        │
│  Accelerometer     Quaternion        Mechanical Flag                    │
│  Data (200Hz)      Processing       Position: Up/Down                   │
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
                    │  (XIAO Board)   │
                    │                 │
                    │  ┌───────────┐  │
                    │  │   BLE     │  │
                    │  │ Antenna   │  │
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



| Sensor                             | Dimensions     | Features                                                          | Price Range      |
| ---------------------------------- | -------------- | ----------------------------------------------------------------- | ---------------- |
| GY-91 (MPU-9250 + BMP280) [20]     | 20.5 × 14.3 mm | 9-axis (Accel/Gyro/Mag) + Barometer (10-DOF total)                | ~$7.60 – $8.50   |
| BNO085 (9-DOF AHRS) [21]           | ~20 × 15 mm    | 9-axis with onboard ARM Cortex-M0 processor                       | ~$9.40 – $12.00  |
| BNO055 (Absolute Orientation) [22] | <font color="#9bbb59">~20 × 12 mm    | 9-axis absolute orienta</font>tion; outputs Euler angles and quaternions | ~$10.30 – $14.50 |
''