**kickstarter-challenge analysis
# Overview
Extracting data related to outcomes and launch dates in theater category from kickstarter, and performing analysis to show the connection between outcomes and launch dates. Also, performing analysis over data related to goals and outcomes within "plays" subcategory to establish the successful and failed rates in each set of goals. 
# Analysis and Challenges
## Theater Outcomes by Launch Date
* Created a new column of "Years" with =YEAR formula to extract the years from "Date created conversion" in kickstarter
* Created a new sheet and named "theater outcomes by launch date", and inserted a pivot table with launch date as row, outcomes as column, filtered with parent category and years.
* Grouped the row lable column to show the months of the year, filtered the column label to show only "successful", "failed" and "canceled", sorted the parent category column to show only "theater", and sorted the column label in descending order to show "successful" the first. 
* Inserted a line chart with number of projects as X axis and months of the year as Y to show the number of successful,failed, and canceled project by months. 
## Outcomes based on Goals 
* Created a new sheet named "Outcomes Based on Goals" 
* Breaked down the goal column as instructed, used =COUNTIFS formula to extract the numbers of successful, failed and canceled projects in "plays" subcategory for each set of goal 
* Used =SUM formula to calculate the total number of successful, failed and canceled projects for each set of goal 
* Divided the total projects with successful, failed and canceled project to get the percentage of successful, failed and cancaled rates for each set of goal 
* Created a line chart to show the successful, failed and canceled rate in each and every breakdown of goal amount 
## Challenges encountered while performing the analysis 
* Unable to get the correct numbers of projects because I overlooked the "plays" subcategory requirement 
* Was able to retrieve the correct data and right graphic of the line chart after applied one more criteria in =COUNTIFS formula 
# Results 
## Conclusions of Theater Outcomes by Launch Date 
* The theater campaign was a lot more successful during early summer time, namely ***May and June***
* The successful and failed number almost meet at the same point in ***December***, which indicates that it is not much effective to conduct theater campaigns during ***winter*** 
## Conclusion of Outcomes Based on Goals 
* Goal amount $20,000 is a threshold, the lower the goal amount set, the higher likely the project will succeed. 
* The line chart shows that the successful and failed rates formed in a exact opposite pattern, the successful rate started recovering when it reached the point of $25,000, so the opposite of failed rate. 
* In order to get more productive, the goal amount should focus more on less than $25,000, and between $35,000 to $44,999. 
## Limitations of this dataset 
The data points are very few in the dataset, missing value and other variance, which is relatively biased to generate a generalized enough set for future predictions. 
## Other possible tables and/or graphs 
We could also create bar chart and/or pie chart, however, each data visualization has its own limitations to present the data, so the line chart could be relatively accurate to pinpoint the data that reflected in terms of each month. 
