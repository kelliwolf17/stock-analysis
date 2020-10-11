# stock-analysis
# Contents
1. VBA_Challenge.xlsm containing the challenge

2. 2 screenshots of the elapsed run time for the script (in resources folder)

3. green_stocks.xlsm containing the module practice

# Overview of Project
The purpose of this analysis was to be able to analyize the Total Daily Volume and Returns for each ticker symbol from the data Steve provided. He originally wanted to determine whether or not Daqo (DQ) was a good investment, but has since wanted to look at other investment options for his parents. In order to do this, the source code needed to be refactored to include the other investment options.
# Results
The outputs for 2017 and 2018 are seen in the next section. The Total Daily Volumes match the module, but the Returns are slightly off. I believe this to be a rounding error at some point in the formatting code. 
## Stock Performace Comparison
See the results for 2017 and 2018 stock performance. RUN and TERP were the only stocks to improve from 2017 to 2018, though TERP still had negative returns. 

![2017_results](https://user-images.githubusercontent.com/71397190/95666538-38848500-0b20-11eb-9ab7-83ade99c5afe.PNG)

![2018_results](https://user-images.githubusercontent.com/71397190/95666539-3ae6df00-0b20-11eb-8df1-1518baf742f7.PNG)
## Script Performance Comparison
The execution times from the original script to the refactored script improved significantly. For example, the original script ran in 0.766 seconds whereas the refactored code ran in 0.230 seconds. 

Refactored script:

![VBA_Challenge_2018](https://user-images.githubusercontent.com/71397190/95690301-4dbee980-0bdc-11eb-83f7-8097403df5b5.PNG)

Original script:

![original_2018](https://user-images.githubusercontent.com/71397190/95690302-51eb0700-0bdc-11eb-92b1-b6d370f90c9a.PNG)

# Summary
Refactoring code allows one to improve the logic of source code. It can allow for cleaner, more concise code and make it easier to maintain. This is helpful if you want to expand your code to evaluate more items, like in this case we refactored it to evaluate 12 tickers as opposed to just 1. With more complex code and with a limited amount of time, I could see that refactoring may be a burdensome task not worth the effort. It could take too much time, and depending on the amount of people working on the code, cost could become a factor. 

In this particular case, I do not see any disadvantages of refactoring. It was fairly simple script, in a simple program, running a relatively small data set. The larger the data, the more complex the code, refactoring can take a lot more time and resources. We were also able to evaluate more outputs in a more efficient code with relatively little extra time involved. 
