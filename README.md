# An Analysis of Kickstarter Campaigns
## Purpose
I peformed an analysis on Kickstarter data to help hopeful playwright, Louise. I filtered data, created plots and charts, and used statistics to help Louise determine how much money to raise and what her chances were of being successful. 
![Parent Category Outcomes Stacked Column Chart Kickstarter](path/to/Parent Category Outcomes Stacked Column Chart Kickstarter.png)
![Line Chart Outcomes Based On Launch Date](path/to/Line Chart Outcomes Based On Launch Date.png)
![Box Plot](path/to/Box Plot.png)
## Recommendations
For her play "Fever", Louise should lower her Kickstarter goal considerably in order to achieve success. Her goal is more than double the mean of successful campaigns for plays. Additionally, the median pledged for successful campaigns is even lower, so she might want to consider asking for less than $3,000. Also, Louise should look to get a musical funded in Great Britain but seek less than $4,000 in order to have a good chance at success. 
# Kickstarter Challenge
## Purpose
The purpose of this challenge was to help Louise gain insight on how other Theater Kickstarter campaigns fared. I looked at the outcome of campaigns based on both launch date and goal of the kickstarter.
## Analysis
In order to begin the analysis, I first had to create a new column and extract the date created of all the theater campaigns. I then used this information to create a pivot table to find a relationship between the date created and the outcome of the campaign. 
Attached (hopefully I did this right) is a screenshot of my pivot table fields. ![Theater_Outcomes_Pivot_Table](path/to/Theater_Outcomes_Pivot_Table.png)
After this, I created a line chart displaying the three outcomes (successful, failed, and canceled) and their quantity with the months on the x-axis. ![Theater_Outcomes_vs_Launch](path/to/Theater_Outcomes_vs_Launch.png)
For deliverable 2, I used the CountIf function to count the number of successful, failed, and canceled campaigns based on 12 different goal ranges. 
I then used the sum function to get the total number of campaigns per goal range. Then, I divided the columns by the total projects column to get the percentages.
Finally, I created a line chart to visualize the relationship between the goals ranges on the x-axis and the percentage of all three outcomes on the y-axis. ![Outcomes_vs_Goals](path/to/Outcomes_vs_Goals.png)
## Challenges
I faced a couple of minor challenges during the analysis. I had to remind myself how to use the Year function for the first deliverable.
It also took me a second to figure out how to properly format the pivot table fields in order to get it to be correct.
Lastly, I had to go back in the module and remind myself how to use the CountIf function for the second deliverable.
## Results
### Conclusions about Outcomes Based on Launch Date
There are many successful Theater campaigns launched in both May and June. These months seem like the best time to start a campaign of this type.
Also, with the exception of December, there are consistently more successful campaigns than both failed and canceled campaigns combined.
### Conclusions about Outcomes Based on Goals
The percentage of successful campaigns are consistently higher than failed campaigns for < $15,000 goals, with the greatest differential being goals < $5,000.
Also, campaigns with goals > $25,000 have very little chance of success.
### Limitations and Possible other Visuals
When analyzing plays sorted by goal range, it is clear that there is very little data for higher goal ranges. 
These small sample sizes can make it hard to make concrete conclusions based on that data.
I think it would also be useful if the data was more specific regarding the location. 
Knowing what country the campaigns are from is useful, but having region-specific data in a large country like the U.S, for example could be helpful.
For an additional visualization, maybe I could create a table for Outcomes that compares the average donations of successful and failed theater campaigns.
This could give us an idea of the relationship between success and the amount backers usually donate in these campaigns compared to the failed ones.
