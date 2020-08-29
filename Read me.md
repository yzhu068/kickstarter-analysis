# Kickstarting with Excel

## Background: 
Louise wants to start a fundraising campaign to help her to fund her play: Fever. She wants to gather a total of $10,000. 

### Purpose: 
The purpose of the analysis is to help Louise go through the data set and figure out what factors makes a fundraising campaign successful. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A piviot table was created for all the campaign outcomes based on the Launch date. Years and subcategories were added as filters to see results better. 
A line graph was created to visulize the results. The line gragh was showing campaign results over different monthes under subcategories of Play.

### Analysis of Outcomes Based on Goals
Based on the amount of moeny each campaign wants to acheive, they were divided into several different categories: < 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999, 20000 to 24999, 30000 to 34999, 35000 to 39999, 40000 to 44999, and greater then 50000. 
For each categories, the "successful", "failed" and "cancled" campaign were counted using COUNTIFS function. Since we are helping Louise to fund her play Fever, only camplain related to "plays" were concerned.

### Challenges and Difficulties Encountered
THere are functions that were not mentioned in the previous leanring sections, such as YEAR and COUNTIFS. However, after reading the instruction and refers to excel help website, it was clear how these functions are used. 
I find changing the excel functions for each cell is still difficult. For example, the tables shown in worksheet " Outcomes based on Goals", for each cell that use COUNTIFS function, I have to edit it to reflected the ranges of the money. I wish there will be a smarter way to do it. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Compaigns launched in May has the highest successful rate, and the ones launched in December or January has the lowest successful rate. 
Overall speaking, campaigns for "play" has a higher percentage for "Successful" than "Failed". 

- What can you conclude about the Outcomes based on Goals?
In general, the successful rate decreases as the "goals" increases. If Louise wants to get a fundraising of $10,000 as minimum, her chance of successful is around 50%. 

- What are some limitations of this dataset?

Although, as the Goals (amount of money) increases, the total projects numbers decreases signigicantly. On one hand, it diminish the trend showing by the gragh since it loses statistical meaning a bit; but on the other hand, it means less people would go high campaign goals, maybe it is becuase it is difficult to achieve. 

- What are some other possible tables and/or graphs that we could create?
I would also be interested to know Pledged Based on Launch Date, Pledged based on Duration (Date end-Date begin). I would Also like to know the regression between pledged and goal. 