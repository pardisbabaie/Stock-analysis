# Stock-analysis
## Overview of Project
Steve is a finance degree graduate with his parents as his first clients. His parents want to invest in green energy and have chosen one specifically to invest in and want Steve's expertise to see if they have made the right decision. We have been given data for a variety of different green energy stocks performance. 
### Purpose
The purpose of this project is to help Steve by analyzing the expanded data to include all the stock market data for the past few years to see how all the energy saving stocks have performed. 
## Results
### Year over year Analysis
The stock data analysis for 2017 shows a positive return on all stocks but one with DQ having the highest return but the lowest daily volume as shown in the image: 

<img width="245" alt="Screen Shot 2020-09-06 at 10 56 04 AM" src="https://user-images.githubusercontent.com/69806770/92329866-644faf00-f038-11ea-9f3d-a100db82fe02.png"> 

The year over year return however shows a significant drop in the return of most of the stocks and an increase in the total daily volumes. There are only two stocks "ENPH" and "RUN" that had a positive return in 2018 as shown in the image:

<img width="248" alt="Screen Shot 2020-09-06 at 10 57 15 AM" src="https://user-images.githubusercontent.com/69806770/92329947-0e2f3b80-f039-11ea-8be5-ee577dadc6c4.png">

### Analysis of script execution times
The refactored code script execution time of both years has significantly decreased from the execution time of the original scirpt as the original script would have to run through the code 12 times to capture all the total daily volumes for the 12 ticker arrays. The refactored code only needs to run through the data once to give the same results which significantly reduces the code running time as shown:
#### Original vs Refactored Script Execution times
##### Original Script 2017
<img width="429" alt="Screen Shot 2020-09-06 at 12 11 42 PM" src="https://user-images.githubusercontent.com/69806770/92330325-fe652680-f03b-11ea-97dd-175e8f839230.png">

##### Refactored Script 2017
<img width="431" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/69806770/92330350-22286c80-f03c-11ea-9276-b156b157431c.png">

##### Original Script 2018

<img width="425" alt="Screen Shot 2020-09-06 at 12 11 18 PM" src="https://user-images.githubusercontent.com/69806770/92330393-93681f80-f03c-11ea-938f-8d6d9b666b24.png">

##### Refactored Script 2018

<img width="433" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/69806770/92330446-d6c28e00-f03c-11ea-9b78-13df813d67e9.png">

## Summary
There are definite advantages in refactoring code as it provides a baseline of code that you can improve upon. This allows for the existing code to be made more efficient both in number of steps and ultimately the script run time. However, one of the disadvantages is that if the initial code we are working off of was not formatted properly it can make it more difficult to refactor. Also, for beginner coders the process of refactoring requires thinking in a different way about the code which is a challenging process.
The advantages of refactoring the VBA challenege code is that it runs much more efficiently only having to run trhoguh the script once instead of the 12 times the original script had to run. It also avoids having to use a nested loop which can make the script more complicated. The disadvantages of refactoring this code are only that working off the original code can pose the potential for more bugs within your data source and you have to go through the process of debugging so that the code can run correctly. 
