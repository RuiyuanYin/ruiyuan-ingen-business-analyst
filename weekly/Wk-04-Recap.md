Week 4 Recap — Cost-Benefit Analysis and KPI Framework
Name: Ruiyuan Yin

This week I turned the Sentinel Prime AI TCO work from Week 3 into a five-year cost-benefit model. The main change was separating the $98,125 initial deployment cost from the yearly operating costs. I put the investment in Year 0 and used the annual operating savings in Years 1–5. This keeps the same total savings as the Week 3 model and avoids counting the initial cost twice.

For the discount rate, I used the July 31, 2026 U.S. 10-year Treasury yield of 4.75% and added the required 3% risk premium. The final discount rate is 7.75%. In the base case, Sentinel has an NPV of about $561,511, an IRR of 158.7%, and an estimated payback of 7.6 months. The result is strong because the model compares Sentinel with one 24/7 human-security post while still keeping 25% human oversight and 2% downtime backup. Since one modeled deployment already has positive NPV, the customer-side model does not show a minimum contract size.

I also tested the two required sensitivity cases. If hardware cost rises by 20%, NPV falls to about $540,091 and payback moves to 9.2 months. If useful life falls from five years to three years, NPV falls more sharply to about $317,647. The three-year useful life has the largest effect because the model loses two years of savings, although NPV is still positive.

The second workbook is a 15-KPI framework for Fari, Senpai, and Sentinel Prime AI. Each platform has one KPI for deployment, operations, energy, customer economics, and business health. I tied the targets to the Week 3 SOM and TCO numbers when possible. For Sentinel, the deployment target is shown as 184–920, with 276 as the base case. For Fari and Senpai metrics that need real operating data, the baseline will be calculated from the first 30 days of pilot logs and then kept fixed for later comparison.

The part I had to think about most was making sure each KPI could actually be updated. It was easy to list broad ideas, but harder to define a clear formula and a usable data source for each one. Keeping the framework to five measures per platform made it simpler and easier to follow.