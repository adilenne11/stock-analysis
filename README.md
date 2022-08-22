# Stock Analysis for Steve
## Purpose 
The purpose of this project is to refractor or edit a VBA code to collect data for the entire stock market over the years. In this project we are looking at data of 12 different stocks for the years 2017 and 2018. There is a table with lots of information about each stock for each year. However, Steve only wants to retrieve information about each stock’s ticker, total daily volume, and the return. Once Steve has this information, he will determine whether to invest in these stocks. A refactored VBA code will retrieve this information that Steve needs for thousands of stocks.
## Results
In this project we are looking at data of 12 different stocks for the years 2017 and 2018. The performance of the 2017 stock market is positive. Every stock, except one, for the year 2017 had a return from 5.5% to 199.4%. But the 2018 stock market is negative. Almost every stock, except two, for the year 2018 had a negative return from -3.5% to -62.6%.

The refactored VBA code for 2017 takes about 0.25 seconds to run. The refactored VBA code 2018 takes about 0.23 seconds to run.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/110357810/186021953-607ee674-515d-4a86-b54a-ad68025e693d.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/110357810/186021961-40e5985b-4648-47d1-9f72-fad9ceccf284.png)

## Summary of the Pros and Cons
The original VBA code took about one second to run. Refactoring the VBA code made it simpler to output information therefore it was faster to run. An advantage of a refactored VBA code is that it can be used for a bigger chunk of data. Another advantage of a refactored VBA code is that there are less steps therefore more efficient and quicker to run. A disadvantage of refactoring code is being able to break complex codes into several functions.

An advantage of the original VBA script is that it is easy to read because it is only focused on two table. A disadvantage of the original VBA script is that it is created to only process a certain number of rows. An advantage of the refactored script is that it can process thousands of rows. A disadvantage is it can be difficult to write the code because it needs to be able to work for a bigger set of data in the future, so comments within the code need to be clear to understand so the next person using the code will be able to make any adjustments if needed.
