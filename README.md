Tableau Project
Sales Performance Analysis

Business Scenario:

Mike Goodman, the head of Product Management of a retail products company, is responsible for determining which products his company should continue to offer for sale and which products should be discontinued from the company’s product catalog. 

Project Objective:

To build a dashboard that will present monthly sales performance by product segment and product category to help client identifying the segments and categories that have met or exceeded their sales targets, as well as those that have not met their sales targets.

Expectation/Goals to achieve:

1.	Using the sample Superstore dataset, create a bullet chart with Category and Segment dimensions and Sales measures. 
2.	Blend the data with the Saved Sample - Sales Target data set to bring in the Sales Target measure. 
3.	Color code the chart to identify Categories and Segments that are above or below target. 
4.	Add the year of sales to the view to identify trends and outliers. 
5.	Add a filter so that the user can select one, more than one, or all years. 
6.	Create a dashboard with this view.
 
Calculated Field:
Sales Above Budget?
IF SUM([Sales])>SUM([Sales Target (Sales_Target)].[Sales Target (Sales Target)]) 
THEN 
'Above Target'
ELSE
'Below Target'
END
 
Tableau Public Link:

Worksheet:
https://public.tableau.com/profile/saranya7758#!/vizhome/SalesPerformanceVsTarget_16188861518540/SalesPerformanceWithTarget

Dashboard:
https://public.tableau.com/profile/saranya7758#!/vizhome/SalesPerformanceVsTarget_16188861518540/SalesPerformanceVsTargetDashboard

Conclusion:
Thus, using the dashboard, we can find which products the company should continue to offer for sale and the products to be discontinued from the company’s product catalog. 

