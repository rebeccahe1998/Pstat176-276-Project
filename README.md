# Pstat176-276-Project

Write a module AmerOption.py (you can use any platform other than python that you prefer)
and an analysis file. Our goal is to use Monte Carlo method and estimate the price of an American put option. In particular, we want to analyse if the estimation can benefit from implementation of the control variates method.


Stock prices are modeled as a geometric Brownian motion:
St = S0 * e ^(Rt) where Rt =  mu*t+sigma*Bt
Interpretation:
Rt is log return on [0,t]
mu is expected annual return
sigma is anual volatility
Bt is standard Brownian motion
