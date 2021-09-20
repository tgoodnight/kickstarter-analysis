# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Kickstarter Analysis Project

### Overview of Project

The purpose of the Kickstarter Excel project was to learn about how to analyze data in an Excel workbook.  From beginning to end, this project taught me how to receive a data file, break do the data into useable parts, extract information using formulas and pivot tables, and then how visualize the data using appropriate charts for the data.  

### Analysis and Challenges

I performed my analysis on the Kickstarter challenge by using filters, formulas such as COUNTIFS, and Pivot Tables.  Overall, the analysis was pretty straightforward, but I can see how someone could run into trouble in a few areas:
1.	 At some points we had to analyze the data by month, but the data we had was only in Short Date format.  In order to get the data into “by month” format inside of a Pivot Table was a little tricky because you must drag the Date into the column list and then it splits into Year, Month, and Day.  You then remove Year and Day and are left with the ability to view the data split into Jan, Feb, Mar…ect.
2.	Another point in the project that I could be confusing for somebody would be if there were any data inconsistencies in the Kickstarter data tab.  For example, if there were typos in the Outcomes column then it could mess up your COUNTIFS statements because the reference for “successful” must be spelled exactly as is or it will not count the data that you want.  

In conclusion, the results on the Kickstarter analysis were loud and clear.
1.	 ![Theatre_Outcomes_vs_Launch_Date](https://user-images.githubusercontent.com/90290952/133950893-540a50ce-7417-466d-a14e-b1737f871e9a.png)
Two conclusions that we can draw from this chart are:
  - The most successful outcomes per month for the theatre category were in May and June. 
  - Throughout the year, the outcomes for February through June had the lowest “failed” rates.  Overall the average “failed” rate was around 39%.
2.	![Outcomes Based On Goal](https://user-images.githubusercontent.com/90290952/133950936-296f9918-14f2-4ea1-911a-ebb75c42445b.png)
A few conclusions can be made about the Outcomes Based on Goals in the Kickstarter data.  
  - This chart is a bit misleading because it does not bring you to the correct conclusion.  When one analyzes this chart they will probably correctly conclude that the highest percentage of successful outcomes based on goal amount were those that were under $5,000.  This is certainly correct but it ignores the fact that the rest of the chart can also possibly make you conclude that there is also a midpoint in the data where if the Goal is between $35,000 and $45,000 then it may also be pretty successful based on the outcome.  That would be a completely incorrect conclusion but at no fault to the person viewing the chart.  The reason that this is incorrect is that 16% of the data points lie between a Goal of $5,000 and $10,000, while an additional 15% of the data lies in areas greater than a $10,000 Goal.  In conclusion, 69% of the data lies below or equal to a $5,000 Goal, and the chart has a highly positive skew.  ![Outcome Based on Goal (Positive Skew)](https://user-images.githubusercontent.com/90290952/133950981-e1a4bafb-5f17-4d6b-8e10-a8af5f718af8.png)

This was a great challenge because it taught me how to analyze a dataset in multiple ways and to use many methods to figure out which way was the correct way to visualize the data based on measures of central tendency.
