# Kickstarting-with-Excel
  ## 1: Overview of Project
  This analysis provides multiple ways of looking at success and failure within Kickstarter, specifically regarding theaters and plays.
  ## 2: Analysis and Challenges:
### **Analysis**
-- While analyzing the kickstarter data, it was of utmost importance to isolate the most important factors, in this case the category and subcategory of interest (theaters and plays). A simple, powerful, and fast way of organizing large swaths of data can be accomplished through pivot tables, which is the primary means of organization utilized in sheet 2 of the workbook, ["Kickstarter Challenge"](main/Kickstarter_Challenge.xlsx).
-- By isolating the theater category, we are better able to evaluate trends in the data. In this case, we can clearly see that from 2009 thruogh 2017 there is a signifigant trend of successfule plays from late spring to early fall. ![theater_Outcomes](https://github.com/Z-Zachattack/1-Kickstarting-with-Excel/blob/main/Resources/Thaeter_Outcomes_vs_Launch.png). 
--The second way we analyzed the data was by outcomes. In this case, we were looking for trends within the whole data-set to consider what goals are most likely to be successful. Sadly, this data is only really useful when evaluating goals under 10,000 dollars, as there are not enough larger kickstarter goals to evaluate with any sense of certainty. ![Outcomes Based on Goals](https://github.com/Z-Zachattack/1-Kickstarting-with-Excel/blob/main/Resources/Outcomes_vs_Goals.png)
### **Challenges** - *two major challenges*
--The primary challenge was due to excel itself. While the excel suite has many powerful operations, formulas can be long and cumbersome, leading to fatigue and mistakes. For instance, Deleverable 2, "Outcomes Based on Goals" required the use of **countifs()** function, while simple to use, to find the correct information it required four unique commands (the correct subcategory, outcome, lower funding, upper funding). Off the top of my head, it seems as though a "between" function could remove one of the commands. 
  - I.E. (successful, play, betweeen 100 and 200), instead of (successful, play, above 100, AND below 200)

-- The second challenge 
 # 3: Results
