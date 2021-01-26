# Kickstarting with Excel

## Overview of Project

Our customer, Louise, has been thinking about launching a Kickstarter to fund her play entitled Fever.  We have been working with her to identify key features of successful Kickstarter campaigns.

With our analysis she has recently decided to launch her campaign which came very close to reaching its goal.  Louise now has further questions as to why her campaign failed and how future campaigns could be improved.

### Purpose

The purpose of this analysis is to find different factors that could have improved Louise's campaign.  We are going to look at two different potential reasons that the campaign may have failed.

#### First Cause

The first cause we will investigate is whether or not the goal was reasonable.  We are going to look into other campaigns and compare how many were successful vs failed or cancelled based upon the amount of money that the campaigns were looking to raise.

#### Second Cause

The second cause that we will investigate is the launch date of the campaigns.  We would like to know whether or not the month that the campaigns were launched has an impact on whether or not the campaign was successful.

## Analysis and Challenges

Looking through the data, we have identified several key factors that lead to successful Kickstarter campaigns.  Our analysis and conclusions are outlined below.

No project is without its challenges.  We have also outlined a few of the challenges that we encountered while working through this project below.

### Analysis of Outcomes Based on Launch Date

![Outcomes Based on Launch Date](https://github.com/ForTheGold/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

The graph tells the story of the data quite clearly.  The most successful Kickstarter theatre campaigns are launched in the summer.  The best month to launch is May and June is also quite good as both have very high success rates.

It appears that there are not nearly as many successful campaigns launched in fall or winter.  February has a bit of a spike, but it does not compare to campaigns launched in summer.

It would appear that there are more campaigns launched overall in summer though as there are more failed campaigns as well as more successful campaigns than in winter.  However, the difference in the number of successful campaigns compared to winter is a great deal larger than the difference in failed campaigns.

### Analysis of Outcomes Based on Goals

![Outcomes Based on Goals](https://github.com/ForTheGold/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

Again our graph gives us a clear picture as to what is happening with the data.  It appears that there are a few sweet spots with regards to campaign goals.

The campaigns with very modest goals tend to have high success rates and then ones in the 35 - 45,000 range tend to also have very high success rates.

Below and above these numbers the failure rates tend to increase dramatically.  It seems that somewhere in the 35 - 45,000 range would be a good aim for a Kickstarter campaign that needs to raise more than a very small amount of money.

### Challenges and Difficulties Encountered

#### Launch Date

It was difficult to imagine how this data should best be visualized, but we decided upon using a pivot table.  In this pivot table, we needed to decide which of the data would be most relevant as we have a good amount of data.

##### Pivot Table

We decided that it would be best to show the statistics as to how many campaigns were successful, failed and canceled based upon the month that they were launched in.  We then filtered this data by theatre only as we wanted to ensure that our analysis was as close to Louise's plan as possible.

##### Graph Selection

Although many different visualization techniques were tried, we decided that the easiest way to understand this data at a glance would be to present the data with a line graph.

#### Goals

It was also difficult to image how this data could best be visualized, but we ended up deciding that it would be best to do it as a percentage of the total number of projects.  We separated the goals into ranges then calculated the percentages.

The line graph appears to be one of the best ways to visualize this information although a few other types of graphs were considered in the visualization process.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion that can be drawn from the Outcomes based on Launch date graph is that summer is the best time to launch a theatre campaign and May in particular is the best month of the year to launch a campaign.

The second conclusion that can be drawn is that fall and winter are the times of the year that have a much lower rate of successful campaigns with the possible exception of February.

- What can you conclude about the Outcomes based on Goals?

The first thing that you can conclude from this analysis is that very modest campaigns looking for less than 10 -15,000 tend to be successful.  This can be promising for a person who is not looking for a great deal of money.

The second conclusion that can be drawn is that campaigns that set goals in the range of 35 - 45,000 tend to be successful.  This is great news for someone who can create a production in that range of money.

The final thing that we can see is that asking for more than 45,000 or less than 35,000 (but still more than 15,000) does not appear to be a good idea as the campaigns have a very high rate of failure.

- What are some limitations of this dataset?

The limitations of the dataset come from the fact that there are simply not a huge number of records to us conclusions.  The dataset only contains just over 4000 records in total which is not that many to begin with.

The problem tends to compound when we start to break down the data.  For instance if we look only at theatre only then we have just over 1300 records, and when we look at plays then we only have just over 1000 records.

When we look at plays in December there were only 56 plays launched in total.  It is possible that with a greater amount of data we may find that launching a play in winter is not as bad as this data appears to show.

- What are some other possible tables and/or graphs that we could create?

A few of other tables that would be useful to create would be looking at the percentage funded of both the successful as well as the failed campaigns.

It would be interesting to know if the failed campaigns got almost no funding, very nearly met their goals or somewhere in between.  It would also be interesting to know whether or not the successful campaigns barely met their goals or whether they went far beyond their funding goals.

It would also be interesting to break things down by country to see where theatre and plays are the most successful.

It would also be interesting to break things down by backers.  It would be useful to know whether successful campaigns simply had more backers who each give a small amount of money, or just one or a few people who give huge amounts of money.  That would definitely have an effect on Louise's campaign strategy.
