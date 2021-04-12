# Stock-Analysis

## Overview of Project
The purpose of this Analysis was to gain a functional understanding of VBA. In this particular example we used VBA to assist Steve, a recent Finance Graduate, evaluate the performance of Green Energy stock data from 2017 and 2018 for his parents. We also evaluated the script running the analysis to see the effects, if any, of refactoring our code.

## Results

**Stock Performance 2017 - 2018**

In 2017, the handful of Green Stocks selected for this analysis performed very well. Out of 12 stocks, 11 had positive returns with half of the stocks having 50% returns or higher. 2018 told a very different story with every stock except 2 showing negative returns. The two positively returning stocks in 2018 also showed positive returns in 2017, these two stocks were 'RUN' and 'ENPH'. Out of those two positively returning stocks, ENPH was the better performer with 129.5% returns in 2017 and 81.9% returns in 2018. Steve's parent's initial bet was on 'DQ', but Steve would be wise to advise against that stock due to the -62.6% returns performance in 2018. If I had to suggest a stock to Steve's parents over 'DQ', it would be ENPH.


2017 Performance

<img src="https://github.com/niklasax/stock-analysis/blob/main/Resources/Stock%20Performance%202017.png" width="200" height="200" />

2018 Performance

<img src="https://github.com/niklasax/stock-analysis/blob/main/Resources/Stock%20Performance%202018.png" width="200" height="200" />

**Run time analysis**

Another Analysis performed was the time it took to run the script iteself. We compared the initial code's time performance against our later 'refactored' code's time performance. In comparison, refactoring the code reduced the time to run by about 75%. the initial code took around 2.85 seconds to run while the rafactored code took only around .7 seconds to run.

Refactored

<img src="https://github.com/niklasax/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png" width="400" height="130" />
<img src="https://github.com/niklasax/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png" width="400" height="130" />

Not Refactored

<img src="https://github.com/niklasax/stock-analysis/blob/main/Resources/2017%20(not%20refactored).png" width="400" height="130" />
<img src="https://github.com/niklasax/stock-analysis/blob/main/Resources/2018%20(not%20refactored).png" width="400" height="130" />


## Summary

**Pros of refactoring code**

Manageability- Code that has been refactored is much easier to troubleshoot. With good code that is concise and well noted, any potential bugs are much easier to fix. For example, our refactored code was well documented and notated so if another person were to go into the code to try and debug, they would what each grouping of code's task was.

Scaleability- Code that has been refactored is more efficient. Cutting down on unnecessary or redundant lines of code and can run the same tasks with less resources which ,in the end, will allow you to process more data. In the stocks example, we saw a 75% reduction in speed, reducing the time to run from around 2.85 seconds to .7 seconds. This may not seem like a lot of savings in terms of time, but the reduction becomes more meangingful when we have more data we have to process. For example, if our initial analysis took an hour to run, refactoring would have cut down the time to run to 15 minutes.
