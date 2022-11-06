# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends.

## Purpose
Kickstarter is a popular platform for crowdfunding. The goal for this projecct is to analyze data from the platform to determine how create a successful crowdfunding campaign for a theater play. 

## Analysis
### Outcomes Based on Launch Date
In order to determine what would help us start a good crowfunding campaign for a theater play, I analyzed the outcomes of past kickstarters in relation to their launch dates. In order to do this, I created a pivot table and sorted that data by the months in which past campaigns had been launched and by the outcome - successful, failed or canceled -. Then, I created a line chart to determine when the best time is to launch the campaign.

![Theater_Outcomes__vs_Launch](https://user-images.githubusercontent.com/116690861/200128830-d18fc7a1-6975-414a-ab4a-f68a8c666f69.png)

### Outcomes Based on Goals
I also looked at the percentage of successful, failed and canceled crowdfunding campaigns based on the initial goal amount. To achieve this, I created a table that shows different dollar goal ranges and the number of successful, failed and canceled campaigns that each range had. After that, I calculated the percentage of successful, failed and canceled campaigns for each goal range. I used a line chart to show the results and observe the relation between the goal amount and the outcome.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/116690861/200129035-c060f8cb-51a3-4a70-803f-80ac1611b1c7.png)

## Challenges
I did not find any challenges for this particular analysis but if someone were to use this set for another project, they could encounter some. The Percentage Funded data has some outliers that could skew the outcome of any analysis. These outliers would need to be removed prior to coming to any conclusions regarding the data set. 

## Results
### Outcomes Based on Launch Date
After analyzing this data, I observed that there is a trend for successful campaigns based on what month they were launched. From March to May, the amount of successful campaigns increases, while it slows down all through the summer and reaches its lowest point in December. From this trend we can determine that the best time to launch a Kickstarter campaign is in May and the worst time is in December.

### Outcomes Based on Goals
There is also a trend found in the percentage of sucessful campaigns based on the goal amount. I can see that campaigns become less sucessful the higher the goal is. There is an uptick in success in campaigns with a goal between $35,000 and $44,999 but the data sample is very small compared to the other goal amounts. From this analysis it can be determined that a goal between $0 and $4,999 has the highest success rate.

### Limitations
There is some additional data that could be obtained in order to make a more accurate analysis. 

#### Location
This data looked at Kickstarter campaigns all over the world. It would be beneficial for this analysis if the United States data was broken down into states to see where is the best place to launch a campaign.

#### Rewards
Many Kickstarter campaigns offer rewards to the donors. It would be interesting to analyze the success rate of campaigns with and without rewards.
