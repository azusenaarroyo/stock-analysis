# Stock Analysis with VBA

## Overview of Project
Twelve stocks were analyzed over the years of 2017 and 2018 to provide data on which stocks had a positive and negative yearly return along with their total daily volume. In addition, the initial code was refactored to improve script run time. 

## Results
In 2017, DQ had the highest yearly return at 199.4% return, and TERP had the lowest yearly and negative return at -7.2%. In 2018, RUN had the highest yearly return at 84%, and DQ had the lowest yearly and negative return at -62.6%. ENPH and RUN were the only two stocks to show a positive yearly return in both years, with ENPH having the highest yearly return of over 80% in each year.

Refactoring the code allowed the code to run over four times faster for the analysis of each year.  Before refactoring the code the script run time for the stock  analysis of years 2017 and 2018 was 0.5859375 seconds and 0.6054688 seconds, respectively. Below you will see the images of the script runtime for each year after  refactoring the code.

### 2017 Stock Analysis Script Run Time

<img width="334" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/91927712/140628070-6f41dbd6-4a1d-4599-82eb-5a3e98720753.png">

### 2018 Stock Analysis Script Run Time

<img width="305" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/91927712/140628071-5caa14c1-c9b8-4f82-9492-211fa8acab83.png">


## Summary
  In general, refactoring code can enhance performance by using less memory and improving the logic of the code by reducing the amount of steps needed to run the script. In addition, it can improve the quality of the code by improving bad patterns and preventing future defects. Some of the disadvantages of refactoring code may be running into functionality errors and the amount of time it can take to refactor large data sets. 
