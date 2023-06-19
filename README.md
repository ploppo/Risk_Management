# Risk_Management
Homework for the class of Risk Management 2021/2022

This homework id done on a notebook of Matlab. 
The file try_CVar is assesting how many scenaries are needed to have a decent approximation of the CVar for a normal distribution.
The file min_CVar use the result found in try_CVar. The goal of this file is to find the minimal CVar, for a portfolio of four different stock company using real historical data and with a constraint on the mean of the portfolio. So creating an optimization problem with constraints is then possible to finde the optimal number of stocks needed for each company. The result is then compared with the Matlab native function and also against scenaries out of sample. 

