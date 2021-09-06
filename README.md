# stock-analysis
## Overview of Project
### Purpose
###### Steve enlisted our help because his parents want to invest in green energy stocks. Wanting to analyze all the options, he put together this spreadsheet of how 12 different green energy stocks did in 2017 and 2018. Using this data, we will determine if DAQO is worth investing in.
## Results
### Compare the stock performance between 2017 and 2018
###### In 2017, the yearly return for almost all of the green energy stocks, besides one, was positive. Even DQ had a high return at 199.4%. However, most of the stocks plummeted in 2018, including DQ which returned a negative yearly return of -62.6%. 
### Compare execution times of the original script and the refactored script
###### For our yearly analysis of 2017, the refactored script ran at a time of .1484375 seconds compared to the original script which ran at a speed of .6875 seconds (shown in image below). That produced a faster script of .5390625 seconds. 
![2017 original script run time](https://github.com/liabrooke/stock-analysis/blob/main/Original_Script_2017.png) 
###### For our yearly analysis of 2018, the refactored script ran at a time of .125 seconds compared to the original script which ran at .71875 seconds. That produced a faster script run time difference of .59375 seconds. While this is not a substantial difference at the moment, this could lead to significance once our data sets become larger or we incorporate more stocks into our analysis.
## Summary
### What are the advantages or disadvantages of refactoring code? 
###### One advantage to refactoring code, which is the main reason we completed it for this module, was to get the code to run faster. Steve will eventually want to run analysis on larger datasets and refactoring will lead to faster run times. Refactoring can also make code easier to read and more adaptable. A key disadvantage would be the time it takes to refactor and fix any new bugs that arise. This issue could be exacerbated even more if the code is lengthy. 
### How do these pros and cons apply to refactoring the original VBA Script?
###### Having already been led through the module and the analysis of the "green_stocks" worksheet, it was difficult to step back and break it down even further, when the original code already worked. When I first refactored my code, my run times did not amount to a significant difference when compared to the original script run times. I had to work my way down line by line, trying to indentify any areas that I could edit. While my code did end up running faster than what I started with, it took a significant amount of time. This was also a relatively small amount of code, so if it had been lengthier, it would've been very costly in regards to time and money. However, we now have faster code so if we introduce more data into our sets, we should not come across slow run times.
