<<<<<<< HEAD:README.md
# # Fintech BootCamp Project 1
 #   **Monte-Carlo Simulation and Portfolio Optimization**

![](https://github.com/blueprint99/Fintech_Bcamp_Project1/blob/MishraSubash-patch-1/images/Overview%20Images.png.png)

## Prepared By: 
  * **Kavin Minchala**
  * **Aljohara Aloudan** 
  * **Subash Mishra** 
  * **Victor Martinez**
  
  # Project Outline 
# Introduction : 
### As mention in the title, this project has two seperate but interliked analysis of protfolio constructions. 
## A. Monte Carlo Simulation: 
### Monte Carlo simulation involves using random number generators to simulate random effects. Simulating a historical prices for many times allows us to measure the variation just as we would if we took many samples of a real event. In this project we are using 30 years historical data to anlaysis risk-return pattern of an user desired portfolio. 

## B. Portfolio Optimization : 
### Portfolio optimization is the method of selecting the best performing portfolio, out of the set of all portfolios being considered based on the amount of investment in each stock. Our project would select that portfolio which yeilds the highest sharpe ratio out of 5000 seperate portfolio meaning the highest expected return for desired level of risk. 

## Purpose of Project: 
 * to run numerious simulation to analyse the underlying risk-retrun tradeoff of user desired stocks/portfolios. 
 
 * to get the optimum investment weight (Asset allocation) so that user could  pontentailly optimized portfolio to obtain highest sharpe ratio and expected to beat the market. 

## Hypothesis : 
### It is possible to beat the market whne allocating optimum weight in a stock portfolio. 

### The well diversified and properly allocated portfolio could possibly beat the market. 

## Data Source : 
### To evaluate the project, we use Yahoo Finance as our primary data source. The reason using yahoo Finance is to get Adj Close. The adjusted close reflects stock dividens and stock splits which gives better idea of the overall value of stock and help making informed decision about trading stocks. 

## Timeframe :
### In the first part of the project, we run numerious( user can opt any number of simulations) Monte-Carlo simulations based in 30 yrs historical data to priciously predict risk-return tradeoff and price flactuations of stocks in the portfolio.

## Questions and Data : 
* What is the source and timeframe of data?
* Why benchmark is important? 
* Does larger number of stimulations give better idea to forcast?
* Can Users construct their own portfolio?
* Does portfolio optimization means neutral stragegy?

## Modeling and calculations : 
##  A. Monte-Carlo Simualtion: 
### We designed the project to fulfil user desire to construct protfolio. User can input any stock index of listed companies in the input panel, opt out timeframce (by default it uses 30years) and number of simulations. Once user completed inputs, two seperate Monte-Carlo simulations will run, one for stocks portfolio and other for benckmark. The simulations will allows to compare how user-selected portfolio perform with the benchmark over time. 

## B. Portfolio Optimization: 
![](https://raw.githubusercontent.com/blueprint99/Fintech_Bcamp_Project1/MishraSubash-patch-1/images/portfolio.png)

### In this section, we code to find out the best perfromaing portfolio among 5000 portfolios based on the highest Sharpe Ratio. The highest Sharpe ratio means the highest expected return for desired level of risk. Our code would able to locate and return the investment weight embeded in that best performancing portfolio which means the portfolio which yeids greatest sharpe-ratio among 5000 possibles outcomes. We call it as the most possible optimized portfolio. 

## Data Visualization : 
![](https://raw.githubusercontent.com/blueprint99/Fintech_Bcamp_Project1/MishraSubash-patch-1/images/weight%20allocation.png)
### This project comprises several well simplified and good looking graphs. Graphs includes scatter plot, line charts, boxplot, piechart and many more. We understand the fact that visualizations make complex data easier to understand and makes easier to detect patters, trend, and outliers in the groups of data. 

## Summary and Conclusion : 
### The Monte-Carlo simulations is very useful tool to model the probability of different outcomes. Here, in the above project our model was successful analyse the risk-return tradeoff betweens stocks and gives us clear idea to forcaste future market prices. Moreover, the Portfolio optimization model allows user to guide for a selection of best performing financial assets. The model we develped helps user to select the best portfolio (asset distribution), out of the set of all portfolios being considered, according to the highest sharpe ratio. Both Monte-Carlo simulation and Portfolio Optimization plays a considerable role within a strategic planning to predict the furure stocks as well to get best performing portfolio so that investors possibly beat the market. 

  
