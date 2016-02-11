# Programming-for-Financial-Engineering

This assignment has four parts:

(a) Write a Python script to download asset data for the Russell 1000 index over the last two years, using the Yahoo finance kit. You may adapt the script I provided. As a hint, write your script so that it writes all asset information to a text file. 

(b)  Compute the day-over-day asset returns for all these stocks. Again you may write this information to a text file.

(c)  Suppose you are given a set S of ten assets. Let x denote the returns for the assets in the set S, and let y denote the returns for all assets. 
Your task is to carry out an ordinary linear regression (OLS) used to explain y as a function of x of the form y = c x (thus, no intercept). Note that the coefficients vector c will be 10-dimensional.

(d)  The final task is to iterate (c) over many choices for the set S, with the goal of finding the best such set, defined by the largest combined R^2 value. I will let you use your imagination to carry out this (partial) enumeration. It should not run for more than a couple of hours. 
