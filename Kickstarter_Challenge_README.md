# Kickstarting with Excel

## Project Overview:

### The purpose of this analysis was to provide our customer Louise additional data on how different campaigns - similar to her play "Fever" - fared while raising funds for each project in relation to their launch date and overall fundraising goals. This will help Louise when she is ready to move forward with raising funds for her next project.
### Analysis was performed by first collecting data for two separate outcomes. The first analysis was based on launch date and was used to determine if time of the year had any influence on the success or failure of a fundraising campaign. The second analysis was based on fundraising goals which identified percentage of success or failure of a campaign based on the fundraising goal amount.
---
## Outcomes Based on Launch Date
### This analysis was performed by creating a pivot table to show the number of outcomes - either successful, failed or canceled - based on when the campaign was created. The outcomes based on launch date were conveyed through a line chart showing yearly results of each outcome from January through December.
![Theater_Outcomes_vs_Launch.png](https://github.com/jmueller187/Kickstarter_Challenge1/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
---
## Outcomes Based on Goals
### This analysis was performed by creating a new table to show the number of each funding campaign for the Plays subcategory within a specific funding goal range (i.e. less than $1000, $1000 to $4999, $5000 to $5999, etc., up to greater than or equal to $50000). The 'COUNTIFS' function was used to determine the breakouts between successful, failed and cancened campaigns within each category, which then allowed us to calculate the percentage of successful, failend and canceled campaigns once we calculated the sum of total campaigns in each goal category. The outcomes based on goal were conveyed through a line chart showing the percentage of each outcome over the 12 funding goal ranges.
![Outcomes_vs_Goals.png](https://github.com/jmueller187/Kickstarter_Challenge1/blob/main/Resources/Outcomes_vs_Goals.png)
---
## Challenges and Difficulties Encountered
### There were two challenges during the analysis, both of which occurred while formatting the 'COUNTIFS' functions for the Outcomes Based on Goals table and displaying those results on a line chart. As this was the first time I had attempted to use this function and add a line graph to a worksheet, I was unclear on how to proceed to get the desired results. Thanks to some assistance from the TA's and my classmates during the Saturday office hours Zoom session, I was able to resolve both of these challenges and deliver the final results required for the Challenge. 
---
### For the first challenge, I was trying to compare the sum of total projects from my Ooutcomes Based on Goals worksheet with the total number of plays listed under the Subcategory column on the main Kickstarter worksheet. I ended up finding a difference of 19 projects between the two values. With some help from a classmate, we discovered there was a fourth project category - 'live' - that was not being considered in our analysis. This category contained the 19 projcts that made of the difference in my verification sums.
---
### For the second challenge, I encountered issues trying to create the line graph to show the relationship between goal amount ranges and percentage of successful, failed and cancelled projects. I was trying to insert the graph without selecting the specific columns from the worksheet that were needed on the graph. Once I selected the necessary columns, I was able to graph the outcomes correctly.
---
## Results

## Conclusions drawn about the Outcomes based on Launch Date
### 1) The largest majority of the Theater fundraising goals ended up being successful, with almost twice as many projects succeeding than failing.
### 2) People were more inclined to contribute to fundraising campaigns during the 2nd quarter of the year - from May to July. These three months yielded the highest number of successful campaigns month to month for the entire year.
---
## Conclusion drawn about the Outcomes based on Goals
### Fundraising campaigns with a goal less than $15000 were the most likely to succeed. These project's percentage of success ranged from a minimum of approximately 55% to a maximum of approximately 76% based on the goal range. As the amount of fundraising goals in this range decreased, the percentage of the campaigns being successful increased.
---
## Limitations of this dataset
### 1) The dataset includes campaigns from 21 countries. Additional countries could have been included for a broader range of results.
### 2) This dataset includes campaigns from 2009 to 2017. This range could have been expanded up through 2020 or prior to 2009 to increase the amount of projects to analyze.
---
## What are some additional tables and/or graphs that could be created?
### 1) Successful and Failed Kickstarter campaigns per country included in the dataset.
### 2) Charts of Mean Goal/Plegded, Meadial Goal/Pledged, Standard Deviation of Goal/Pledged, Upper Quartile of Goal/Pledged, Lower Quartile of Goal/Pledged and IQR of Goal/Pledged for successful and Failed campaigns.
### 3) Use additional Subcategories to determine Successful / Failed Kickstarters, Outcomes Based on Launch Date, Outcomes Based on Goals, etc.
### 4) Summarize Average Donation ranges per various Subcategories to determine what types of projects backers are interested in funding. 
