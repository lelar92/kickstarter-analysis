# An Analysis of Kickstarter Campaigns for Plays

## Overview of Project

### Purpose 
The purpose of this project is to look at different Kickstarter campaign outcomes for plays in relation to their launch dates and their funding goals to determine trends.

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date
Using the data about Kickstarter campaigns I created a pivot chart and added filters for the parent category theater, and chose plays as the sub-category. I also added a filter for years since we want to analyze the data by month of the year. I removed the column for live campaigns since that information isn't relevant. Using the information in the pivot chart I created the following graph.
![image](https://github.com/lelar92/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
The only challenge was that it was necessary to extract the year from the date the campaign was started, but this was easily accomplished by using the =YEARS function in Excel.

### Analysis of Outcomes Based on Goals
Using the same data about Kickstarter campaigns as above I extracted data showing the number of successful, failed, and canceled Kickstarter campaigns for plays based on a dollar range set for their goal. This was accomplished using the =COUNTIFS function in Excel and filtering for each dollar range and the outcome. I then used the data to create the following line graph to display the information.
![image](https://github.com/lelar92/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
 - Based on the data it appears that campaigns launched in May and June are more successful at reaching their goal. The data also shows that campaigns launched in June and July had roughly an equal number of failed campaigns.

- What can you conclude about the Outcomes based on Goals?
The data shows that campaigns with goals under $5000 had the highest rate of success.

- What are some limitations of this dataset?


- What are some other possible tables and/or graphs that we could create?
A box and whiskers plot would help to show the distribution of goals and total amounts pledged for plays in the US. This would expose any outliers which may skew the data.
