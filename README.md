# stock-analysis
## Overview of Project
  In this project we are creating a program on VBA to analyze a set of stocks performance thru years 2017 and 2018. This program will help Steve analyze the performance of a green energy company named DAQO New Energy corp. which his parents want to invest their money on. However, he wants to compare the performance of 12 different companies in order to diversify his parents portfolio. Also, we are refactoring the code that we obtained on the beginning in order to have a more complete program that will run faster; with the purpose that in the future we could refactore this code in order to analyze the whole stock market.
## Results
#### Stock Analysis
  By analyzing the performance of these 12 stocks in years 2017 and 2018. We can see that in general the stock market for these stocks was better in year 2017 than in 2018. Also, by comparing the performance throughout the 2 years of these stock; Steve should recommend his parents to not invest their money in the DQ company since in 2018 the company underperformed and lost over 60% of the value it had at the beginning of the year. Instead, they should invest in ENPH and RUN which reported a gain of over 80% in value in year 2018; and 129.5% and 5.5% in 2017 respectively. 
  



#### Refactoring Program Analysis
  To refactor the program we created a set of arrays that would store the information that we obtained throughout the loops and calculations in the program. Also, we added all the calculations inside the loops and the results printing outside of the loops; which helped reduce the oerations realized by the computer and reducing the running time from 0.637 seconds to 0.117 seconds. This means an over 80% reduction of processing time which would be significant if running an analysis to the whole stock market.
  
<img width="420" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/68616522/89115404-025ac300-d456-11ea-90a5-6024abb2c6eb.png">
<img width="422" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/68616522/89115449-4a79e580-d456-11ea-923a-6a498c4f837d.png">
  
## Summary
  All in all refactoring a code makes the program run faster and occupy less memory in the computer; Moreover, if we have to add or delete processes and calculations to the program. It gets easier to edit it because there are less lines where the variables are cited. However, it makes it harder to understand the logic and processes going throughout the program. Also, it gets more difficult to debug the program in case of compiling errors.
  In the original VBA script we had an extra nested loop that basically would make the program run for longer time. This however made the program look a little simplier to understand. In the second script we added the arrays that would hold the information obtained thru the loops and deleted a layer to the nested loops. Which helped the program to run faster, saving time and memory in the computer calculations. Also, it made the program more challenging to understand its logic and the process in the loops. 
  
