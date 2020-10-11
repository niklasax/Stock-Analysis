# Stock-Analysis

## Overview of Project
The purpose of this Analysis was to gain functional understanding of VBA. In this particular example, we used vba to help Steve, a recent Finance Graduate, help his parents evaluate the performance of Green Energy stock data from 2017 and 2018.

## Results
In 2017, the handful of Green Stocks selected for this analysis performance very well. Out of 12 stocks, 11 had positive returns with half of the stocks having 50% returns or higher. 2018 told a very different story with every stock except 2 showing negative returns. The two positively returning stocks in 2018 also showed positive returns in 2017, these two stocks were 'RUN' and 'ENPH'. Out of those two positively returning stocks, ENPH was the better performer with 129.5% returns in 2017 and 81.9% returns in 2018. Steve's parent's initial bet was on 'DQ', but Steve would be wise to advise against that stock due to the -62.6% returns performance in 2018. If I had to suggest a stock to Steve's parents over 'DQ', it would be ENPH.

**Stock Performance 2017 - 2018**

<img src="https://github.com/niklasax/stock-analysis/blob/main/Stock%20Performance%202017.png" width="200" height="200" />
<img src="https://github.com/niklasax/stock-analysis/blob/main/Stock%20Performance%202018.png" width="200" height="200" />

**Run time analysis**

Another Analysis performed was the time it took to run the script iteself. We compared the initial code's time performance against our later 'refactored' code's time performance. In terms of performance comparison, there was little to no difference in performance between the original and refactored code. Both scripts ran in the range of 2.8 to 2.9 seconds.

Refactored

<img src="https://github.com/niklasax/stock-analysis/blob/main/VBA_Challenge_2017.png" width="400" height="130" />
<img src="https://github.com/niklasax/stock-analysis/blob/main/VBA_Challenge_2018.png" width="400" height="130" />

Not Refactored

<img src="https://github.com/niklasax/stock-analysis/blob/main/2017%20(not%20refactored).png" width="400" height="130" />
<img src="https://github.com/niklasax/stock-analysis/blob/main/2018%20(not%20refactored).png" width="400" height="130" />


## Summary

**Pros of refactoring code**

Manageability- Code that has been refactored is much easier to troubleshoot. With good code that is concise and well noted, any potential bugs are much easier to fix. For example, our refactored code was well documented and notated so if another person were to go into the code to try and debug, they would what each grouping of code's task was.

Scaleability- Code that has been refactored is more efficient. Cutting down on unnecessary or redundant lines of code and can run the same tasks with less resources which ,in the end, will allow you to process more data. In the stocks example, we did not see much in improvement in the runtime between initial and refactored code. This could be an indication of either an already efficient initial script, or an indication of further potential improvement needed in the refactored version.
