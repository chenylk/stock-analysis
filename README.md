# Stock-Analysis

## Overview
* In this project, I analyzed the script speed for a VBA code by refactoring an earlier solution. This code is being used to help determine the best performing stocks, from a list of 12, over the last couple of years. 


## Results
  ### Stocks
   * Stocks had a way better performance in 2017 than it did in 2018. The two stocks that had a positive percentage growth in both 2017 and 2018 were RUN and ENPH.
   
   ![Stock_data_2017](https://github.com/chenylk/stock-analysis/blob/master/stock%20data/2017_stock_data.PNG)
   ![Stock_data_2018](https://github.com/chenylk/stock-analysis/blob/master/stock%20data/2018_stock_data.PNG)

  ### Execution Times
   * The execution time for the refactored code was much faster than the original code presented. The nested for loop slowed down the code exponentially. Refactoring the code will be better suited in the long run because it will handle larger data sets better and faster. 
   
   #### Unrefactored code times 2017,2018 
   ![Time_original_2017](https://github.com/chenylk/stock-analysis/blob/master/original%20code%20times/Allstocksanalysis_2017.PNG)
   ![Time_original_2018](https://github.com/chenylk/stock-analysis/blob/master/original%20code%20times/Allstocksanalysis_2018.PNG)
   #### Refactored code times 2017, 2018
   ![Refactored_2017](https://github.com/chenylk/stock-analysis/blob/master/resources/VBA_Challenge_2017.png.PNG)
   ![Refactored_2017](https://github.com/chenylk/stock-analysis/blob/master/resources/VBA_Challenge_2018.png.PNG)
   
   
## Summary
 * The advantages of refactoring code are that the code will be more concise and more readable for others. The overall code block will look nicer and others will be able to better understand why you did what you did. A disadvantage of refactoring code is the time it takes to clean the code up. It is very time consuming and a lot of times you will run into errors that you may not know how to fix.  
 * The refactored code was able to track all of the variables through the tickerindex. This was a more efficient method than using the nested for loop which is takes more time due to the fact that the computer has to loop through additional values inside each item in the loop. In this case, the code had to loop through all of the stock data for each stock even though only that particular stock's data was needed. The tickerindex was able to track the index of which stock the data was needed for and only had to loop through all of the stock data one time. Again, a disadvantage of refactoring this code was time consumption and having to fix all of the original bugs presented with the changes. However, this time is worth it to save script running time and have the code be better understood by outside readers.
 
 * Original Code
 
 ![Code_snip_2017](https://github.com/chenylk/stock-analysis/blob/master/code%20snips/original_code_nested_for_loop.PNG).
 
 * Refactored Code
 
 ![Code_snip_2018](https://github.com/chenylk/stock-analysis/blob/master/code%20snips/refactored_code.PNG)
