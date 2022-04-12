# VIX futures term-struct trading strategy WQU690 Capstone - Experiment 1

We will use VX futures term-structure historical data (from 1/3/2016 to 8/4/2022), SPX/IXIC convergence/divergence to predict next IXIC movement.

# 1.1. Steps
1.   Download VIX futures term-structure historical data (CBOE)
2.   Download S&P500 index (SPX) and NASDAQ100 composite index (IXIC) historical data (Yahoo Finance)
3.   Compute technical indicators values for VIX, Contago, SPX/IXIC convergence/divergence
4.   Compute trading signals (target values -1 (sell), 0(no action), 1(buy)) for our learning process based on a predetermined risk:return ratio
5.   Use the computed values as features to train our model
6.   Crossvalidation, Performance report, Backtesting
7.   Deploy the model and test with real-time data