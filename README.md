# Kickstarting with Excel - Ketaki's Analysis

## Overview of Project
This project collected data from different fundraising campaigns across the world and analyzes this fundraising dataset, highlighting the campaign outcomes based on their launch dates and goals.
This analysis will be helpful for making future fundraising campaigns successful.

## Analysis and Challenges
I performed this analysis using several excel capabilities such as excel functions to calculate totals, percentages of goals, COUNTIFS and count on outcomes. This data was then summarized using Pivot Tables and/or Charts for the two required analyses.
1.	Outcomes Based on Launch Date Chart
2.	Outcomes Based on Goals Chart

For 1. ,
I found that overall number of successful campaigns for Parent Category 'Theatre' is more than failed or canceled. We can see the Pivot Chart (Theater_Outcomes_vs_Launch.png) suggesting that the successful campaigns exceed the total number of campaigns across all the months.
*	The highest number of campaigns were launched in the months of May and June.
*	It is also seen that the number of successful theatre campaigns in the months of May and June were the highest.

For 2. ,
I found that there were no “canceled” campaigns for Subcategory “plays”.  This means most compaigns in this subcategory reached their completion. However, this missing piece of information cannot help one conclude that all campaigns would lead to completion.


### Challenges and Difficulties Encountered
It is difficult to conclusively derive a correlation between goals and outcome percentages because of some data points having different outcome than the ones in this catgory.

## Results

### Outcomes based on Launch Date	
*	The success of the campaign depends on its launch date. That’s why we see that a lot of campaigns being started in May and June as that period was conducive to success.
*	Overall, it can be said that the Theatre campaigns were successful.
*	The number of campaign launches reduce towards the end of the year. 
*	The number of canceled campaigns remained consistent throughout the months, start of the year (January) having the highest number of canceled campaigns.

### Outcomes based on Goals
*	There seems to be an indirect co-relation between the goal and the success percentage. As the goal increases, the success percentage of the campaign decreased, except data points between amounts $35000 -$45000, which seem to be unusual.
*	Most successful campaigns for subcategory plays have a goal of less than $1000, suggesting this goal category can be a favorite for future campaigns.
*	96% of the campaigns in this subcategory have a goal less than $20000.
*	Only one campaign greater than $45,000 was launched in this subcategory and it failed, suggesting campaigns wth higher amounts may not succeed in this subcategory.

### Limitations of this dataset
* There are some data points for the goal in the theater category between amounts $35000 -$45000, which do not follow the said pattern of the indirect relation between the success percentage and the goal amount. 
* This could be eliminated by finding more examples like these and add to the dataset or considering them as outliers.
* For plays, they don’t have any examples of canceled  or amount greater than 50000 fundraising events. 

### Other possible tables and/or graphs that we could create
* We could create charts to understand the relation of goals vs pledges for different outcomes that will help understand how the current campaign goal can be  adjusted for successful outcome. 
* A chart that can find a correlation between the duration of the campaign and its outcome.That can help underdtand if a campaign can be successful by adjusting its duration.
