# Week 1 - InGen Business Landscape

**Prepared by:** Ruiyuan Yin  
**Assessment date:** 13 July 2026  
**Scope:** Fari, Senpai, Sentinel Prime AI, Aido Rover, Aido Humanoid, and PIC 2.0

Cost tiers used in this report are: Tier 1 below $5,000, Tier 2 from $5,000 to $25,000, Tier 3 from $25,000 to $100,000, and Tier 4 above $100,000.

## Short overview

The five products have quite different business logic. Fari and Senpai are companion-type products. Their electricity cost should be small compared with software, content, support, privacy work, and whether people really use them. Sentinel is closer to an enterprise service because it needs monitoring, data storage, and system integration. Rover and Humanoid are heavy capital assets. For these two products, the important question is not only whether the robot can work, but whether it can complete enough useful tasks with low intervention.

For energy analysis, I do not only look at power consumption. I also look at useful output, such as cost per resident interaction, student-hour, validated security alert, completed patrol, or accepted work cycle. This makes the comparison closer to a business decision.

## 1. Fari

- **Public stage:** In development
- **Likely buyer:** Executive Director or VP of Resident Experience in a senior-living organisation
- **Main use case:** Companionship, reminders, family connection, simple wellness check-ins, and staff escalation
- **Estimated cost tier:** Tier 2, $5,000-$25,000, low confidence
- **Public cost analogue:** ElliQ membership and NAO V6
- **Energy class:** Continuous, low-to-moderate
- **Main TCO driver:** Software/service, support, privacy control, and staff adoption
- **Main competitor:** ElliQ
- **Main business risk:** The product is not mature and the real care outcome is still unclear

