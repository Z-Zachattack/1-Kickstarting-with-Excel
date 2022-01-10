# Kickstarting-with-Excel
  ## 1: Overview of Project
  This analysis provides multiple ways of looking at success and failure within Kickstarter, specifically regarding theaters and plays. We will look over two metrics to evalutate kickstarter data in this repository, first using pivot tables, we will examine monthly trends to see if certain months yeild better results for starting a theater kickstarter goal. Then we will see if there is any information to be gleaned from different financial goals within plays (a subset of theaters).
  ## 2: Analysis and Challenges:
### **Analysis**
-- While analyzing the kickstarter data, it was of utmost importance to isolate the most important factors, in this case the category and subcategory of interest (theaters and plays). A simple, powerful, and fast way of organizing large swaths of data can be accomplished through pivot tables, which is the primary means of organization utilized in sheet 2 of the workbook, ["Kickstarter Challenge"](main/Kickstarter_Challenge.xlsx).
-- By isolating the theater category, we are better able to evaluate trends in the data. In this case, we can clearly see that from 2009 thruogh 2017 there is a signifigant trend of successfule plays from late spring to early fall. ![theater_Outcomes](https://github.com/Z-Zachattack/1-Kickstarting-with-Excel/blob/main/Resources/Thaeter_Outcomes_vs_Launch.png). 


--The second way we analyzed the data was by outcomes. In this case, we were looking for trends within the data-set filtered by 'theaters' and 'plays' to consider what goals are most likely to be successful. Sadly, this data is only really useful when evaluating goals under 10,000 dollars, as there are not enough larger kickstarter goals to evaluate with any sense of certainty. It is clear that there is a coorilation between asking for less money and success. Besides the outliers at the higher ends, there is a nearly linear downward slope between asking for more money and failure. ![Outcomes Based on Goals](https://github.com/Z-Zachattack/1-Kickstarting-with-Excel/blob/main/Resources/Outcomes_vs_Goals.png)


### **Challenges** - *two major challenges*
--The primary challenge was due to excel itself. While the excel suite has many powerful operations, formulas can be long and cumbersome, leading to fatigue and mistakes. For instance, Deleverable 2, "Outcomes Based on Goals" required the use of **countifs()** function, while simple to use, to find the correct information it required four unique commands (the correct subcategory, outcome, lower funding, upper funding). Off the top of my head, it seems as though a "between" function could remove one of the commands. 
  - I.E. (successful, play, betweeen 100 and 200), instead of (successful, play, above 100, AND below 200)


 ## 3: Results
  ### Results from the Theater Outcomes by Launch Date
  When looking at the data, there are clearly two conclusions we can discover from the Theater Outcomes by Launch Date. 
  -- First, as stated earlier, May and June are by far the best times to start a kickstarter campaign if one is attempting to kickstart a theater goal. 
  -- Secondly, Oct thru Dec are the worst times of the year to start a campaign. This is not only because of low success rate, but also the higher instances of failure. When looking at the graph, the further the blue line is above the red line, the higher chances of success are, conversly the closer or if the red line is higher than the blue line the more likely the campaign will fail.
  ###Results from the Outcomes based on Goals
  -- The main conclusion from the Outcomes data is that one ought to create the lowest financial kickstarter goal possible.
  ###Final Thoughts
  --- As stated above, there are signifigant limits to the dataset. The largest is the lack of information, this dataset only has around 1400 theater samples. While that may seem like a lot, it doesn't provide the depth of information necessary to have a trustworthy analysis.
  --- I think it would be interesting to see whether being a "staff-pick" would assist or hinder the success rate of a play. It seems as though staff-picks would provide higher visibility, which is likely a contributing factor for the success/failure of a kistarter campaign.
  
  
