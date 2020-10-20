Table of Contents
Project Overview
Resources
Objectives
Summary
Limitations

Project Overview
This module is a deep dive into Excel, a tool that can be used across all areas of life, from household budgeting to complex financial analysis. Learning the intricacies of Excel will draw on (and enhance) skills we may have already, like computer literacy, data literacy, and quantitative reasoning.

Resources
Software: Excel
Objectives
Use filters and Excel formula to create new datasets
Create visualizations using Excel charts and pivot tables
Interpret the summary data provided from the visualizations
Summary
In this challenge, we continued to exercise our Excel prowess! This time, we created two new analyses: outcomes based on goals and outcomes based on launch date.

Background
Louise’s play Fever came close came close to its fundraising goal in a short amount of time. How many other Kickstarter campaigns were able to do this as well? In this challenge, we conducted a data analysis to answer this question and determine whether the length of a campaign contributes to its ultimate success or failure.

Objectives
The goals of this challenge were to:

Use filters and Excel formula to create new datasets
Create visualizations using Excel charts and pivot tables
Interpret the summary data provided from the visualizations
Instructions
Open Excel and create two sheets. Name them "Outcomes Based on Launch Date" and "Outcomes Based on Goals."
In the "Outcomes Based on Goals" sheet, do the following:

Create 8 new columns with the following headings:
Goal
Number Successful
Number Failed
Number Canceled
Total Projects
Percentage Successful
Percentage Failed
Percentage Canceled
In the Goal column, create 12 new rows to sort each project. This will hold each goal range we're charting:

Use COUNTIFS()to count the number of successful, failed, and canceled projects within the newly defined ranges. (Filter the Kickstarter sheet to show only the Plays subcategory, otherwise, our scope includes all campaigns instead of the ones we are interested in.) Populate the appropriate columns.

Add each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column.

Use division to find the percentage of projects that fall into each category (percentage successful, percentage failed, and percentage canceled).

Create a line chart to visualize the relationship between the goal amount and the campaign’s chances of success, failure, or cancellation.

Save the line chart as a .png image.
Goal Chart





In the "Outcomes Based on Launch Date" sheet, do the following:
Create a pivot table that charts the outcome of each Kickstarter project based on the launch date.

Set the “Parent Category” filter to “theater” and save the chart as a .png image.

Launch Date Chart


# An Analysis of Kickstarter Campaigns
Performing Analysis on Kickstarter data to uncover Trends (Bootcamp)

#Introduction
We are analyzing kickstarter data to help optimize a upcoming campaign for the Play "Fever". Utilizing data from successful, canceled, and failed campaigns around the world we explore factors in successful campaigns, as well as focus on campaigns that have a similar goal as well as category.

##Summary
Based on our analysis, we can conclude that opening the campaign in May would give the best chance of success. Theatre campaigns do their best starting in may, and begin to lower their success rate from June through the end of the year; of he 166 theatre campaigns launched in May, 111 of them were successful.

![Theatre Outcomes based on Launch Month in the US](Outcomes%20Based%20on%20Launch%20Date-Theatre.png)

Fever has a high chance of success; There were 525 Successful Theatre campaigns, and 412 of those were Plays.
![US Theatre Campaigns](Parent%20Category%20Outcomes-US%20Theatre.png)


Fever’s goal of $10,000 - $12,000 can lower the chances of success. Most of the successful play campaigns were for amounts closer to $5000. A Goal of $10,000 may be tough, but is not unobtainable. 

Many of the failed campaigns have a lower median pledge amount. In order to maximize success, Fever will need to appeal to individuals who are willing to contribute higher amounts.

|	|Successful|	Failed|
|---|---|---|
|Mean Goal|	$5,049|	$10,554|
|Median Goal|	$3,000|	$5,000|
|Standard Deviation of Goal|	$7,749|	$21,968|
|Upper Quartile of Goal|	$5,000	|$10,000|
|Lower Quartile of Goal|	$1,500	|$2,000|
|IQR of Goal|	$3,500|	$8,000|
|		|||
|Mean Pledged|	$5,602|	$559|
|Median Pledged|	$3,168|	$103|
|Standard Deviation of Pledged|	$8,335	|$1,331|
|Upper Quartile of Pledged|	$5,699|	$501|
|Lower Quartile of Pledged|	$1,717|	$9|
|IQR of Pledged|	$3,982|	$492|


### Conclusion
In conclusion, the best chance of success will fall in setting a reasonable pledge goal, starting the campaign in the month of May, and working to appeal to contributors with a higher spending power.


### Challenge


#### Background
The Kickstarter Fever by Louise was able to achieve a measure of success in a very short amount of time. Based on this, We want to analyze how common this rate of success is, and how time affects the overall success of a campaign.

Utilizing data from before the campaign, as well as further analysis after the campaign started- it can be concluded that.

1) Campaigns started during the month of May are the most successful campaigns. This trend is the same in both the global and United States markets. The trend also follows suit when only looking at Theatre campaigns in both the global and United States markets.

![Global Theatre Campaigns Success Based on Date](Outcomes%20Based%20on%20Launch%20Date-Challenge.png)

2) The effect of the goal of a Theatre/Play campaign roughly follows a reverse bell curve. Campaigns of $1000 or less have a 80% success rate; Past $1000 the success rate declines to 20% for campaigns between $25,000 and $30,000. At that point the success rate rises to about 67% between $35,000 and $45,000 before declining sharply once again. This means that the overall sweet spot for campaign goals is less than $1000 or between $35,000 and $45,000

![Percentage success based on total Goal](Outcomes%20Based%20on%20Goal%20Amount.png)

3) The effect of the Length of a Theatre/Play campaign roughly follows a bell curve. Campaigns of less than 7 days have an overall success rate of %40, and rises to over 80% for campaigns between 15 and 21 days. From there the success rate lowers as the length of the campaign gets longer. This concludes that the best chance of success falls on campaigns that are 15-21 days long.

![Percentage success based on Length of Campaign](Outcomes%20Based%20on%20Length.png)

#### Limitations
This overall report does not take into effect any outside influences that are typical of a campaign. There is no comparison to the overall marketing power of each of the campaigns, as well as other intangible factors such as popularity of the campaign originators, or the brand of the campaign. It can be concluded that a theatre campaign by a well known producer will automatically have an advantage in the Kickstarter field.

Another factor that is unknown at this time is the demographics of the pledges. Its unknown if certain types of campaigns appeal to certain types of demographics, and if that has an influence on the success of a campaign. Does appealing to a demographic of a certain financial level affect the success rate of a campaign?

#### Further action
In other to dive deeper in the given data, it might be useful to correlate the date success rate with other factors. How has the success rate changed from year to year? Does the trend of a may success rate correspond year over year? How has it changed?

In addition to the year, can we compare length of campaign to the months and see how the trend holds? Does a short campaign in May do as well as a longer campaign in may?

Lastly, what is the average campaign pledge by month, are there higher median pledges in may which contribute to its success?

