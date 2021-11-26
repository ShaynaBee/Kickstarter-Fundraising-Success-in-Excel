# Kickstarter-Fundraising-Success-in-Excel
Analysis of Kickstarter Fundraising Efforts in Excel
# Kickstarting with Excel

## Overview of Project
This project intends to analyze data from thousands of Kickstarter campaigns to discover any trends among successfully launched projects.  
### Purpose
The purpose of this project is to best predict the outcome of a campaign launched for a play with a goal of $10,000, by comparing the previously gathered data's success rates based on their goals, and launch dates.
## Analysis and Challenges
To preform this analysis I first had to determine the outcomes of every play launched within each month, to determine the mpost opportune time to launch our campaign. First the data was filtered within the origional sheet to show only plays, and their subsequent outcomes. However, this was still a large amount of data to comb through and not very organized, so to simplify it further I created a pivot table grouping successful, failed, and cancelled projects, against the months listed on the right side of the table. Then to display the data in an even more discernable way, I created a line graph charting the findings from the pivot table. 
![Outcomes By Date Pivot Chart](https://user-images.githubusercontent.com/94236316/143661364-cb2f4c1d-da12-499a-94c3-41d623d0c677.png)

Secondly, I needed to create a seperate sheet showing the percentages of success for projects of various funding goals. This would allow us to determine if the goal of $10,000 was reasonable based on the outcomes of other projects' goals. In order to do this I used a "COUNTIFS" function to count all the campaigns that fell into certian categories we were looking for. I first grouped them based on their traget goal, with ranges of $5,000. Then to show us results more tailored to our project specifically, I included in the function to only display "plays". Finally our last variable was based on whether the outcome was successful, failed, or cancelled.
![outcomes based on goal chart](https://user-images.githubusercontent.com/94236316/143661370-82b69766-f8b3-4e9b-b74c-454e136e812d.png)

### Analysis of Outcomes Based on Launch Date
When analyzing the line chart created for the outcomes based on thier launch date, the most obvious finding is a large spark in plays successfully funded in the month of May, and slighty less but still high numbers through August. The lowest month for successful outcomes was in December after slowly declining from the summer months. This could be for any number of reasons such as outdoor plays being less desriable in cold months, or the financial stress of the holidays not allowing for extra income to be spent on funding projects such as these. Failed projects stay at relatively the same rate throughout the year without much fluctuation, which means that there must be a different variable effecting whether or not a project fails.   
![Theature Outcomes vs Launch](https://user-images.githubusercontent.com/94236316/143661380-cbdd68bf-35ee-4bf5-80d4-0016dd923794.png)

### Analysis of Outcomes Based on Goals
When we disect the data found when we compare the outcomes of each project based on the financial goal we can see that theres a very sharp decline of the percent of projects funded after $5,000. Projects begin to have a much higher failure to success rate as the amount needed goes higher. Successful plays to take a higher percentage around the $35,000-$40,000 mark, however the amount of plays in this range is only abuot 6, as opposed to about 600 in the $0-$10,000 range. This being the case would make anything higher than $10,000 inapropriate goal for our project, with the ideal range actually being betwee $0-$5,000 for the highest change at success.  
![outcomes based on goal](https://user-images.githubusercontent.com/94236316/143661386-de854b1f-217f-4f15-b29d-494cf1f226af.png)

### Challenges and Difficulties Encountered
Most of the challenges I faced during this project happened when I ws trying to determine exaclty what data i needed to analyze in order to yeild the results I was looking for. Properly formatting the pivot table with the correct categories and writting the COUNTIFS function properly took lots of trial and error. However, after giving lots of thought to exactly what I was trying to determine and the role each category plays in our data, I was able to visualize what I needed more clearly and create the proper output. 
## Results
Based on the data we analyzed, we could conclude that the goal of $10,000 was potentially too high for this project to have a good chance at being successful. The ideal goal seems to be under the $5,000 mark. We also can colclude that the best time to launch the campaign would be in May, or possibly sometime in the summer months as well. However thse closer we get to December the likleyhood of it being a success goes down.    
