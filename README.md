# Kickstarting with Excel

## Overview of Project
#### This project analyzes Kickstarter data collected between 2009 and 2017 focusing on Theater campaign launch dates and overall funding goals. 

### Purpose
The purpose is to analyze and visualize campaigns based on their success rate relating to launch dates and fundraising goals. 
### Analysis and Challenges
#### Sheet: Theater Outcomes by Launch Date
![Outcomes Based on Launch Date](https://github.com/matthallman/Week1_Excel_Homework/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
Converted dates from Unix to dates. Separated Parent and Subcategorys. Used pivot table function to sort campaigns by:Year, Month and Category, focusing only on the failed and successful campaigns. 
#### Sheet: Outcomes Based on Goals
![Outcomes vs Goals](https://github.com/matthallman/Week1_Excel_Homework/blob/main/Resources/Outcomes_vs_Goals.png)
Used VLOOKUP and COUNTIFS to create a table showing number of successful, failed, and canceled campaigns based on original stated goal. I created line chart showing results of Percentage vs Goal. Goals were seperated into twelve different ranges starting with goals below $1000 and increasing range by $500 ending at $50,000 or higher. I used the COUNTIF function to find the number of successful, failed, canceled campaigns for each goal range and then calculated percentages from the total sum of each 

## Analysis and Challenges


### Launch Date vs Goals
Campaigns asking for a lower amount of money ($1 - $15,000) had a higher success rate of meeting their goal.The one outlier as funding goals increase is in the $40k to 45K range. Setting a goal between those numbers would give a higher change at success.

### Challenges and Difficulties Encountered
Working with COUNTIF and VLOOKUP were the biggest challenges for me. It took a while for me to get the formulas and I was stuck until i realized I needed to make the goal cells <= and >= and not just <>. 
## Results

#### - What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the data analyzed by launch date; campaigns started in the spring time [May - July] had a higher success rate than those started in colder months. May had the most successful campaigns (111). Launch date was less influential when looking at failed or canceled campaigns.
#### - What can you conclude about the Outcomes based on Goals?
Campaigns asking for a lower amount of money ($1 - $15,000) had a higher success rate of meeting their goal. As the goal grows, so does the chance of the campaign failing. Setting a goal between those numbers would give a higher change at success.
#### - What are some limitations of this dataset?
Sample size seems to be a limitation, adding additional sources from other croudfunding platforms (GoFundMe, IndieGoGo, Patreon) could help fill in some blanks.
#### - What are some other possible tables and/or graphs that we could create?
Goals vs Category/Sub Category. Size of contribution based on each goal. 
