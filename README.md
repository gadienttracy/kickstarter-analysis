# Kickstarting with Excel

## Overview of Project
Louise has created and fundraised the goal amount for her play, *Fever*.  In order to help Louise decide the best time of year to launch her play an analysis was performed of the kickstarter information relating to plays and the month of the year they were released.  Additionally, a comparison was drawn between successful, failed, and canceled plays and their fundraising goals.  The broad overview of this information indicates that May is the most popular month to release a play. Plays with fundraising goals less than $1000 have the highest success rate at 76%, while plays with fundraising goals between $45,000 and $49,999 failed 100% of the time.
### Purpose
The purpose of this study is to provide Louise with an analysis that will help her determine the best month to release her play, based on past play release information.  Additionally, based on Louise's fundraising goal we can help to provide a past look at the percentage of plays that were successful, failed, or canceled with the same fundraising goal.
## Analysis and Challenges
The broad overview of this information indicates that May is the most popular month to release a play. May also sees the most successful outcomes for plays and the most failed outcomes for plays. Plays with fundraising goals less than $1000 have the highest success rate at 76%, while plays with fundraising goals between $45,000 and $49,999 failed 100% of the time.
### Analysis of Outcomes Based on Launch Date
166 plays have been released in May, making it the most popular month to release a play; 111 plays were successful, 52 failed, and 3 were canceled.  December is the least popular month with only 75 releases; 37 plays were successful, 35 failed, and 3 were canceled.  
### Analysis of Outcomes Based on Goals
Plays with a fundraising goal of less than $1000 show the highest success rate at 76%. However, it is worth noting that this group of plays totals 186, while the $1000 to $4999 group has a total count of 534 and a 73% success rate.  Plays with a fundraising goal of $45,000 to $49,999 have the smallest success rate with 0%, however there is only 1 play in this group and it failed.
### Challenges and Difficulties Encountered
The initial challenge I faced was the scrubbing of the data.  After creating my pivot chart for Theater Outcomes by Launch Date there were a few rows that were blank.  I went back to the initial worksheet to identify the rows that were not returning a date and found that my formula had not been applied to them.  After applying the date conversion formula to these rows I was able to eliminate any "blank" dates in the pivot chart.
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/91269696/147510764-6265da41-3a9f-44aa-aa58-59f38b6b0d59.png)

When examining the outcomes of plays based on launch date, May is the most popular month to release a play (166 instances), additionally it has the most instances of successful plays (111).  This is a 66% success rate for plays released in May, which is the highest success rate overall.  December has the least number of plays released (75), with the least number of successful plays as well (37). This is a 49% success rate.  Therefore, Louise should avoid releasing her play in December and may have a greater chance of success if she releases her play in May.
- What can you conclude about the Outcomes based on Goals?
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/91269696/147510799-3a1a3e05-09d2-460e-9157-bde2c94ef29a.png)

When analyzing the outcomes of plays based on their fundraising goals we see that plays whose goal is less than $1000 have the highest success rate at 76% and plays with fundraising goals between $45,000 to $49,999 have a 0% successful.
- What are some limitations of this dataset?

The first limitation of the Outcomes based on goals dataset is the number of plays with fundraising goals greater than $15,000, only 86 in total.  For a greater understanding and a more precise indicator of goal success, the goal parameters should be furter broken down in the $0-$14,000 range as this group has the largest number of instances.
The second limitation is for the Theater Outcomes Based on Launch Date.  The vast amount of information for plays released by month comes from 2014-2016, when comparing these three years the outcomes are the same (May has the most number of successful plays and December has the least), however it is worth noting the significant increase in information or number of plays released for the past three years and how the numbers could start to shift with the increase in information or plays over time. It appears the information for 2017 is not yet complete.
- What are some other possible tables and/or graphs that we could create?

The addition of a bar graph displaying successful, failed, and canceled plays by year would help to represent the significant increase in plays being released within the last 3 years.  A line chart further breaking down the fundraising goal range of $1000-$14,999 would help Louise to narrow down her financial goal setting for the fundraising of her play.
