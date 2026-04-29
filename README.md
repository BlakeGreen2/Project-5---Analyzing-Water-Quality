# Project-5---Analyzing-Water-Quality

Clients: Garrison River Diversion Project & Red River Valley Water Supply Project (RRVWSP)

-------------
**Background**

This project was completed to evaluate water quality along the McClusky Canal system to support decision making for a proposed pipeline in North Dakota from Lake Sakakawea to Lake Ashtabula through the Sheyenne River.
Over the course of the project key parameters will be evaluated at multiple locations and a mass balance equation will be made with a function that can be used to evaluate multiple mixing scenarios.

-----
**Parameter Evaluation**

All parameters will have summary statistics showing the mean, median, max, min, and number of observations at each location along the canal system. Then 6 key parameters were observed from these statistics and put into boxplots using matplotlib and seaborn to create the visualizations. A bar chart was also created to help better evaluate the Total Dissolved Solids along the canal and visually see the increases from the source to other points along the canal. 

----
**Mass Balance Equation**

A function to evaluate the concentration of Total Dissolved Solids after mixing from the pipeline. The current code has the Q(pipe) set to 6 cfs which was a client given design number. The Q(River) is set to 50 cfs which was found from the dataset. These inputs can be changed individually to evaluate different mixing scenarios to see how they would effect the final concentration of Total Dissolved Solids. The equation assumes steady state conditions and complete mixing.

----
**Temporal Trend Analysis**

A temporal trend analysis was also completed using a statsmodels function. This showed the water quality for total dissolved solids and sulfate over the years in Lake Ashtabula and Lake Sakakawea. The linear regression was used to see if there was a linear trend between time and water quality degradation. All graphs were then plotted on subplots and showed a positive correlation. If a statistical analysis were to be done these results would possibly not have an alpha value less than 0.05 due to insufficient data points for some of the graphs however they do provide insight into the data when combined with previous analysis of the parameters.

----
**Contents**

- Raw Data Files
- Python Code
- Scope of Work
- Gantt Chart
- Engineering Timesheet
- Annotated Code Document
- Written Report
