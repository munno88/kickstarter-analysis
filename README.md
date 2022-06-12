# Kickstarting with Excel
Analysis of Kickstarter campaign

## Overview of Project and purpose 

Louise's play Fever Came close to its fundrasising goal in very short period of time.  She now wants to know how her campaign did overall in comparision to others, and if there specfic variables tha play a role on how scuessful a campaign goes.
 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
 we first started the analysis by getting the year out from launch date from kickstarter dataset and after that I careate a pivot table using parent category by "theater" and year. and I use outcomes in column, date created in rows to find out how many play was successful, failed and canceled by month. I foud out the month of may had the most successful number of play. the client can also use this pivot table to view the campaign outcomes of any month just by using row labels button on table.

![image](https://user-images.githubusercontent.com/103727169/173212554-3343bbc8-7753-49c6-a229-113aebf16fd1.png)


after creating pivot table i started creating a pivot line chart to help visualize percentage of failed, canceled and successful. 

![image](https://user-images.githubusercontent.com/103727169/173212595-2bb14f93-a64c-4f0e-83cf-6fbf74a18135.png)



### Analysis of Outcomes Based on Goals

The outcomes based on goals were analyzed by taking the ranges of dollar amount and seeing the number of successful, failed and canceled campaigns. we do this by using COUNTIF Function gethering data from kickstarter goal, successful, failed, canceled and subcategory. we then get percentages of successful, canceled and failed campaign at various daollar amount ranges. 

![image](https://user-images.githubusercontent.com/103727169/173212686-5f84bc17-573c-4047-a4f9-2adbfab51fd4.png)


after gethering a percentages of successful, failed and canceled i made a pivot chart to help visulize the percentage of out comes rate based on goal.

![image](https://user-images.githubusercontent.com/103727169/173212706-e5bc54ff-6be3-48c0-a170-4eb755a24e72.png)



### Challenges and Difficulties Encountered

There was one difficultie i Encountered first was my data set i found out it was wrong after i did my whole project so i need to start over again from scretch and  had to re-do whole thing step by step and i started to realize my launch date convertion formula was wrong since i had typo mistake and correct that error and resolved the issue. 




## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The month of may had the both highest number of successful campaign aswell as most failed. while december had the list amount of successful and failed.

- What can you conclude about the Outcomes based on Goals?

campaign with lower dollar amount ranges for goal tend to be more successful or higher rate of success while higher dollar amount range goals tend to be less successful.


- What are some limitations of this dataset?

one limitation that comes to mind is possibly using data from more recent years and comparing it to an older data set. that way our data in whole is more accurate.


- What are some other possible tables and/or graphs that we could create?

well we can create other pivot tables and chart by using parent category and subcategory and seeing the amount pledged and goal to see which category and subcategory are most successful.
