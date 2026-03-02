📊 Marketing Funnel & Conversion Performance Analysis | Power BI

Data Science & Analytics Internship – Future Interns

🚀 Project Overview

This project was developed as part of my Data Science & Analytics Internship at Future Interns.

The objective of this analysis is to evaluate marketing campaign effectiveness using a structured funnel approach. The dashboard tracks how customers move from initial contact to final subscription and identifies key drop-off stages impacting conversion performance.

By transforming raw campaign data into interactive business insights, this project demonstrates how data-driven decision-making can improve marketing ROI and customer acquisition strategies.

🎯 Business Problem

Banks invest heavily in marketing campaigns, but not all contacted customers convert.

This dashboard answers critical business questions:

How many customers were contacted?

What percentage subscribed to the term deposit?

Where does the largest funnel drop-off occur?

Does follow-up frequency improve conversion?

Which customer segments convert the most?

Which months show higher marketing effectiveness?

Does contact type (cellular vs telephone) impact results?

🛠️ Tools & Technologies

Power BI Desktop – Dashboard development & visualization

DAX (Data Analysis Expressions) – KPI calculations & funnel metrics

Microsoft Excel – Data cleaning & preprocessing

Data Modeling – Measures & structured funnel logic

Dataset Source: Bank Marketing Dataset from UCI Repository

📐 Key DAX Measures
Total Contacts =
SUM(Sheet1[Contact_Flag])

Total Conversions =
SUM(Sheet1[Converted_Flag])

Conversion % =
DIVIDE([Total Conversions], [Total Contacts], 0)

Multi Contact Count =
CALCULATE(
    COUNT(Sheet1[campaign]),
    Sheet1[campaign] > 1
)

These measures form the foundation of the marketing funnel and conversion analysis.


🔍 Key Insights & Findings

The overall conversion rate is approximately 11.5%, meaning nearly 88% of contacted customers do not convert.

Customers contacted more than once show significantly higher subscription probability.

Previous successful campaign responses strongly increase conversion likelihood.

Cellular contact method performs better than telephone in terms of conversion efficiency.

Certain months show higher conversion activity, indicating seasonal campaign effectiveness.

📌 Business Recommendations

Based on the analysis:

Improve lead qualification before outreach to reduce initial drop-off.

Increase structured follow-ups for high-potential customers.

Prioritize cellular-based outreach campaigns.

Re-target customers with prior successful interactions.

Allocate budget toward high-performing seasonal periods.

Even a 2–3% improvement in conversion rate could significantly increase total subscriptions without increasing marketing spend.

📈 Impact of This Project

This project demonstrates:

Funnel & growth analytics

KPI-driven marketing evaluation

Business insight generation from raw data

Practical Power BI dashboard design

Real-world campaign performance analysis

It reflects how analytics can directly influence revenue optimization and marketing strategy decisions.

🧠 Skills Demonstrated

Marketing Funnel Analysis

Conversion Optimization Metrics

DAX Calculations

Business Insight Communication

Data Visualization & Storytelling

Decision-Focused Reporting
