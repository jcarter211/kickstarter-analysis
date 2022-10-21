# Kickstarting with Excel

## Overview of Project
When I first examined this data, I had the goal of helping Louise, a playwright, analyze her crowdfunding campaign for her play called "Fever". She provided a data set with a range of crowdfunding campaigns in different industries with multiple fundraising goals. I first began looking at all parts of the data on crowdfunding campaigns. After learning that "Fever" almost hit it's fundraising goal relatively quickly, I changed my focus to help Louise examine how other crodfunding campaigns performed in regards to their launch dates and fundraising goals. In order to understand this relationship, I sorted, organized, and analyzed the data provided by Louise. After looking through all of the crowd funding campaigns, I narrowed my focus to examine the theater parent category in particular. 
### Purpose
The purpose of this report is to share my findings and thoughts about how the theater campaigns fared with various launch dates and goals. Hopefully, Louise will be able to better understand the success factors of a fundraising campaign as she moves forward with her other projects in the future. I had already examined the outcomes of all of the campaigns in relation to their launch date as I processed the full data set provided by Louise. In order to help Louise focus on the theater category, I had to filter my data to only show that industry. 
## Analysis and Challenges
To conduct my analysis, I created a few visual representations of the data that helped me better process how the fundraising goal and the launch date relate to success, failure, or cancellation of the theather campaigns. 
### Analysis of Outcomes Based on Launch Date

[Theater_Outcomes_vs_Launch](./Theater_Outcomes_vs_Launch.png) 

This first image shows how the theater campaigns performed based on the time of their launch. For the purpose of this analysis, I only focused on the successful, failed, and cancelled campaigns. In order to create this chart, I had to create a Year column that extracted the year from the Date Created column. I also had to filter the data to the parent category of "Theater" and by the "Years". I organized my data to show descending order with the most successful campaigns showing first in my table. From my table, I created a chart where I am able to see a few trends and deduct conclusions based on the time the campaign was launched. 

### Analysis of Outcomes Based on Goals
I also wanted to explore how the goal amount affected the outcome of the campaign. To do this, I calculated the number of successful, failed, and canceled projects within a certain fundraising category: for example, less than $1000. I then found the percentage of successful, failed, and canceled projects in each funding range.

[Outcomes_vs_Goals.png](./Outcomes_vs_Goals.png) 

This image helped me interpret which fundraising goals had the most success/failure in the theater parent category. Something interesting to note from my data is that none of the theater category campaigns were canceled. 
### Challenges and Difficulties Encountered
As I tried to help Louise in her analysis, there were a few challenges I encountered when working with the data. I found it helpful to better organize the data by creating a few new columns. The dates in the file originally showed timestamps, which are difficult to read and understand. I converted these two columns into a readable date in the "Date Created Conversion" and "Date Ended Conversion" columns. I also split the category and subcategory column so that I could analyze the parent category and subcategory seperately. I also had to create my own data table to show the outcomes of the campaigns versus the fundraising goals. Had I not taken this step, it would have been extremely difficult to see how each the amount of fundung required changes the outcome. I think that this data set can be overwhelming to look at when first opened. Organizing the data using a variety of methods proved challenging but helped with the overall result.  
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The month with the most successful campaigns is May. As you can see on the chart, there is a large spike above May which progressivly declines as the months go on. 
2. The months with the most failed campaigns is October and July. Both of these months had 50 failed campaigns. 
- What can you conclude about the Outcomes based on Goals?
Campaigns that had a goal of less than $1000 had the highest percentage of success. 
- What are some limitations of this dataset?
Some of the limitations of this dataset include consumer preference. We do not have the ability to see the genre of play or the target audience. If a campaign was successful, perhaps it's because the play's plot interested a larger number of backers than another. We also do not know the exact meaning of some of the columns. What made something a staff pick? What does spotlight mean in relation to the data? There is more information we could gather to get a better understanding of the campaigns. 
- What are some other possible tables and/or graphs that we could create?
There are a few other tables and graphs that could be useful to create when looking at this data and finding factors for campaign success. It would be interesting to see if different countries performed better in getting close to the campaign goal. It would also be interesting to analyze if a higher number of backers had an affect on the goal as well. In terms of campaign launch dates, I would imagine it would be helpful to investigate the year and use background knowledge of the overall economy. If the campaign was launched closer to 2008, I would imagine a lower goal would have been more helpful as people may not have been willing to spend as much of their income. 
