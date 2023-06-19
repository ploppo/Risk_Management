# Risk_Management
Homework for the class of Risk Management 2021/2022

## The first homework is related to hedging currency price exchange.

The homework is inspired from the business case Hedging Currency Risk at AIFS of Harvard Business School.

The tool created is a graphical interface to understand what happens in the case of different situation of hedging. This takes into account the percentage of hedging, the fraction of option on the total amount and the number of students that will take part into the program.
 

## The second homework is a simulation of the CVaR.

The file try_CVaR.mlx is assessing how many scenarios are needed to have a decent approximation of the CVar for a normal distribution.
The file min_CVaR use the result found in try_CVaR. The goal of this file is to find the minimal CVaR for a portfolio of four different stock company using real historical data and with a constraint on the mean of the portfolio. So creating an optimization problem with constraints is then possible to find the optimal number of stocks needed for each company. The result is then compared with the Matlab native function and also against scenarios out of sample.

