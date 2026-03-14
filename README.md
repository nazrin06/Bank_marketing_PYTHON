Bank Term Deposit Subscription Analysis

Business Question:
-How can we optimize our direct marketing outreach to maximize term deposit conversions while minimizing operational costs and customer "contact fatigue"?

Executive Summary
This project analyzes customer demographic, economic, and campaign data to predict which clients are most likely to subscribe to a term deposit. By identifying high-probability segments—such as students, retirees, and university graduates—the bank can transition from "mass calling" to a data-driven, targeted strategy.

Key Decisions (with visuals attached)
-Feature Prioritization: Age and Euribor 3-month rates were identified as the primary drivers of subscription behavior, outweighing traditional demographic factors like job type in predictive power. [visuals/top_features.png](https://github.com/nazrin06/Bank_marketing_PYTHON/blob/e11a1f650f73f655ebed654743e9b68948108b57/visuals/top_features.png)
-Segment Targeting: Focused analysis on high-conversion groups (Students/Retired) despite their smaller total volume in the dataset compared to the University Degree segment. !(visuals/term_deposit_subs_by_jobs.png)
-Metric Focus: Prioritized call duration as a leading indicator of interest, using it to distinguish between successful and unsuccessful engagements. !(visuals/duration_by_subscription.png)


Risks & Constraints
- The dataset is heavily skewed toward "University Degree" holders (over 12,000 instances). This could lead to a model that performs well for this group but fails for others.

- "No" responses vastly outnumber "Yes" responses across all job categories, which typically requires advanced sampling techniques to ensure the model doesn't just predict "No" every time.

Open Questions
- At what point does the campaign (number of contacts) become counterproductive? There is likely a "diminishing returns" threshold for outreach.
- Are there regional or seasonal factors not captured in the current feature set that could explain the high conversion rates for retirees?
