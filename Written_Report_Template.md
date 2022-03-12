# Kickstarting with Excel

## Overview of Project
 
### Purpose - To determine the best time to launch a fundraiser for a play and determine a feasible goal for that play. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

  I had to create a pivot table to make sure I was only analysing the correct data. Making sure we categorized the launch dates by montha and whether or not they were successful, failed, or canceled. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90650209/157999184-331712c4-edc0-4848-8f05-0460349821ac.png)

### Analysis of Outcomes Based on Goals

  This analysis was done by using countifs functions to make sure data was categorized by goal amounts and whether they were successful, failed, or canceled. One of the keys to making sure it worked correctly was thinking about exactly how the numbers should be represented in the goals. EX. =COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<=4999",Kickstarter!$R:$R,"plays")


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90650209/157999193-a027d5e8-2b81-4c1c-a913-67d4fb97fce1.png)

### Challenges and Difficulties Encountered

  I did have some difficulty at first finding a way to make the pivot table have rows by months. I was able to used the date conversion to finally get it to show the rows as months. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  
  You can see clearly that the optimal time to launch would be in May or Early Summer. Also overall Launches are more successful than they are failures. 
  
- What can you conclude about the Outcomes based on Goals?
- 
  If you keep your goal smaller you have a higher chance of success when funding your play. 
  
- What are some limitations of this dataset?
- 
  It doesn't account for seasonal productions. Christmas and Holiday plays may be more likely to be funded in the Holiday season but the data has a hard time capturing that. Also if we had a category for playright or artist we may glean some data on if there specific productions are more likely to be funded. 
- What are some other possible tables and/or graphs that we could create?

  We could create an average donation based off of either goals or type of fundraising efforts in a way to see where more money is commited in projects. 
  
