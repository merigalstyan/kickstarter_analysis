# **Kickstarting with Excel**
 
## Overview of Project
 
In the previous project, Louise wanted to start a campaign to help fund her play "Fever.” She needed to analyze the Kickstarter data to determine all specific factors that make a campaign successful. While Louise came close to her fundraising goals, she still needs additional information. This project will focus on combing through the Kickstarter data even further.
 
### Purpose
This project aims to understand the outcomes of different campaigns using visualization tools and methods. The outcomes of campaigns would be based on their launch dates and funding goals.
 
## Analysis and Challenges
 
As mentioned above, the analysis would determine the outcomes of campaigns based on their launch date and funding goals. The first part of the analysis would focus on the outcomes based on launch dates. 
 
### Analysis of Outcomes Based on Launch Date
In the first section of the analysis, I used the “Kickstarter” dataset to create a  pivot table. I filtered the table based on “Year” data to determine the number of successful, failed, and canceled campaigns. Since Louise is interested in the outcomes of theatrical plays, I also filtered the outcomes based on the parent category “theater.” 
 
**Here's a graph of the outcomes:**
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111609994/187269606-302ad81b-b810-44e8-ac40-679add25bf64.png)

 
### Analysis of Outcomes Based on Goals
The next step of the analysis would be uncovering the percentage of successful, failed, and canceled plays based on their funding goal. I used the “COUNTIFS” function in this section to filter the sub-category by plays, outcomes, and fundraising goals. This allowed me to determine the numbers of successful, failed, and canceled campaigns. Based on the resulting data, I calculated the percentage of successful, failed, and canceled campaigns.
 
**The visual of the outcome:**
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111609994/187269629-2b0abe45-5500-4291-9936-e33ccbb3e2da.png)

 
### Challenges and Difficulties Encountered
One of this analysis’s challenges was ensuring the "Countifs" function returned all the correct numbers. Since I needed to filter the data by the goal, outcomes, and categories, I created an extra pivot table to double-check all the correct numbers for my analysis. In addition, since canceled plays were 0, I used the pivot table for double-checking if my analysis was correct.
 
## Results
 
### The Outcomes based on Launch Date.
 
I determined that the most successful campaigns throughout the years have been around May and even June. This gives Louise an edge to organize her campaign around that time to be more successful. 
Although May has a significantly high success rate, it should be mentioned that failed campaigns also increase around May till August.
 
### The Outcomes based on Goals.
The results indicate that the higher the fundraising goal is, the more failed plays there are. As the fundraising goal increases, the number of failed plays also increases. Lower expectations of fundraising goals result in more successful projects. We can assume that fundraising goal has a direct link with success. Although it may not be the only reason for failed campaigns, it has a huge impact, and Louise should consider a lower budget.
 
### The limitations of the dataset?
 
This dataset’s limitations include insufficient metrics to understand the reasons behind successful or failed campaigns. We know which categories are successful based on fundraising goals and launch dates, but we don't know what other factors impact the success rate.
Additionally, there aren't enough metrics to describe why success and failure rates increase during relevant periods. 
The dataset has outliers.
 
### Possible tables/graphs:
 
Aside from the graphs showcased above, this analysis would be easier to understand if we filtered the results based on launch date by country. This graph would compare different countries and their success and failure rates and allow Louise to focus her efforts in a specific country where success is higher.
 
In the previous project, the analysis included determining the outliers of the dataset. Based on this information, this analysis could include a table or a graph that excluded all the outliers and allowed more precise data to be displayed.
 
Finally, another graph would compare the campaign outcomes based on average donations. Average donations could work as another metric to capture another reason for different outcomes. 