Fari is described by InGen as an eldercare companion robot and is still in development. In my view, the first customer is more likely a senior-living operator than one individual family. The economic buyer may be the Executive Director or VP of Resident Experience. Nursing staff, caregivers, IT, and privacy staff will also influence the decision. Fari should support daily engagement and basic reminders, but it should not be presented as an autonomous medical decision system. ([InGen product ecosystem](https://www.ingendynamics.com/))

There is no public InGen price, so I use two market references. ElliQ currently shows membership options of $39.99 and $59.99 per month, plus a $249 lease-initiation fee. This is a consumer service price and can only be a lower market reference. RobotLAB lists NAO V6 at $16,990, which gives a better reference for an institutional social robot. Based on these two points, I put Fari in Tier 2, but the confidence is low. ([ElliQ membership](https://elliq.com/products/membership); [NAO V6 Standard Edition](https://www.robotlab.com/store/nao-v6-standard-edition/))

Fari may stay powered or docked for most of the day, so I classify it as continuous, low-to-moderate energy use. No public wattage or battery information was found. Electricity should not be the main cost. The bigger cost may be software subscription, customer support, staff training, privacy/security work, and whether the staff can put Fari into the normal care workflow.

The main competitor is ElliQ because both focus on older adults and companionship. The main risk is that the product may collect sensitive information but still cannot show enough improvement in resident engagement or staff workload. If health information is handled for a regulated US healthcare organisation, HIPAA safeguards may also become relevant. ([HHS HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html))

The first pilot should answer one simple question: what resident outcome or staff task becomes better after using Fari, and what data leaves the device?

## 2. Senpai

- **Public stage:** In development
- **Likely buyer:** District CTO or Director of Curriculum and Instruction
- **Main use case:** Teacher-led STEM, coding, demonstrations, and guided learning activities
- **Estimated cost tier:** Tier 2, $5,000-$25,000, medium confidence
- **Public cost analogue:** NAO V6
- **Energy class:** Intermittent, low-to-moderate
- **Main TCO driver:** Curriculum, teacher training, support, and utilisation across classes
- **Main competitor:** NAO V6
- **Main business risk:** Schools may not see clear learning improvement or teachers may not use it often

Senpai is an educational robot in development. I do not think the correct position is “replace the teacher.” A more practical position is a reusable learning tool controlled by the teacher. The likely buyer may be a District CTO, Director of Curriculum and Instruction, or STEM/CTE Director. Teachers, principals, IT, privacy staff, and procurement will also be involved. The first use cases can be guided coding lessons, science demonstrations, language practice, or structured social interaction. ([InGen product ecosystem](https://www.ingendynamics.com/))

NAO V6 is the clearest public comparison. United Robotics Group shows NAO in education and research settings, while RobotLAB lists the Standard Edition at $16,990 with software, curriculum, warranty, and support. This supports a Tier 2 estimate for Senpai. The final price may still be very different if InGen sells it by classroom package, subscription, or school licence. ([United Robotics Group education and research use](https://unitedrobotics.group/en/news-events-press/events/united-robotics-group-at-robocup-2024-in-eindhoven); [NAO V6 Standard Edition](https://www.robotlab.com/store/nao-v6-standard-edition/))

The robot is likely used during lessons instead of operating 24 hours, so the energy class is intermittent, low-to-moderate. Charging and battery readiness are important because one failed lesson affects teacher confidence, but electricity itself should be a small cost. The largest TCO items may be curriculum updates, teacher training, repair, technical support, and low utilisation. A robot used every day by several classes has a much better cost per student than one used only for open days.

The main competitor is NAO V6 because it already has an education and research position. Senpai needs to be easier to use, cheaper in total, or better connected with school curriculum. The main risk is not hardware only. It is possible that teachers do not have time to prepare lessons, or the school cannot see measurable learning improvement. Student data is another issue because FERPA and COPPA may apply in the United States. ([FERPA](https://studentprivacy.ed.gov/ferpa); [COPPA](https://www.ftc.gov/legal-library/browse/rules/childrens-online-privacy-protection-rule-coppa))

A useful pilot should choose one curriculum-linked lesson and measure student use hours, teacher preparation time, and learning result.

## 3. Sentinel Prime AI

- **Public stage used here:** In development, based on the dedicated product page
- **Likely buyer:** Chief Security Officer or Director of Physical Security
- **Main use case:** Continuous monitoring, alert triage, evidence capture, and human response support
- **Estimated cost tier:** Tier 3, $25,000-$100,000 first-year equivalent, low confidence
- **Public cost analogue:** Knightscope K5 with KSOC, using its historical 2021 SEC revenue range
- **Energy class:** Continuous, moderate
- **Main TCO driver:** System integration, monitoring, storage, maintenance, and service
- **Main competitor:** Knightscope K5 with KSOC
- **Main business risk:** Design targets may be understood as proven performance

Sentinel has the clearest enterprise buyer among the five products, but its public maturity information is not fully consistent. The general InGen page gives a more developed impression, while the dedicated Sentinel page says “In Development” and explains that performance figures are design targets. I use the dedicated page because it is more specific and dated. This is a conservative treatment and avoids using a target as a proven result. ([InGen product ecosystem](https://www.ingendynamics.com/); [Sentinel dedicated page](https://ingendynamics.com/sentinel.html))

The buyer may be a Chief Security Officer, Director of Physical Security, or site security leader. The SOC manager, IT/cybersecurity team, privacy or legal team, facilities staff, and system integrator also need to agree. The strongest use case is not replacing all guards. It is helping with continuous sensing, sorting alerts, keeping evidence, and sending the correct event to a human operator.

No public Sentinel quotation was found. Knightscope is the closest market reference because it combines an autonomous security robot and an operations platform. In a 2021 SEC filing, Knightscope said it recognised recurring monthly revenue from $3,500 to $8,150 per ASR. The amount included rental, maintenance, service, support, data transfer, KSOC access, charge pads, and selected upgrades. This gives a historical annual range of about $42,000-$97,800. It is not a current Knightscope price and not an InGen price, but it supports a Tier 3 first-year estimate. ([Knightscope K5](https://knightscope.com/the-force); [Knightscope 2021 SEC filing](https://www.sec.gov/Archives/edgar/data/1600983/000110465921059135/tm2113857d1_partii.htm))

Sentinel needs sensors, edge computing, communication, data storage, and continuous availability. I therefore classify energy use as continuous, moderate. However, the main TCO item is more likely integration with VMS, SIEM, SOC, identity systems, and the human monitoring process. False alerts can also create hidden labour cost.

The main competitor is Knightscope K5 with KSOC. The biggest risk is that a customer buys based on target performance and later finds too many false alerts, difficult integration, or privacy problems. A pilot should use blinded event tests and agree the false-alert and response-time limits before starting.

## 4. Aido Rover

- **Public stage:** Research stage
- **Likely buyer:** Director of Site Operations, Asset Integrity, or Physical Security
- **Main use case:** Outdoor patrol and visual or thermal inspection at large sites
- **Estimated cost tier:** Tier 3, $75,000-$100,000 for the base-platform class; it may become Tier 4 after deployment
- **Public cost analogue:** Boston Dynamics Spot, using the historical $74,500 Explorer Kit launch price
- **Energy class:** Duty-cycle, high during patrol
- **Main TCO driver:** Depreciation, rugged maintenance, payloads, integration, and downtime
- **Main competitor:** Boston Dynamics Spot
- **Main business risk:** Outdoor reliability may be too low for the cost

Rover is a research-stage outdoor patrol and inspection platform. Public examples include airports, utility sites, solar fields, wind farms, and correctional facilities. The likely buyer is a Director of Site Operations, Asset Integrity, Reliability, or Physical Security. EHS, IT/OT security, maintenance staff, and risk teams will also influence the project. The first use case should be a repeatable route, such as perimeter patrol or thermal inspection, rather than a general promise to work in every outdoor environment. ([InGen product ecosystem](https://www.ingendynamics.com/))

Boston Dynamics Spot is a useful comparison because it is already used for industrial inspection and remote data collection. Boston Dynamics now uses quotation pricing, but IEEE Spectrum reported a $74,500 Explorer Kit launch price in June 2020. This was a historical base package and did not include all inspection sensors, autonomy software, integration, or long-term service. For this reason, I estimate Rover at $75,000-$100,000 for the base-platform class. A complete deployment can go above $100,000 and enter Tier 4. ([Boston Dynamics Spot](https://bostondynamics.com/products/spot/); [IEEE Spectrum Spot price](https://spectrum.ieee.org/boston-dynamics-spot-robot-dog-now-available))

Rover is heavy and needs propulsion, sensors, communication, and outdoor navigation. Its energy use should be high when it is moving, but it will probably work by missions, so I classify it as duty-cycle, high. The useful measure is energy and cost per completed patrol, not only battery size. The major TCO items are depreciation, maintenance of tyres or drivetrain, batteries, sensor calibration, mapping, site integration, connectivity, and recovery after a failure.

The main competitor is Spot. The largest business risk is low reliability or low utilisation. Weather, mud, slopes, vehicles, people, signal loss, and emergency recovery can stop a mission. A high-price robot completing only a few low-value inspections cannot make a good business case even if its electricity cost is not high. OSHA also treats the robot as a full system including controls, power, sensors, and interfaces, so safety assessment is required. ([OSHA robot systems guidance](https://www.osha.gov/otm/section-4-safety-hazards/chapter-4))

The pilot should measure the percentage of patrols completed without help and the full cost of one successful inspection.

## 5. Aido Humanoid

- **Public stage:** Research stage
- **Likely buyer:** VP Operations, Director of Automation, or Chief Innovation Officer
- **Main use case:** Supervised material handling, machine tending, inspection, or teleoperation
- **Estimated cost tier:** Tier 3, $25,000-$100,000 for the platform; it may become Tier 4 when fully deployed
- **Public cost analogue:** Unitree G1 and H2
- **Energy class:** Duty-cycle, high peak
- **Main TCO driver:** Actuators, maintenance, task engineering, integration, supervision, and downtime
- **Main competitor:** Unitree H2
- **Main business risk:** Safety and intervention cost may be higher than the labour saved

Aido Humanoid has a large long-term possibility, but today it also has the highest uncertainty. InGen lists it as research stage. The public description gives a height of about 5 feet 4 inches, weight around 70 kilograms, and a four-hour runtime. These are design-level public characteristics, not proof of field performance. The buyer may be a VP Operations, Director of Automation, or innovation leader, with engineering, EHS, IT/OT, maintenance, finance, and workers also involved. ([InGen product ecosystem](https://www.ingendynamics.com/))

The use case must be narrow. “General labour” is too large to test. A first pilot can focus on one structured task, such as moving material, machine tending, visual inspection, or teleoperation in a controlled area. The business case should record cycle time, payload, error rate, number of human interventions, and recovery time.

Unitree gives useful public price references. Its official store lists G1 at $13,500 and H2 at $29,900 before customs. H2 is around 70 kilograms, so it is a better comparison by full-size mass. The basic price is not the deployed price. Working dexterous hands such as DEX5-1 or DEX3-1 are separate products, and application engineering, safety systems, integration, training, and service add more cost. I therefore put the platform in Tier 3, but a complete working deployment may enter Tier 4. ([Unitree G1 store](https://shop.unitree.com/products/unitree-g1); [Unitree H2 store](https://shop.unitree.com/products/unitree-h2); [Unitree H2](https://www.unitree.com/mobile/H2/); [DEX5-1](https://www.unitree.com/mobile/Dex5-1); [DEX3-1](https://www.unitree.com/mobile/Dex3-1))

Humanoid locomotion, balance, arms, perception, and onboard computing create high peak demand. Because it works by tasks and needs charging, I classify it as duty-cycle, high peak. Electricity is still not likely to be the largest cost. Actuator maintenance, batteries, end effectors, task programming, human supervision, downtime, and safety validation are more important.

The main competitor is Unitree H2. The biggest risk is safety and reliability before labour economics. A research robot that needs frequent human rescue can add labour instead of reducing it. OSHA guidance also shows why risk assessment, guarding, emergency stop, and safe operating procedure are necessary. ([OSHA robotics](https://www.osha.gov/robotics))

The pilot should first answer why a humanoid shape is necessary for the task, and what autonomous completion rate is needed to make the cost reasonable.

## 6. PIC 2.0 energy and compute cost context

The names below are InGen-specific. I use public academic concepts only as the closest comparison, not as proof that InGen uses exactly the same implementation. Each model has two sentences for the public concept and one sentence for the energy or deployment cost.

**GRPO - Group Relative Policy Optimisation**  
GRPO is closest to Group Relative Policy Optimization in DeepSeekMath, where outputs in one sampled group are compared to produce a relative learning signal. For a robot, a similar idea can compare several action plans during training, while knowledge distillation can move learning from a large model into a smaller deployment model. Energy and cost effect: more samples and simulation increase offline GPU time, but a smaller distilled or quantised model can reduce memory, power use, and delay on the robot. ([DeepSeekMath](https://arxiv.org/abs/2402.03300); [knowledge distillation](https://arxiv.org/abs/1503.02531))

**STUM - Spatiotemporal Uncertainty Model**  
STUM is closest to uncertainty analysis that combines present sensor confidence with how old the information is. Its action, review, and escalation logic is similar to conformal prediction and approximate Bayesian methods, which give a confidence range instead of only one answer. Energy and cost effect: conformal calibration can be light, but ensemble or repeated Monte Carlo inference uses more edge computing, memory, energy, and time. ([Conformal prediction](https://arxiv.org/abs/2107.07511); [MC dropout](https://proceedings.mlr.press/v48/gal16.html))

**SEOM - Self-Supervised Ethical Oversight Mechanism**  
SEOM is closest to constrained or safe reinforcement learning, where the system tries to maximise task reward while respecting safety limits. It is also similar to shielding, where a safety layer blocks or corrects an action that breaks a formal rule. Energy and cost effect: safety training and testing add offline compute, and runtime checking adds some delay, but these costs may reduce accident, liability, and supervision cost. ([Constrained Policy Optimization](https://proceedings.mlr.press/v70/achiam17a.html); [safe RL via shielding](https://arxiv.org/abs/1708.08611))

**AMDC - Adaptive Multi-Domain Calibration**  
AMDC is closest to automatic multi-sensor calibration, where cameras, LiDAR, IMU, or other sensors must remain aligned when conditions change. The multi-domain part is similar to domain adaptation, which helps a model work when training data and real deployment data are related but not the same. Energy and cost effect: continuous calibration and fleet sharing need sensor processing and network traffic, but they can reduce manual calibration, false alerts, retraining, and site visits. ([Automatic Camera-LiDAR Calibration](https://arxiv.org/abs/2404.17298); [Domain-Adversarial Training](https://jmlr.org/papers/v17/15-239.html))

**HTD-IRL - Hierarchical Task Decomposition via Inverse RL**  
HTD-IRL is closest to hierarchical reinforcement learning, where a long job is divided into smaller reusable skills or options. The inverse RL part means learning the reward or goal from expert demonstrations instead of writing every rule by hand. Energy and cost effect: collecting demonstrations and training the model need time and compute, but a task hierarchy can reduce online search and make local replanning faster on the robot. ([Options framework](https://www-anw.cs.umass.edu/~barto/courses/cs687/Sutton-Precup-Singh-AIJ99.pdf); [Inverse Reinforcement Learning](https://ai.stanford.edu/~ang/papers/icml00-irl.pdf))

**CRL-MRS - Cooperative Reinforcement Learning with Meta-Reward Systems**  
CRL-MRS is closest to cooperative multi-agent reinforcement learning with centralised training and decentralised execution, such as QMIX. Its fleet-dispatch function is also similar to multi-robot task allocation, where tasks are assigned according to robot ability, location, time, and reassignment need. Energy and cost effect: training becomes more expensive when the fleet is larger, and communication also uses energy, but better coordination can reduce duplicate travel and idle time. ([QMIX](https://proceedings.mlr.press/v80/rashid18a.html); [multi-robot task allocation](https://cse-robotics.engr.tamu.edu/dshell/cs689/papers/gerkey04formal.pdf))

## Main conclusions

1. Purchase price is not enough for comparison. Software, integration, maintenance, people, and downtime are important for all five products.
2. Electricity is probably not the largest cost, but energy still affects mission duration, charging, and utilisation, especially for Rover and Humanoid.
3. Product maturity should control how strong the business claim can be. A design target is not the same as tested customer performance.
4. Every pilot needs a clear baseline and one output measure. Otherwise, it is difficult to know whether the robot creates value.
5. All estimated prices and energy classes should be replaced when vendor quotations, measured power logs, battery-cycle data, and real pilot results are available.
