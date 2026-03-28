## 1.
### Ethics
#### SD extract
The concept of ethical design allows students to see engineered solutions in a global context. It provides opportunities for students to become global citizens, helping them to strengthen their ability to make decisions based on an understanding of the values, principles, concepts and ideas that shape different assumptions and inform designed responses. Students also develop an ability to analyse, evaluate and critique engineered solutions. Students can consider, as part of their design, factors such as ==__inclusiveness and wellbeing__==, ensuring that the goal of the design is ==user focused==. Ethical design is broader than its relation to machines; it also encompasses ==social and psychological influences==, such as user ==experience and user-friendly interfaces, community involvement, health and safety features, accessible information, inclusivity, collaboration and the responsible use of open-source code==.
As part of ethical design, a crucial focus is placed on ==sustainability==, which encompasses ==environmental, economic and social dimensions==. Sustainable design practices consider the ==long-term impacts== of engineered solutions, aiming to ==minimise resource depletion, reduce pollution and waste generation, and promote the wellbeing of both present and future generations==. By prioritising sustainability, engineers and designers strive to create solutions that meet the needs of society without compromising the ability of future generations to meet their own needs. This involves ==adopting renewable energy sources, optimising resource efficiency, minimising carbon emissions, and designing for longevity, repairability and recyclability==. Additionally, ethical design involves engaging users in decision-making processes and ==ensuring transparency and accountability== throughout the design, implementation and maintenance phases of projects. Ultimately, sustainability is not just a component of ethical design – it is a guiding principle that shapes the entire design process, ensuring that engineered solutions contribute positively to the wellbeing of people and the planet.
The three dimensions of sustainability are:
	- **Environmental sustainability** is about ensuring that the resources of the planet are available for future generations and includes the selection of resources used for fabrication, manufacturing and production as well as resources required for use after production. It relates to addressing the needs of a system’s lifecycle without depleting resources and/or having a lasting impact on the environment.
	- **Economic sustainability** involves efficient resource use to maintain economic growth over time. This includes engineering industries’ contributions to the Australian and global economies, the creation of employment opportunities, and managing the costs of a system across its lifecycle. Considerations include comparing costs of different materials and weighing up the present and future value of resources within the system.
	- **Social sustainability** ensures that current and future generations have access to social resources such as human rights, education, political empowerment and community connection. In systems engineering, this dimension includes practising stewardship that promotes the wellbeing of both the broader community and future generations.
#### Ideas
- Needs to be able to be used by anyone, and not locked behind a paywall as such. 









WAIT HOW DO YOU KNOW THIS?
she has no right, but like who does?

Maturity is subjective. They all have different definitions of it, and youre comparing your definition to someone else's
Argument or a attack to her ego?
Youre trying to objectify a abstract aspect of humans
Its hard to put pen to paper on this
and people feel like their answer is silly or "immature"


To achieve a Raw 50, your "Investigating and Defining" folio section must be structured logically to guide the assessor through your thinking. This section covers **Criterion 1**, where you need to hit the "Very High" (9–10) indicators.

Here is the exact structure you need, broken down into four distinct sections.

### **Section 1: The Problem Statement (The Ethical Hook)**

**Goal:** Explain a problem that considers specific ethical design factors (environmental, economic, or social).

**What to write:**

You must identify a clear need or opportunity and explicitly link it to sustainability. For your automated battery dispenser, focus on the hazards of improper disposal.

- **The Issue:** Explain that batteries contain toxic heavy metals (lead, cadmium, lithium) that leach into soil if sent to general landfill.
    
- **The Ethical Consideration (Environmental/Social):**
    
    - _Environmental:_ "Improper disposal contributes to soil contamination.".
        
    - _Social:_ "Manual sorting exposes humans to leakage risks and fire hazards from short-circuited lithium cells.".
        
- **The Data:** You _must_ cite a statistic here. (e.g., "According to [Source], 90% of handheld batteries end up in landfill...").
    
- **The Opportunity:** "An automated system reduces human risk and increases recycling efficiency, directly addressing the _Environmental_ and _Social_ dimensions of sustainability.".
    

### **Section 2: Research into Factors Influencing Creation and Use**

**Goal:** Conduct research to _explain_ how specific factors influence your system.

**What to write:** Create a detailed table or series of paragraphs addressing the factors listed in the study design. You must cite standards or data for each.

