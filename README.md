# FUTURE_DS_03 — Marketing Funnel & Conversion Performance Analysis

**Internship:** Future Interns — Data Science & Analytics
**Task:** Task 3 of 3

## What this task is about
Analyze marketing funnel data to identify conversion drop-offs, channel performance, and opportunities to improve lead-to-customer conversion.

## Files in this folder
- `data/raw_funnel_data.csv` — weekly funnel data (Visitors → Leads → MQLs → SQLs → Customers) by channel, with ad spend, for 2025
- `task3_funnel_analysis.ipynb` — full analysis notebook (cleaning, EDA, charts, insights)
- `task3_funnel_analysis.html` — HTML export of the notebook
- `task3_funnel_dashboard.xlsx` — Excel dashboard with funnel, channel, and weekly-trend breakdowns
- `*.png` — chart images exported from the notebook

## Tools used
Python (pandas, matplotlib) for the analysis and Excel (openpyxl) for the dashboard.

## Approach
1. Cleaned up an inconsistent channel name variant ("Facebook / Instagram Ads" vs "Facebook/Instagram Ads") that would otherwise split one channel's numbers into two rows.
2. Looked at the overall funnel and conversion rate at each stage to find the biggest drop-off point.
3. Compared channels on conversion rate and cost-per-acquisition to see which are actually efficient, not just high-volume.
4. Looked at the weekly trend to see how traffic and conversion rate move together (or don't) around the festive season spike.

## Key takeaways
- Visitor → Lead is the single biggest drop-off point in the funnel.
- Referral and Email convert far better end-to-end than the paid channels.
- Facebook/Instagram Ads is the least efficient paid channel — highest CAC, below-average conversion.
- The November traffic spike doesn't bring a proportional lift in conversion quality.

Full write-up with charts is in the notebook.
