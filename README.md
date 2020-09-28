# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to determine the optimal strategy for launching a Kickstarter campaign to fund a future play. The data used to attempt to reach this conclusion is based
on the launch date of past campaigns, as well as how successful past campaigns were based on if they met their respective funding targets or not.

## Analysis and Challenges
The analysis was done in two parts. First, determining the best month to launch a a kickstarter campaign. This was done by isolating the theater campaigns from the original data set, and splitting them up by month. 
Campaigns in each month were futher categorized as either successful, failed, or canceled. The second metric looked at whether or not a campaign met its targeted fundraising goal. Targets were split up by dollar amount to get a more
accurate picture for each bracket. This is important because it differentiaties the smaller budget local plays from the larger productions. Both analyses were made into charts for ease of absorbing information. 

### Analysis of Outcomes Based on Launch Date
Based on launch date, it is clear that the second quarter of the year is the best time to launch a Kickstarter campaign for play fundraising. ALso, the worst time to launch a campaign are the winter months.

### Analysis of Outcomes Based on Goals
The graph of outcomes based on goals shows that the most successful category is the one with the most modest fundraising goals. The second highest fundraising target group was the least successful.


### Challenges and Difficulties Encountered
The major problem I encountered while doing the analysis was effectively using the COUNTIFS function in EXCEL to split up the campaigns in the second analysis. To overcome this I looked at the Microsoft documentation as well as YouTube videos.
As I will expand upon later, it was also difficult to draw many meaningful conclusion based on the limitations of the data set.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Since the most successful campaigns launched in Q2, the plays people were most enthusiastic about came out later in the year. This data wasn't made available for this analysis (expanded upon later.) 
Also, the peak and trough type shape of the graph indicates that people likely suffer from 'fundraising overload.' Once they donate to a campaign, there is a period of a respite before wanting to donate again.

- What can you conclude about the Outcomes based on Goals?
One can conclude that in general there is a inverse correlation between the targeted donation and the percent chance that it will be successful. It is fairly self evident that the lowest goals were the most successful as they requested the least amount of money.
The the second highest target group likely encompassed fairly large scale productions, but not those of a 'Broadway level' notoriety, example. This is probably why they were the least successful.
 
- What are some limitations of this dataset?
The dataset provided information on the successful of the campaigns, but not how well the the plays themselves did. Theoretically, a campaign could do poorly and not meet its goal, but the play itself could sell out every night. 
If one wants to properly measure the success of a campaign, there needs to be data that ties to how well the play did as well. The geography category is also much too broad. It is only at the country level, and there are numerous communities within these countries with varying demographics.
One would want to see the demographics, and preferably average income level, of where the play was produced to see how that correlates with its fundraising goals. The dataset was also severly lacking data on campaigns with higher fundraising goals, making it difficult to draw meaningful conclusions to aid future campaigns.

- What are some other possible tables and/or graphs that we could create?
As I mentioned in the previous question, tables could be added with data of more specific geography, financial success of the play (measured in ticket sales.) One graph that could be added is one that synthesizes the information from the two charts we created.
It would show the success of the campaign based on it's goals, but with the month launched on a third axis. This would make it easier to visualize if there is any insight into whether the financial amount of the goals are effected by launch month at all.
