# Week 1 Recap

**Name:** Ruiyuan Yin  
**Week:** 1

This week I mainly built a first understanding of InGen's product landscape. I reviewed Fari, Senpai, Sentinel Prime AI, Aido Rover, and Aido Humanoid. For each product, I identified the likely buyer, main use case, estimated cost tier, energy-use class, main TCO driver, competitor, and business risk. I put the comparison into `W01_Platform_Summary_Table.xlsx` and wrote the supporting analysis in `W01_InGen_BA_Landscape.md`.

One important learning is that the electricity bill is usually not the biggest cost of a robot product. For Fari and Senpai, software, support, training, privacy, and actual usage may be more important than charging cost. For Sentinel, integration with the security workflow, monitoring, storage, and false alerts can create a large cost. Rover and Humanoid have higher physical energy demand, but maintenance, downtime, task engineering, and human intervention may still decide whether the business case works.

For me, Rover has the most interesting energy economics in this week. It may use high power during a patrol, but power per hour cannot explain its real value. A better measure is energy and total cost per completed patrol or inspection. If the robot often needs recovery, cannot work in bad weather, or completes only low-value missions, a low electricity cost does not make the project economical.

My fuel-consumption work in Yunnan gives me a simple method for estimating robot operating cost. At the mine, I calculated each machine's daily operating cost as daily fuel use multiplied by fuel price. A robot can use the same logic: daily electricity use in Wh multiplied by electricity price. Battery-cycle life can also be treated as part of equipment depreciation.

I also made a short primer for five business analysis frameworks: SWOT, TAM/SAM/SOM, TCO, stakeholder mapping, and the data analysis workflow. This helped me connect the product research with business questions. For PIC 2.0, I compared the six model names with the closest public academic concepts and considered their possible compute and deployment-cost effects. These comparisons are only public analogues and do not prove InGen uses the same technical implementation.

The main difficulty was limited public information. InGen does not publish complete prices, measured energy use, or field-performance data for these products. Some public maturity descriptions are also not fully consistent, especially for Sentinel. I therefore used competitor information only as a reference and marked uncertain numbers as estimates, not InGen quotations.

During Week 1, I also ran the environment-check notebook and completed the GitHub upload. Before submission, I checked the Week 1 filenames, links, and required items one more time.

In Week 2, I will build a competitor database covering more than 15 vendors and prepare an investor analysis. I will look at Chinese companies such as Unitree, Keenon Robotics, and Booster Robotics, together with relevant international competitors.