# Power-BI-Projects
These are Power BI semantic models, dashboards, and reports created by Apurva Dave. These are for viewing and sharing only and should not be otherwise used, copied, or sold without written and signed permission from Apurva Dave.

For the mock data model files dated 9 Apr 2026, the semantic model was built using the following:
custom date table that allows fiscal year, quarter, month, and week granularity
summarized fields and complex DAX measures that enable dynamic switching based on user selections

Data visualizations (e.g. line charts, columns charts, control charts, cards with KPIs) are grouped into the following 3 types of reports: 
a dashboard - An overview that shows values and charts for all devices and all countries combined. The aim is to provide a summary view of the business. The current status and trends of some main KPIs and KRIs are shown, including total sales profits, gross profits, units sold, and number of complaints year to date and compared to the previous year.
analytical reports - These contain charts that allow users to see more details and sub-segments of the data. One report provides the same KPIs and KPIs from the dashboard, but allows for filtering by type of device and country. A second analytical report shows sales and gross profit over time and allows the same type of filtering by the user.
an operational report - with configurable control chart for risk-based analysis - The operational report is aimed at helping the user to know whether to take immediate action. The control chart provides upper and lower control limits and visually shows whether the average number of complaints has exceeded those. If such outliers are seen, then action should be taken to find out why, and that would lead to further action depending on the findings.


