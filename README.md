# Pstat176-276-Project

Write a module AmerOption.py (you can use any platform other than python that you prefer)
and an analysis file. Our goal is to use Monte Carlo method and estimate the price of an American put option. In particular, we want to analyse if the estimation can benefit from implementation of the control variates method.


Stock prices are modeled as a geometric Brownian motion:
St = S0 * e ^ ((mu-0.5 * sigma^2)t + sigma *Wt)

Interpretation:

mu is expected annual return

sigma is anual volatility

Wt is THE Brownian motion PATH that includes effects of all random shocks since time 0 
