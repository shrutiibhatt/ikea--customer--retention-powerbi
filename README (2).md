# IKEA Customer Retention Analytics (Power BI)

A Power BI report analysing customer churn, loyalty and customer lifetime
value (CLV) for 300 IKEA customers, built from five linked tables.
Completed as part of the Internshala Digital Marketing course.

## Business question
Which customers are loyal and which are at risk of churning, and how do
loyalty tiers, promotions, store types and regions affect retention?

## Key findings
- Overall churn was 51.67% (155 of 300 customers); 145 were repeat customers
- Liverpool (55.6%) and Birmingham (55.4%) had the highest churn; London was lowest (47.5%)
- Platinum customers churned most (55.95%), compared with Silver (51.49%) and Gold (48.70%)
- Promotions applied to 51% of transactions, but average transaction value was almost identical with and without one (250 vs 249)
- Superstores averaged 257 per transaction vs 245 for Express stores
- High-CLV customers bought about 5.2 times on average, versus 1.9 for low-CLV customers

## Recommendations
1. Review Platinum benefits, since the top tier has the highest churn
2. Run retention campaigns in Liverpool and Birmingham, and learn from London
3. Test targeted promotions before scaling them
4. Prioritise high-CLV customers with personalised engagement

## What I built
- Data cleaning and modelling in Power Query (5 tables, linked by relationships)
- DAX measures for churn rate, repeat rate, CLV and CLV segments
- 10 report pages: one per course task, plus a 4-page final dashboard (Overview, Loyalty & Promotion, Store & Region, Customer Segmentation)
- Slicers for Region, Income Group, Loyalty Tier and Store Type

## Files
- `IKEA_Customer_Retention.pbix`: the Power BI report (open in Power BI Desktop)

## Tools
Power BI, Power Query, DAX, Data Modelling, Customer Analytics

## Notes
- This is the report as submitted for the course. Where the commentary inside the report differs from the findings above, the findings above (checked against the report's charts) take precedence.
- The dataset is a 300-customer course dataset, so store-level results are directional rather than conclusive.
