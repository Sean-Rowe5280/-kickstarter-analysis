 # Kickstarter Campaigns: The Impact of Goals and Launch Dates on Outcomes
## Overview
Louise wants to understand how different kickstarter campaigns fared in relation to their launch dates and their funding goals. To get some answers for her we have analyized a large data set of kickstarter campaigns from 2009 to 2017. We looked at three outcomes; successful, failed and canceled campaigns and asked the questions:

-How does the month in which a campaign is launched impact its outcome?

-How does the amount of a funding goal impact the outcome?

Utlimately the purpose of this analyisis is to understand how the variables launch date and funding goal can effect the outcome of a kickstarter campaign. We want to determine what month Louise should start her kickstarter and what she should set as her funding goal in order to avoid a canceled and failed outcomes and achieve a succeessful campaign.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

To Start this analysis I created a pivot table looking at outcomes for all the kickstarter campaigns. Outcomes(successful, failed, canceled) were added as columns with the date created(launch date Month) added as rows.  I then added outcome count to the values selection to show the number of successful, failed and canceled campaigns during each month. Lastly I added the filters year and praent category which i filtered by theater to isolate those comapaigns in my table.  This then allowed me to create a simple line chart to visualize the three outcomes of theater kickstarter campaigns based on the month in which they were started.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107006216/174694856-8be84735-1f23-47b5-bf8e-69c918642b14.png)


### Theater Outcomes Based on Launch Date

In Addtion to anaylizing outcome based on launch date I examined the impact of a goals on the outcome of kickster campaigns for plays. Fot this I split the outcome data for plays into 3 catergories again; successful, failed, and canceled.  I then created a goal range(i.e., 1000-4999,5000-9999, etc) and used excel to count how many successful, failed and canceled kickstarters fell within each range. Frome here its easy to create another line chart to very clearly see the goal range of the most successful campaigns is.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107006216/174694864-618e25cc-197d-483a-82a2-8162a8785b3a.png)

### Challenges and Difficulties Encountered

Some possible challenges that could be ecn

## Results
### Outcomes Based on Launch Date
The analysis of the outcomes based on Launch date tells us that the most successful time of year to start a Theater Kickstarter campaign is in the month of May. This  can be visualized above in the chart.  We can see starting in March the number of successful campaigns was 56 but steadily increased excelerating in April and reaching its maximum of 111 successful campaigns in the Month of May. Looking at successful campaigns over the course of the year the best time for Louise to Launch her campaign would be May. 

Alteratively the greatest number of failed campaigns occurred in October.  Again this can be seen in the chart above. October sees a significant spike with 50 failed kickstarters, the most over the course of the year, and only 65 successful campaigns, far from the 111 in May.  This would be the worst time of the year to launch a kickstarter. 

### Outcomes Based on Goal
The analysis of the outcome based on the size of the goal tells us that the most successful campaigns had a goal under 5,000, 73%-76% of campaigns we're successful in this range 

### Limitations of This Dataset
In our analysis the only variables we're looking at to draw conclusions about outcomes are theater launch dates and the goals for plays when in fact we know there are many other variables that will impact the outcome. So the main limitation of the tables and charts we created for our analysis is its too simple. To create a more robust analysis we should isolate more variables and examine their impact on the outcomes of theater kickstarter campaigns(location, deadline, average donation just to name a few). Also were looking at outcomes based on launch date for the parent category THEATER and then the outcome based on goals for PLAYS subcategory, ideally we should be consitent with how were are filtering this. 

Additionally to create a more accurate prediction on how to produce a successful theater campaign we would want to run some statistical analysis of the data. Calculate the mean, medium, quartiles, IQR and identify outliers to be removed to make for a more accurate prediction.

### Additional Possible Tables and Graphs

Another chart we could add that I think is a better way to visualize the outcome based on goal amount is a column bar chart:

![Outcomes_vs_Goals_Bar_Chart](https://user-images.githubusercontent.com/107006216/175422846-04bd9e15-d187-453d-b012-166b8da8b06a.png)









