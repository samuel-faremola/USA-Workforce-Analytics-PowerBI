# USA-Workforce-Analytics-PowerBI

By Samuel Faremola

## Project Overview
A Power BI portfolio project exploring workforce distribution, working hours and overtime across departments and US states.

## Dashboard Features
- Employee totals and average hours worked
- Employee distribution by department and state
- Overtime hours by department
- Employment type breakdown
- Total overtime and overtime per employee
- Department slicer for interactive analysis

## Key Results
With all departments selected:
- Total employees: 500
- Average hours worked: approximately 1.45K
- Total overtime hours: approximately 62K
- Overtime per employee: 124.10 hours
- California has the largest employee count: 148
- HR has the largest department headcount: 105

Hours refer to the period covered by the dataset, rather than a weekly figure. Dashboard values displayed in K are rounded.

## DAX Example
Overtime per Employee =
DIVIDE(
    [Total Overtime DAX],
    DISTINCTCOUNT('Data'[EmployeeID]),
    0
)

## Business Use
The dashboard supports comparisons of staffing and overtime across departments. Overtime per employee provides context when comparing teams of different sizes.

Further investigation should consider workload, staffing needs and the reporting period before recommending changes.

## Repository Files
- Power BI project (.pbix): open in Power BI Desktop to explore the report.
- Dashboard PDF: view the exported dashboard.
- Analysis report PDF: read the findings and recommendations.

## Skills Demonstrated
Power BI Desktop, DAX measures, interactive filtering, data visualisation and analytical reportin
