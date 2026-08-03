# Prieto Engineering Projects

Mechanical engineering and process-improvement case studies completed in a food-processing manufacturing environment.

These projects demonstrate my experience with:

- Mechanical design and reverse engineering
- Manufacturing process improvement
- Design under practical constraints
- Equipment prototyping and testing
- Failure analysis and risk reduction
- Collaboration with technicians, operators, management, and local manufacturers

---

## Projects

1. [Reverse-Engineering Legacy Machine Components](#1-reverse-engineering-legacy-machine-components)
2. [Open-Vessel Enzymatic Hydrolysis Test Rig](#2-open-vessel-enzymatic-hydrolysis-test-rig)
3. [Post-Cooking Shower System Redesign](#3-post-cooking-shower-system-redesign)

---

# 1. Reverse-Engineering Legacy Machine Components

### Reducing manufacturing downtime and replacement-part costs

![Components selected for the initial reverse-engineering trial](assets/images/legacy-machine-components.jpg)

## Context

The food-processing facility operated aging German manufacturing equipment from companies including Multivac, Weber, and Handtmann. Some machines had been in operation for more than 45 years.

Replacement components were expensive, slow to source internationally, and sometimes no longer commercially available. When a component failed, production could stop for weeks while the facility waited for an imported replacement or paid a significant premium for expedited sourcing.

## Problem

While shadowing a senior technician during a breakdown repair, I observed that many equipment failures were not truly unexpected.

The technician could identify recurring failure modes and knew which components were most likely to wear out based on years of practical experience. However, this knowledge had never been converted into a systematic maintenance or replacement strategy.

The failure patterns were predictable. The cost and downtime did not have to be.

## Engineering Approach

I proposed identifying the components with the highest failure frequency, reverse-engineering them, and manufacturing replacements locally.

The process involved:

1. Working with the senior technician to identify frequently replaced components
2. Inspecting worn parts and analyzing their failure patterns
3. Reconstructing the original geometry through dimensional measurement
4. Creating CAD models and engineering drawings
5. Working with local machine shops to fabricate replacement parts
6. Testing the components under production conditions
7. Revising tolerances, materials, and manufacturing requirements based on observed failures

Many of the components were rotating parts subjected to cyclic loading. Early prototypes exposed problems involving material selection, tolerances, and manufacturing methods.

One recurring issue involved components that should have been machined as monolithic parts but were instead fabricated using welded joints. These joints failed under cyclic loading. We corrected the drawings and manufacturing specifications through several iterations.

## Outcome

After approximately two months of development and testing, the process became a standard operating practice at the facility.

Results included:

- **25–75% reduction in replacement-part cost**
- **Lead-time reduction from weeks to days**
- Reduced dependence on international suppliers
- Reduced unplanned manufacturing downtime
- A repeatable process for capturing technician knowledge and converting it into engineering documentation

## Engineering Takeaway

The most valuable lesson was not simply how to reproduce a machine component.

The technician already possessed extensive knowledge of the equipment and its failure modes. The engineering opportunity was to convert that undocumented operational expertise into a repeatable and scalable process.

This project reinforced my interest in connecting practical knowledge, engineering analysis, and systematic process improvement.

---

# 2. Open-Vessel Enzymatic Hydrolysis Test Rig

### Designing a safe, low-cost system for a one-time food-processing trial

![Open-vessel enzymatic hydrolysis test rig](assets/images/hydrolysis-test-rig.jpg)

## Context

A food-industry client approached the facility to conduct a contract-production trial for a new product involving the enzymatic hydrolysis of animal protein.

The process used mechanically separated chicken meat, offal, and bone material. It required:

- Elevated processing temperature
- Continuous mechanical agitation
- Controlled mixing during enzyme activation
- Equipment that could handle the material throughout the cooking cycle

The facility did not own suitable equipment and could not justify purchasing or renting specialized machinery for a single trial.

## Problem

The original concept involved a sealed vessel containing:

- A submerged heating element
- Heated biological material
- Steam generation
- A rotating agitator shaft penetrating the vessel wall

A closed design would have created pressure-related failure modes, including:

- Dynamic shaft-seal failure
- Steam leakage
- Seal blowout
- Uncontrolled pressure-vessel rupture

Based on the available materials, fabrication methods, and shop tolerances, the system could not be built with an acceptable safety margin as a sealed pressure vessel.

## Engineering Approach

Rather than attempting to strengthen the closed design, I changed the system boundary.

The vessel was redesigned as an **open, vented system operating at or near atmospheric pressure**. This eliminated pressure accumulation and removed the most severe potential failure mode.

The process temperature required for enzyme activation could still be achieved without operating above atmospheric pressure.

The agitation system used a:

- **SEW-Eurodrive inverter-duty gearmotor**
- Model: **WA30 DRS71S4BE05**
- Power: **0.37 kW**
- Voltage: **220/380 V**

The motor drove a submerged paddle attached to the rotor shaft. Variable-speed operation allowed the agitation rate to be adjusted during different stages of the hydrolysis process.

Fabrication combined:

- Existing vessel components
- Materials available at the facility
- Shop welding and fabrication
- Mechanical assembly of the motor and agitator
- Iterative testing under operating conditions

## Outcome

The resulting system successfully completed the production trial and validated the client’s product concept.

The project:

- Avoided the purchase or rental of specialized equipment
- Provided continuous agitation throughout the cooking cycle
- Achieved the required process temperature
- Removed the principal pressure-related hazard
- Enabled the facility to complete the client trial using existing resources

## Engineering Takeaway

The central lesson was that engineering under constraint does not always mean improving the original design.

When the safe version of a proposed system cannot be built using the available materials, manufacturing methods, or budget, the correct response may be to redefine the system itself.

In this case, changing the design from closed to open was more effective than attempting to manage the pressure-related failure modes directly.

### Project Media

[Watch the hydrolysis test-rig video](assets/videos/hydrolysis-test-rig.mp4)

---

# 3. Post-Cooking Shower System Redesign

### Improving consistency in smoked-sausage production

![Post-cooking shower system](assets/images/post-cooking-shower-system.jpg)

## Context

Smoked sausage production requires a controlled cold-water shower immediately after the cooking and smoking cycle.

This process, sometimes called a bloom or chill shower, helps:

- Stop the cooking process
- Set the surface color developed during smoking
- Tighten the casing
- Stabilize product texture
- Control moisture before packaging
- Reduce the product’s internal temperature

Poor control during this stage can produce inconsistent coloring, wrinkled casings, and continued cooking beyond the target internal temperature.

## Problem

The facility’s original cooling system consisted of pipes with manually drilled holes that allowed ambient-temperature water to drip over the product.

The system had several sources of variability:

- Ambient water-temperature changes
- Seasonal temperature variation
- Water-pressure fluctuations
- Uneven distribution across the product
- Dependence on operator judgment
- Limited control over cooling rate and spray coverage

The resulting product finish was inconsistent. This became particularly important when manufacturing products under a client’s brand, where surface appearance and batch-to-batch consistency were critical.

## Engineering Approach

The redesign addressed both water temperature and distribution.

### Temperature Control

I rerouted the water supply through a large reservoir located inside a cold chamber.

This replaced ambient-temperature water with a consistently chilled supply and reduced variation caused by weather, season, and facility temperature.

### Water Distribution

I replaced the drilled-pipe drip system with variable-flow spray nozzles.

The nozzles provided:

- More uniform surface coverage
- Greater control over water flow
- A repeatable spray pattern
- Adjustable operating parameters
- Reduced dependence on operator compensation

### Process Optimization

The operating parameters were refined iteratively by testing different combinations of:

- Water-inlet temperature
- Flow rate
- Spray duration
- Product core-temperature reduction
- Surface-color development
- Casing condition

The selected settings produced the most consistent balance of cooling performance and product appearance.

## Outcome

The redesigned system produced:

- More consistent surface color
- Improved casing integrity
- More uniform cooling
- Repeatable batch-to-batch results
- Reduced sensitivity to ambient conditions
- Reduced dependence on operator judgment
- Greater control over the post-cooking process

## Engineering Takeaway

This project demonstrated that relatively simple changes to process inputs can significantly improve manufacturing consistency.

By controlling water temperature and distribution, the system replaced an operator-dependent process with one that was more measurable, adjustable, and repeatable.

### Project Media

[Watch the post-cooking shower video](assets/videos/post-cooking-shower-system.mp4)

---

## About This Repository

These case studies are based on engineering and process-improvement work completed in a family-owned food-processing business.

Certain company, client, product, and equipment details may be generalized to protect confidential or proprietary information.

## Contact

**Marcus Prieto**  
Mechanical and Mechatronics Engineer

- GitHub: [engmaprieto](https://github.com/engmaprieto)
- LinkedIn: Add your LinkedIn profile
- Portfolio: Add your portfolio website
