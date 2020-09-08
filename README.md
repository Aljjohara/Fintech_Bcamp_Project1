 ## Monte-Carlo Simulation and Portfolio Optimization

## Prepared By: 
- Kavin Minchala
- Aljohara Aloudan
- Subash Mishra
- Victor Martinez
  
  # Project Outline 
## Summary: 
- This project has two seperate but interliked analysis of protfolio constructions. 
## A. Monte Carlo Simulation: 
- Monte Carlo simulation involves using random number generators to simulate random effects. Simulating a historical prices for many times allows us to measure the variation just as we would if we took many samples of a real event. In this project we are using 30 years historical data to analyze risk-return pattern based on the user's desired portfolio. 

## B. Portfolio Optimization: 
- Portfolio optimization is the method of selecting the best performing portfolio, out of the set of all portfolios being considered based on the amount of investment in each stock. Our project would select that portfolio which yeilds the highest sharpe ratio out of 5000 seperate portfolio meaning the highest expected return for desired level of risk.

## Purpose of Project: 
 * Running numerious simulation to analyze the underlying risk-retrun tradeoff of user desired stocks/portfolios. 
 
 * To get the optimum investment weight (Asset allocation) that has the highest sharpe ratio.
 
## Hypothesis: 
### It is possible to beat the market when allocating optimum weight in a stock portfolio. 

### The well diversified and properly allocated portfolio could possibly beat the market. 

## Data Source: 
### Yahoo Finance
-  We used Yahoo Finance as our primary data source to get Adj Close. 
- The adjusted close reflects stock dividens and stock splits which gives better idea of the overall value of stock and help making informed decision about trading stocks. 
### Alpaca
- We used Alpaca to get stock prices 

## Timeframe:
- In the first part of the project, we run numerious( user can opt any number of simulations) Monte-Carlo simulations using 30 years of historical data to predict risk-return tradeoff and price flactuations of stocks in the portfolio.

## Questions and Data : 
* What is the source and timeframe of data?
* Why benchmark is important? 
* Does larger number of stimulations give better idea to forcast?
* Can Users construct their own portfolio?
* Does portfolio optimization means neutral stragegy?

## Modeling and Calculations: 
##  A. Monte-Carlo Simualtion: 
- User can input any stock index of listed companies in the input panel, opt out timeframe (by default it uses 30years) and number of simulations. 
- Once user completed inputs, two seperate Monte-Carlo simulations will run, one for stocks portfolio and other for benckmark. 

## B. Portfolio Optimization: 
![](https://raw.githubusercontent.com/blueprint99/Fintech_Bcamp_Project1/MishraSubash-patch-1/images/portfolio.png)

- We used SciPy built-in library to find out the best perfromaing portfolio among 5000 portfolios based on the highest Sharpe Ratio. The highest Sharpe ratio means the highest expected return for desired level of risk. 
- We locate and return the investment weight embeded in the best performancing portfolio which means the portfolio with highest sharpe-ratio among 5000 possibilities. We call it as the most possible optimized portfolio. 


## Summary and Conclusion: 
- our model has succesfully analyzed the risk-return tradeoff between stocks and forecasted future market prices. 
- the Portfolio optimization model helps the user to select the best portfolio.
- Both Monte-Carlo simulation and Portfolio Optimization plays a considerable role within a strategic planning to predict the furure stocks as well as to get best performing portfolio so that investors can possibly beat the market. 

  