| **Factor**      | **Explanation & Research Evidence**                                                                                                                                                                                                                              |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Function**    | **What it must do:** The system must identify, sort, and dispense batteries.<br><br>  <br><br>**Research:** "Existing industrial sorters use optical sensors [cite source], but for a school budget, I will investigate mechanical sorting by size (AA vs AAA)." |
| **User Needs**  | **Who is it for?** Students and teachers.<br><br>  <br><br>**Research:** "Anthropometric data indicates a bench height of 900mm is ergonomic for standing users [cite source]." The interface must be simple to avoid user error.                                |
| **Materials**   | **Sustainability Focus:** "Comparing PLA (biodegradable) vs ABS (durable). PLA selected to align with the _Environmental Sustainability_ goal of the project.".                                                                                                  |
| **Safety**      | **Crucial:** "Must comply with _AS/NZS 3000_ wiring rules.". "Voltage must be kept below 50V AC / 120V ripple-free DC to allow student work.".<br><br>+1                                                                                                         |
| **Environment** | **Operating Conditions:** "Will operate in a classroom (20°C, dry). Must be enclosed to prevent dust ingress affecting sensors."                                                                                                                                 |
| **Cost**        | **Budget:** "Components (Arduino, Steppers, Servos) must fit within a $150 limit. Economic sustainability requires cost-effective repairability.".                                                                                                               |

### **Section 3: The Design Brief**

**Goal:** Develop a brief that explains and documents the context, constraints, and considerations.

**What to write:**

This is your formal "contract" for the project.

- **Project Outline:** "I will design and construct an automated, integrated battery dispenser and sorter."
    
- **Context:** "Designed for use in a VCE Systems Engineering classroom to facilitate safe recycling.".
    
- **Constraints (Must Haves):**
    
    - "**Must** operate on a 12V DC power supply (Safety/Constraint)."
        
    - "**Must** sort AA and AAA batteries independently."
        
    - "**Must** incorporate an emergency stop button (Safety/Constraint)."
        
- **Considerations (Nice to Haves):**
    
    - "**Should** display a count of batteries sorted on an LCD screen."
        
    - "**Should** be constructed primarily of 3D-printed parts for rapid prototyping."
        
- **System Integration:** Explicitly state that the system will integrate **mechanical** parts (gears, hoppers) with **electrotechnological** control (sensors, Arduino).
    

### **Section 4: Evaluation Criteria (The "9-10" Differentiator)**

**Goal:** Develop criteria linked to parameters, _explaining_ how they align with the design brief and factors.

**What to write:**

This is the most critical table. You must link **Criterion** $\rightarrow$ **Parameter** $\rightarrow$ **Test Method** $\rightarrow$ **Justification**.

**Example Table for your Battery Project:**

|**Evaluation Criterion**|**Target Parameter (Measurable)**|**Method of Verification (Test)**|**Alignment & Justification**|
|---|---|---|---|
|**1. Sorting Efficiency**|$\ge 10$ batteries per minute|Time 3 trials of sorting 20 mixed batteries.|**Aligns with "Function":** To be practical in a classroom, the system must be faster than manual sorting.|
|**2. Sorting Accuracy**|$\ge 95\%$ correct sort rate|Run 50 known batteries (25 AA, 25 AAA) and count errors.|**Aligns with "User Needs":** High error rates would require manual checking, negating the system's purpose.|
|**3. Operational Safety**|Voltage $< 50\text{V AC}$|Measure all rails with a multimeter.|**Aligns with "Safety":** Compliance with _AS/NZS 3000_ and VCE safety regulations.|
|**4. Structural Stability**|Support load $> 2\text{kg}$|Static load test with calibrated weights.|**Aligns with "Materials":** The hopper must hold a full term's worth of batteries without deforming.|
|**5. Sustainability**|$< 5$ Watts idle power|Measure current draw with multimeter ($P=VI$).|**Aligns with "Ethical Design":** Minimizing energy consumption ensures _Economic_ and _Environmental_ sustainability.|

### **Checklist for Success**

- [ ] Did you explicitly mention "Ethical Design" or "Sustainability"?.
    
- [ ] Did you cite _AS/NZS 3000_ or _AS/NZS 3760_ in your Safety section?.
    
- [ ] Are your constraints specific (binary yes/no)?
    
- [ ] Do your evaluation criteria have numbers (parameters) attached to them?.
    
- [ ] Did you explain _why_ those criteria matter (alignment)?.




Yk how there was this new girl who kinda looked like malin? The one i showed you.
Malin took a interest in her
and she thinks im pulling the new girl away from her
And the new girl isnt helping
wdym by the new girl isnt hrlping
She is acting as if im telling her to act in some way in front of malin




malin hated and shit talk u since day 1
ask vathiny
everytime u were around she would speak khmer and say
"that one is so annying"
"THAT ONE"

![[Pasted image 20260224090600.png]]
