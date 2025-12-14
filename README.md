# ROI-Risk-Analysis-Portfolio
Supply Chain Automation ROI Risk Analysis
📖 Application Scenario
This project is designed for Supply Chain Warehousing & Logistics.

When investing in large-scale automation (e.g., Sorters, AGVs), ROI models are often based on ideal efficiency assumptions. This tool performs a risk prediction and sensitivity analysis to quantify how different uncertainties—such as operational inefficiencies, wage inflation, or budget overruns—impact the annual OpEex and the project's overall financial viability.

📊 Risk Scenarios
The model uses the peak year (2029) as a baseline to compare the impact of three specific risk scenarios:

1. Baseline (No Risk)

Assumption: The automation runs at 100% expected efficiency (Base UPH ~422), and labor costs remain stable.

Purpose: Serves as the standard for comparison.

2. Scenario 1: Operational Risk (Single Factor)

Assumption: Due to missorts, labeling issues, or system downtime, the actual Units Per Hour (UPH) drops to 60% of the target.

Impact: Lower efficiency forces the operation to hire significantly more headcount to maintain throughput, drastically increasing OpEx.

3. Scenario 2: Double Risk (Efficiency + Inflation)

Assumption: The equipment runs at 80% efficiency, AND simultaneously, hourly wages increase by 10% (Wage Inflation).

Impact: Tests the compound effect of moderate inefficiency combined with rising labor costs.

4. Scenario 3: Capex Overrun

Assumption: The initial investment cost (Capex) for the equipment exceeds the budget by 20%.

Impact: Analyzes the sensitivity of the model to one-time startup cost variations.

💡 Key Findings & Conclusion
Based on the model's calculation and visualization, here are the final conclusions:

Highest Risk Factor: Operational Efficiency

Scenario 1 (60% UPH) has the most severe impact on OpEx.

When efficiency drops, the required headcount surges from 375 to 625. This results in an annual cost increase of approximately €34.4M (+66.7%).

Conclusion: Operational stability is the most critical success factor. Failing to meet UPH targets destroys ROI faster than any other factor.

Low Sensitivity to Capex

Scenario 3 (Capex +20%) only results in a one-time loss of €146k.

Conclusion: In labor-intensive logistics hubs, initial hardware price fluctuations are negligible compared to the long-term risk of high OpEx.
