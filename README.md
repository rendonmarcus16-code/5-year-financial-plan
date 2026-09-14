Five-Year Financial Forecast & Variance Dashboard

I built a Power BI dashboard tracking departmental spending, budget-vs-actual variance, and a five-year forecast, using two linked datasets — revenue by source and expenditure by department — to structure the analysis. The project was modeled directly on a real Budget & Management Analyst job posting, demonstrating the kind of variance tracking, forecasting, and cross-functional budget review that role requires.

Approach

I started with two datasets — revenue by source and expenditure by department — and first confirmed the data types and structure were clean before building anything on top of them. I then built a shared date table and connected both datasets to it, which let me analyze revenue and expenditure together on a single timeline. From there, I used DAX measures to calculate budget-vs-actual variance (in both dollar and percentage terms), a trend-based forecast for the following fiscal year, and department-level spending breakdowns.

Key Findings

The budget grows at a consistent rate of approximately 3.25% year over year, which I used to project next year's budget at roughly $31.6M. Police and Fire are the two departments most consistently over budget, together accounting for the majority of citywide overspending. On the revenue side, Property Tax is the City's largest source of revenue overall, with Sales Tax as the second-largest — though Sales Tax stands out as the strongest performer relative to its own budget, consistently exceeding projections.

Files
revenue_by_source.csv / expenditure_by_department.csv — dataset
five_year_forecast_brief.md — project brief / assumptions
5_Year_Financial_Plan.pbix — full Power BI report
PDF export — for browsing without Power BI installed
Tools

Power BI, DAX
