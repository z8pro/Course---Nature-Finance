**Course---Nature-Finance**
# Project 1 — Lake of Brienz: Ecosystem Value Assessment

This project estimates the economic value of ecosystem services provided by Lake Brienz using three complementary valuation lenses: stated preference (benefit transfer of household willingness-to-pay for “lakeside quality”), revealed preference (aggregation of recreation consumer surplus, boat-tour producer surplus, hydropower resource-rent proxy, and fishery landed value), and a cost-based perspective using water-quality safeguarding / replacement logic. It also discusses key sensitivities (e.g., income elasticity in benefit transfer) and interprets results in terms of what is captured vs. omitted by each approach.  ￼

Main outputs
	•	Per-household monthly WTP range (benefit transfer) + a personal-use benchmark estimate.  ￼
	•	Annual revealed-preference valuation assembled from non-overlapping service components (central-case order of magnitude ≈ tens of CHF millions/year). 

# Project 2 — Temperature-Trigger Parametric Insurance: Detrending, Pricing, Tail Risk

This project analyzes a high-temperature parametric insurance contract (annual payout capped at $10M) using historical daytime hourly temperature data and scenario-based extensions. It compares detrending strategies (global trend, STL-based trend, and season-aware month-specific adjustments), motivates a baseline choice (raw series as the pricing view), computes capped annual payout statistics for multiple triggers (35°C / 40°C / 45°C), and then estimates a rare-event “1-in-200” payout under a warming scenario by simulating synthetic hourly years with a seasonality + heteroskedasticity + persistence + heavy-tail model (gap-aware AR(1) with Student-t innovations).  ￼

Main outputs
	•	Historical capped payout summary by trigger, showing how contract risk explodes at lower thresholds (cap-binding) and vanishes at high thresholds in-sample.  ￼
	•	Monte Carlo tail risk for a conservative trigger (45°C): 99.5th percentile payout (“1:200”) under mid-century vs long-run warming, illustrating when the cap becomes tail-binding.  ￼
	•	A transparent modeling pipeline for synthetic extension: month-hour climatology, month-hour volatility, persistence, and heavy tails to avoid understating extremes.
