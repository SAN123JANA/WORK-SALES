### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMzIyN2EzMmQtYjkxYi00YzNiLTlhOGQtZTk3ZWUwN2QxOTdmIiwidCI6IjQ4NGU2ZGY2LWNhOWMtNDRhZS1iNzA2LTJlMWQyZmEwYWRkZSJ9&embedImagePlaceholder=true

## Problem Statement

This dashboard helps to perform comprehensive sales analysis to provide actionable insights into various aspects of the business performance over time. This includes calculating and visualizing cumulative sales, year-over-year growth percentages, and total sales within user-defined date ranges. The goal is to empower stakeholders with dynamic, interactive visualizations that facilitate data-driven decision-making

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3: Apply visualizations based on the dashboard
           
### Requirements

1.Cumulative Sales Analysis:

Measure: Create a DAX measure to calculate cumulative sales over a year.
Date Selection: Use a variable to store the maximum date selected by the user through a date slicer and calculate sales up to that date.
Visualization: Provide a line chart to visualize cumulative sales over time.

2.Year-over-Year Growth Percentage:

Measure: Create a DAX measure to calculate the Year-over-Year growth percentage for total sales.
Date Slicer: Allow users to dynamically select the year using a date slicer.
Visualization: Use a line chart to show the YoY growth trend and a card visual to display the YoY growth percentage for the selected year.

3.Total Sales within User-Defined Date Ranges:

Measure: Create a DAX measure that computes total sales within a user-defined date range.
Date Range Slicer: Provide slicers to select the start and end dates.
Visualization: Display the total sales within the selected date range using a card visual and support trend analysis with appropriate charts.

### Summary

By implementing the above measures and visualizations, the business can gain valuable insights into sales trends, growth metrics, and performance over specific periods. The interactive Power BI report will enable stakeholders to dynamically analyze sales data, facilitating informed decision-making and strategic planning.




