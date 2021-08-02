# Kickstarter Analysis

# An Analysis of Kickstarter Campaigns

## Overview of Project
Assisting Louise in cleaning and analysing the data of each campaign from the Kickstarter data provided.
### Purpose
The purpose of this analysis is to see how different campaigns performed in relation to their goals and launch dates. Breaking down the data collected to further investigate specific areas of each campaign to find any relations or reasons for the outcomes based on elements like pledges, goals, location and even time of year. And compile our findings with visual assistance to give Louise a snapshot of the data and the conclusions for future campaign success.

### Analysis and Challenges
The initial action to the Analysis was to cleanse and sort the data by transposing the data to human readable text and breaking down categories; this was completed for the dates, Parent categories and subcategories. I then charted the relevant data into Pivot tables and Pivot charts for the two following deliverables.

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/nyoung246/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
The "Theater Outcomes by Launch Date" chart illustrates the outcomes relative to the time of year for the Parent Category "Theater". To produce this deliverable, all the data provided was highlighted and used to create a pivot table. The data selected to create the pivot table were "Parent Category" and "Years" which were placed under Filters, "Outcomes" which was placed under Columns, "Data Created Conversion" was placed under Rows and "Count if Outcomes" was placed under Values. Once the pivot table was created, I was able to filter the "Parent Category" to "Theater" as requested. A line chart was then created from the pivot table showing the outcomes based on the time of year.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/nyoung246/kickstarter-analysis/blob/main/resources/Outcomes%20Based%20on%20Launch%20Date.png)
The "Outcomes based on Goals" chart which illustrates the outcomes based on goal ranges. To carry out this Analysis and to produce this deliverable, the formula "COUNTIFS" was used to produce the "Number Successful", "Number Failed" and "Number Canceled" based on each goal range. The percentages of "Successful", "Failed" and "Canceled" were calculated using the formula "IFERROR". A line chart was then created to show the outcomes based on goal ranges.

### Challenges and Difficulties Encountered
A challenge of the dataset provided was that the data needed to be cleaned before the Analysis. For example the dates were not in human readable formats. I had to extract the dates in order to be able to analyse the data based on the individual year and months. Once the dates to transposed into human readable format, we were able to illustrate how the campaigns performed different seasonally as well, which was not easily visible before. 

## Results

### What are two conclusions you can draw about the Theater Outcomes by Launch Date?
The first conclusion is that there is a higher number of successful campaigns during the month of May and June, which is 25% of total successful campaigns for Theater. However, there is a drastic drop in successful campaigns with the lowest successes during the month of December. Therefore our second conclusion is that in the month of December there is a higher number of failed campaigns, which is around 5% of total successful campaigns for Theater. This could possibly tell us that December is not the optimal time to launch campaigns due to the Winter season or the busy holiday time.

### What can you conclude about the Outcomes based on Goals?
Looking at the "Outcomes based on Goals" chart for a conclusion, there is a higher success rate when the goals are less than $1,000 as they have a 76% success rate. And there is a higher fail rate for goals greater than $45,000, which has an average of 7% success rate. It seems that lower goals are easier to obtain as less pledge amounts are needed. However, these outcomes may not solely be based on the goal amount and the type of campaign as some low range goals do end up failing. Other elements like time of year could possibly be a factor on the outcomes as well.

### What are some limitations of this dataset?
One limitation is that there is no reason for why campaigns were canceled; were the canceled campaigns canceled due to the amount pledged or for other reasons. This information we cannot tell by a glance from a chart. Another limitation is that we do not get a full picture of all the campaigns when just looking at the one Parent Category "Theater".

### What are some other possible tables and/or graphs that we could create?
Another table and graph we can create is one that shows all Parent Categories, goals and outcomes to get a better picture of all campaigns and show us which Parent Category is the most popular.
