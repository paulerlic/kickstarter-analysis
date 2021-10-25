# kickstarter-analysis


### Overview
In this project we are taking a look at data gathered from Kickstarter campaigns and how successful or unsuccessful these campaigns were in relation to their launch dates and funding goals. The campaigns in this data vary greatly in terms of what they are actually for, they range from tech, video games, movies, plays, and more. Our client Louise recently launched a play called Fever that fell just short of it's fundraising goal, now Louise is determined to understand the world of kickstarter campaigns. 

### Purpose
We are doing this analysis to help Louise understand more about how fundraising campaigns perform and what impact launch dates and goals have on the success of a campaign. The plan is to use this information to Help Louise plan for another Kickstarter campaign, and help to make it a successful one at that. In order to better understand Louise's what this all means for Louise we are going to analyze how other  


## Analysis and Challenges

In the project we are going to focus on two key portions by analyzing campaign outcomes based on their launch dates and the outcome of campaigns based on fundraising goals set for the campaigns. The hope is to discover patterns in these analyses that will help us better understand what makes a successful and unscuccessful kickstarter campaign.  


### Analysis of Outcomes Based on Launch Date

![Outcomes Based on Launch Date ](https://github.com/paulerlic/kickstarter-analysis/blob/6a70263085af45edc7cf1e7bab4db2c4b6a8eb56/Resources/Theater_Outcomes_vs_Launch.png)

This line chart shows what percentage of campaings with the tag Theater failed, succeeded, or were cancelled from the years 2011 to 2017. In order to better understand the data we have displayed the campaigns success or failures on a monthly timeline to see if the time of year makes any difference on the success of the campaigns. It would appear that the month a campaign is laucnhed could have something to do it with it's success or failure. From the months April to July we see a signifcant jump in the number of successful campaigns. A similar reltationship exists for campaigns that failed, however the trend is slightly different with the numbr failures staying relativley flat until August. 


### Analysis of Outcomes Based on Goals

![Outcomes Based on Launch Date ](https://github.com/paulerlic/kickstarter-analysis/blob/6a70263085af45edc7cf1e7bab4db2c4b6a8eb56/Resources/Outcomes_vs_Goals.png)

This graphic represents the percentage of successful, failed, and cancelled campaigns based on what the original fund raising goal was for the campaign. To make the data easier to interperet we stratified the fund rasing goals into groups of $5000 starting at $1000 and under, and going up to $50,000 or more. This allows us to get a better look at how the dollar amount of the fund raising goal impacts a particular campaigns success.     


## Challenges and Difficulties Encountered

There were several challenges to overcome when analyzing this data. To start the information had to formated and filtered properly so that we could better understand it and make sense of how kickstarter campaigns performed. It was a challenge to format the dates given in the dataset as they were in a UNIX format this required some conversion. Addtionally we had to create a pivot table to properly asses the outcome of theater campaigns vs. their launch dates. We had to perform a challenging VLOOKUP to better understand the the outcomes of campaings based on the intial fundraising goal, along with the use of the COUNTIFS statement this proved to be the most challenging part of the project for me.

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

### 1.

We can conclude from this graph that is ideal to launch a campaign between the months of may and June. 

### 2.

We can also conclude from this graph that if left with no other choice it is best to launch a campaign earlier in the year rather than later as failures tend to trend upwards as the year goes on. 


### What can you conclude about the Outcomes based on Goals?

### 1.

We can see that some of the most successful campaigns had a goal of raising less than $4,999. Although there is high percentage of successful campaigns that had a goal of $35,000 to $44,999. The number of campaigns with a large goal is relativley low compared to the total number of campaigns. So we can assume that these campaigns are unusual in their success. We should advise Louise that in order to have a successful campaign, the fund raising goal should be less $5,000. This is probable due to the fact that it is easier to raise less money than more money.

 
### What are some limitations of this dataset?

This dataset doesn't go into great detail on the marketing of these campaigns and how the creators of them shared the campaign with a broader audience. If we had this information it would be possible to draw better conclusions about the actual success of these campaings. 

### What are some other possible tables and/or graphs that we could create?

We could create a chart that looks at the total number of backers vs. the percentage of successful campaings. A table displaying the average donation by country could be very useful in determining what countries have the most generous backers. 
