# stocks-analysis

Analysis and visual representation of data from excel files pertaining to kick-starter campaigns.

## Overview of Project
The purpose of this project was to introduce us to a widely utilized tool and, for many of us, a beginning coding language called VBA.  VBA basically allows us to write code within excel called macros that serve particular functions within the worksheets that can make navigating and accessing data quicker and more user-friendly.  We were given a decently large excel file containing information about different stocks purchased in 2017 and 2018 in addition to how much return they grabbed and various other details.  It was our job in the project to write a macro within the worksheets that creates and completely populates a table showing how well a stock did as well notify us on how fast our code was able to pour through all the data by using a custom-made button.  The Challenge specifically had us refactor or edit the code we had initially created in our modules to see if we could reduce the time the code took to run or in other words create more efficient code that runs quicker when people attempt to run it.  The module and challenge portion of the project really tapped into our knowledge of VBA's syntax and what kinds of code lines could create faster results.   

## Results

### Stock Performance in 2017 vs. 2018
Utilizing our knowledge of pivot tables and filters we constructed a new sheet off the original data pool give nto us titled Theatre Outcomes by Launch Date where in we compressed the data into an efficiently legible and navigable pivot table that helped interpret what goal outcomes looked like depending of the time of year the campaign would launch but only for campaigns attempting to fund some sort of theatrical play.  From that table we created a chart with vibrant and clear traits to really seal the deal in terms of visualizing the data which is extremely important for potential clients who may or may not be comfortable looknig at raw data but would rather see a basic chart to help understand the trends being represented.  Said chart can be viewed here.


![OutcomesvsLaunchChart](resources/Theatre_Outcomes_vs_Launch.png)

### Execution Speed for Original vs. Refactored Code
For this sheet within the main excel project we used the same skillsets as before while putting a greater emphasis on the complex functions you can input into excel to optimize how the data is entered and represented.  For instance I would say for this sheet, being able to properly execute the COUNTIFS function was crucial to the success of the assignment as one can see when they look at our columns labeled, projects: successful, canceled, and failed.  Being able to immediately count all data cells in an especially large data set can optimize specific criteria to be seen and analyzed in a heartbeat.  Then with simple sum functions we are able to create a sense of totality for that specific data variable which in this case happened to be the total number of projects for each goal status.  The other functions utilized a knowledge of basic math and how such equations are represented in excel to calculate percentages which in a scenario of presentation, is an extremely digestible and accesible way to present numbers to pretty much anyone in the working world as well as being a good indicator set for the chart we subsequently created which compared the % of successful, failed, and cenceled projects vs. the total amount of money that was preset as the goal of the campaign.  This graph can then easily distinguish which monetary goal points had which % of success and failure etc.  The afforementioned chart can be viewed here.


![OutcomesBasedonGoalschart](resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered


## Summary

### Advantages vs. Disadvantages of Refactoring Code

### Advantages vs. Disadvantages of Original vs. Refactored VBA Script


As the months reached late spring and into summer (namely May through August) there was a noticeable increase in the amount of campaigns being created which leads me to believe that the funding of plays and theatre productions are carried out in the summer in anticipation of an autumnal theatre season of sorts as funding a play on within weeks of it being performed seems illogical.  Another conclusion I noticed was this same period of time from roughly May to August also had the highest discrepency between success and failure with success nearly doubling every month so it seems that that may be another correlating factor in creating summer campaigns in that people are more likely to donate to your cause as the weather improves. 
- What can you conclude about the Outcomes based on Goals?


Considering the general trend of the chart as a whole it can be concluded that as the target goal amount of money increased, so did the number of campaigns that failed (and inversely as the number of successful campaigns decreased) which makes sense as it seems easier to raise a smaller amount of money for a cause.  Interestingly enough as the campaign goal requirements reached roughly between $35,000-$45,000 the trend flipped and successful campaigns were roughly 30% more prominent  which could indicate that plays for which the budget lies in that range are of high enough quality to warrant the publics desire to fund them but not too expensive that the goal is not met.  However, a more prominent fact remains that absolutely zero campaign kickstarters were canceled at any range leading one to conclude that perhaps none were canceled because most of the failed campaigns were really close to their target goal and/or could put on the performance for less than required.  This would make sense as the arts are prone to budget cuts in communities all the time so being able to make do with less than the desired amount however close means a show itself never gets canceled and will make full utilization of any money donated.  

- What are some limitations of this dataset?

well, for one, our specific projects were only for plays which immediately creates a limiter on fundraising as a whole vs the specific money garnering factor for plays.  No further indication into reasons why certain months were successful in funding campaigns.  Perhaps there are outlying pieces of information that indicates irrelevant reasons why May through August has more successful campaigns and simply summarizing that they in general create better funded projects could lead to a kickstarters downfall.  Limiting Kickstarters locations to specific countries completely undermines specifcs of why they may have succeeded or failed like what if all US kickstarters that were successful occured in California but all that Failed were in Texas?  Then, creating the assumption that US as a whole has X trends would be misleading as a more specific and tailored criteria would have to be in place for several variables to create a truly accurate and trend depicting portrayal.

- What are some other possible tables and/or graphs that we could create?

A graph depicting success, failure, cancel rate of kickstarters depending on the kind of projects being created would give analysts a good idea about which types of campaigns seem to get the best funding which could be useful for marketing or non-profit based entities.  Another would be a table indicating number/% of kickstarters per month and type of campaign which could help us see if my earlier conclusion that play campaigns are more popular in the summer for an autumnal play season vs all kickstarters being more popular in the summer thus negating my conclusion somewhat.
