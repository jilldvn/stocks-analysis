# stocks-analysis

## Overview of Project

This project is to allow a visualization of each stock overall performance in 2017 and 2018 with its total volume and year-end returns. 
By creating two different VBA macros, the purpose is to compare the difference when using refactored code how the processing time could be significantly enhanced. 

## Results

The stocks highlighted in "Red" is with negative returns vice versa, stocks in "Green" has positive return. 
Therefore, at galence comparing to 2018 from 2017 performance, stock perfomance in 2017 has higher rerturns overall than 2018. 

In terms of original and refactoring code, using refactoring script processed the same dataset much faster than original script, refactoring script took 0.18 second to complete analysis, while original scripte needs 1.18 seconds to run.
As a result, it is found refactoring code peforms more efficently than original one. 

## Summary

One of many advantages identified in refactoring script is by establishing Index to allow inerate by stocks at the same time without using nested loops can reduce multiple calculations in the loop. Thus it could save tremandous amount of time to process. 

Disvantage for new developer like me, I found that refactoring codes changing the iterator to index establishment is not too straight forward like creating a nested loop, it requires more attention to ensure each variables are defined correctly. 

On the other side, using original script with nested loop is logically simple to me with less errors occurred so that saving more time for debugging; however, being an end user who only needs the an analysis of outcomes, it takes much longer to get to results, espcially when the data size becomes larger. 
