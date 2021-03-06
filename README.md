# An Analysis of Kickstarter Campaigns
This project is meant to analyize kickstarter data in order to help Louise create a successful crowdfunding campaign to fund her play in the US. Initially, her budget is estimated to be over $10,000. Given a data set of previous kickstarters from different categories across the world, the following analyses were done to help Louise identify what a successful campaign looks so that she could model her campaign in a similar fashion. The analysis looked at things like when the different campaigns were launched throughout the year and funding goals. 

The given data set contains 4115 differnet kickstarters from different categories like theater and food whose outcome, whether successful, failed, or canceled, can be seen in the following graph: 
![parentCategoryoutcomes](https://user-images.githubusercontent.com/85901073/122579056-84c68400-d022-11eb-9ddb-821cba446857.png)

Louise is mostly concerned with the theater category, and from this graph it can be seen that theater is an over successful campaign with over half of the campaigns reaching their funding goals. Next, a breakdown of the outcomes based on what month the campaigns were launched was done and can be seen in the following chart: 
![outcomesYear](https://user-images.githubusercontent.com/85901073/122579182-a7f13380-d022-11eb-8171-f6942f787670.png)
From this chart, it can be seen that, generally, the campaigns launched in May, June, and July had more success of achieving their campaign fundraising goals. 

More analysis was needed in order to draw more concrete conclusions about what makes a successful campaign like the one Louise plans to launch so some statisital analyis was also done on the data set. Filtering the data set to just look at campaigns for plays, it was found that the average fundraising goal of successful campaigns for plays was approximately $5,049 with a standard deviation being $7,749. These successful campaigns had an average pledged amount of $5,602 with a standard deviation of $8,335 which looks similar to the campaign goals. When compared to the failed campaigns whose average goal was $10,554 with a standard deviation of $21,968 but were only able to pledge an average of $559 with a standard deviation of $1,331, it can be seen that the goals of the failed play campaigns were significantly higher than the goals of the successful play campaigns. Based on this, it is recommended that Louise attempt to lower her campaign goal to more resemble those of successful play campaigns whose funding goals average to $5,049. A more visual representation of the outcomes based on funding goals can been seen in the following chart: 
![outcomeBasedOnGoal](https://user-images.githubusercontent.com/85901073/122585439-8182c680-d029-11eb-9913-9e1cfdef6342.png)

Looking at the chart, it can be seen that just under 80% of the campaigns whose goals were under $5,000 were successful, whereas success rates decreased as the funding goals increased. There is, however, a 67% success rate in campaign goals of $30,000 to $44999 so perhaps further analysis could be done to see if this is a reliable and overall successful range to recommend to Louise, although it is well over her initial goal of $10,000. 
  
Some analysis was also done on theather campaigns in Great Britain where Louise plans to hold a future campaign for a musical with an estimated budget of $4,000. It was observed that these types of campaigns are also generally successful, although the median goal for the data set was approximately $2,000 which approximately 75% of the pledged amounts were equal to or less than. So, it is recommended that Louise lower her budget for her future campaign in Great Britain, too. 

One limiation of the data set was that it didn't include the approach taken to raise money for each campaign. This information could have given addition insight on what makes a successful campaign to better aid Louise on what route to take for her own campaigns. 

One possible addition to the analysis could be to narrowed down the Outcomes Based on Goal chart to only show the outcomes of the play campaigns instead of viewing the results for all the campaign categories. A box and whiskers plot for the successful vs failed play campaigns could have also been created to visualize the statistics discussed above. Goal and pledged amounts based on launched month could have also been graphed. 





