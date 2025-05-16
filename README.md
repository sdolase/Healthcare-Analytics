# Healthcare-Analytics
Welcome to our repository for the Healthcare Analytics Project. This project focuses on analyzing key performance indicators (KPIs) across various healthcare and dialysis-related metrics. The insights derived from this analysis are intended to support better decision-making in the healthcare sector.

Table of Contents
Overview

Key Performance Indicators (KPIs)

KPI 1: Number of Patients across Summaries

KPI 2: Profit vs. Non-Profit Stats

KPI 3: Chain Organizations & Total Performance Score

KPI 4: Dialysis Stations Statistics

KPI 5: Total Category Text - As Expected

KPI 6: Average Payment Reduction Rate

Dashboards & Data Tools

Challenges & Solutions

Conclusion



Overview
This project undertakes a comprehensive analysis of healthcare data with a special focus on dialysis centers. By examining various KPIs, we aim to understand patient trends, operational efficiencies, and market dynamics—ultimately providing actionable insights for improved healthcare delivery.

Key Performance Indicators (KPIs)
KPI 1: Number of Patients across Summaries
Observations:

Dominance of Survival Summary: With nearly 1.938 million patients, survival outcomes are a primary focus.

Key Metabolic Parameters: "Serum Phosphorus" and "Hypercalcemia summaries" each record over 600,000 patients, highlighting critical metabolic monitoring.

Vascular Access Consideration: Both "Catheter" and "Fistula summaries" have around 600,000 patients, essential for treatment planning.

Lower Frequency Metrics: "Hospitalization" and "Transfusion summaries" report approximately 495K and 422K patients, respectively.

Niche Metrics: The "nPCR summary" shows only 1,000 patients, suggesting limited applicability.

KPI 2: Profit vs. Non-Profit Stats
Observations:

Profit Dominance: A significant 89% of the organizations are profit-oriented, underlining a strong focus on revenue generation.

Non-Profit Representation: Only 11% of organizations are non-profit, reflecting a smaller portion of healthcare centers focusing solely on patient welfare.

KPI 3: Chain Organizations & Total Performance Score
Observations:

Market Leaders: DaVita and Fresenius Medical Care lead with performance scores of 119 and 118, respectively, indicating their dominant position within the industry.

Score Distribution: A vast majority of smaller organizations score minimally, suggesting a concentration of expertise and quality with top providers.

Dialysis Coverage: Approximately 99% of dialysis stations offer In-center Hemodialysis, stressing the need for diversification towards peritoneal dialysis.

KPI 4: Dialysis Stations Statistics
Observations:

Ownership Mix: Around 91% of dialysis stations are owned by chains, while only 9% are independent centers.

Home Hemodialysis Training: Only 29% of stations offer training for home-based hemodialysis, presenting an opportunity for service expansion.

Service Disparity: There is a noted imbalance between stations offering peritoneal dialysis versus those that do not.

KPI 5: Total Category Text - As Expected
Observations:

High Facility Counts: Categories like Hospitalization (6,818), Fistula (6,517), PPPW (6,659), and Survival (5,966) indicate their prominence in healthcare management.

Lower Count: The SWR category shows the lowest facility count at 3,623, hinting at areas that might benefit from increased attention.

Below is an illustration of facility counts across categories:

Category	Facility Count
SWR	3,623
Infection	5,011
Survival	5,966
Transfusion	6,108
Fistula	6,517
PPPW	6,659
Hospitalization	6,818
KPI 6: Average Payment Reduction Rate
Observations:

This metric tracks the rate at which payments are reduced, providing insights into cost-saving measures and identifying factors that might contribute to financial efficiencies in healthcare facilities.

Dashboards & Data Tools
The analysis was supported and visualized through multiple tools, including:

Excel Dashboard

Tableau Dashboard

Power BI Dashboard

MySQL for data exploration and management

Each tool provided a unique interface for data interaction and further analysis.

Challenges & Solutions
Data Cleaning:

Initial Approach: Null values were first replaced using average values, as the columns were numerical.

Final Strategy: To maintain consistency with KPI specifications (especially for count-based metrics), nulls were replaced with zeros, ensuring data integrity.

Conclusion
The analysis revealed several critical insights:

Market Dynamics: Chain-owned dialysis centers dominate the sector, indicating standardized practices and efficiencies.

Treatment Preferences: In-center hemodialysis is overwhelmingly common, though there is scope for increasing peritoneal dialysis options.

Training Opportunities: Limited availability of home hemodialysis training signals an area for potential growth.

Operational Focus: High facility counts in categories like hospitalization and PPPW confirm their importance, while categories with lower counts (e.g., SWR) suggest areas needing improvement.
