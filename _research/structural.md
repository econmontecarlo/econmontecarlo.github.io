---
title: "Application of SMC methods to structural models in economics and finance"
layout: single-portfolio
collection: research
order_number: 30
---

The following are some projects under this workstream. 

## Bayesian estimation of long-run risk models using sequential Monte Carlo
Andras Fulop, Jeremy Heng, Junye Li and Hening Liu

>We propose a likelihood-based Bayesian method that exploits up-to-date sequential Monte Carlo methods to efficiently estimate long-run risk models in which the conditional variance of consumption growth follows either an autoregressive (AR) process or an autoregressive gamma (ARG) process. We use the U.S. quarterly consumption and asset returns data from the postwar period to implement estimation. Our findings are: (1) informative priors on the preference parameters can help to improve model performance; (2) expected consumption growth has a very persistent component, whereas consumption volatility is less persistent; (3) while the ARG-based model performs better than the AR-based one statistically, the latter could fit asset returns better; and (4) the solution method matters more for estimation in the AR-based model than in the ARG-based model.

[Article](https://doi.org/10.1016/j.jeconom.2020.12.008){: .btn--research}

## Estimating and Testing Long-Run Risk Models: International Evidence
Andras Fulop, Junye Li, Hening Liu and Cheng Yan

>We estimate and test long-run risk models using international macroeconomic and financial data. The benchmark model features a representative agent who has recursive preferences with a time preference shock, a persistent component in expected consumption growth, and stochastic volatility in fundamentals characterized by an autoregressive Gamma process. We construct a comprehensive dataset with quarterly frequency in the post-war period for ten developed countries and employ an efficient likelihood-based Bayesian method that exploits up-to-date sequential Monte Carlo methods to make full econometric inference. Our estimation provides international evidence in support of long-run risks, time-varying preference shocks, and countercyclicality of the stochastic discount factor.

[Preprint](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3857366){: .btn--research}

## Bayesian estimation of non-linear dynamic stochastic general equilibrium models
Andras Fulop, Jeremy Heng and Junye Li 

>In the past decade, Bayesian approaches have become dominant in the estimation of DSGE models in macroeconomics (see e.g. [Herbst and Schorfheide (2015)](https://web.sas.upenn.edu/schorf/companion-web-site-bayesian-estimation-of-dsge-models/) for a textbook treatment). Such models can easily have dozens of state variables, hence most existing work still resort to linearized models where solving the model boils down to a set of linear equations and the likelihood is available in closed form through Kalman filtering techniques, making Bayesian inference straightforward. The few papers in the literature estimating non-linear models (e.g. [Gust et al. (2018)](https://www.aeaweb.org/articles?id=10.1257/aer.20121437)) typically still need to fix some parameters and use a huge number of particles in order to stabilize the algorithm due to the use of inefficient proposals within the SMC algorithms used to estimate the likelihood. In this project, we explore the use of recent advances on optimal proposal generation [Heng et al. (2020)](https://doi.org/10.1214/19-AOS1914) to produce efficient estimates of the likelihood, opening the way to full-fledged Bayesian estimation of richer non-linear models. 

## Percentage Fees in Thin Markets: An Empirical Perspective 
Andras Niedermayer

>Percentage fees are widely used by intermediaries such as auction houses, headhunters, and real-estate brokers. The simplicity of such fees is surprising given the elaborate forms of price discrimination observed in many markets. This project seeks to answer the question whether such simple fees can be approximately optimal for an example of intermediaries: real-estate brokers. For this purpose, we estimate the parameters of a structural industrial organization model. Due to the complexity of the model, we use Bayesian estimation implemented through Monte Carlo simulation. We then want to use these estimates to construct counterfactuals, such as how well percentage fees compare to non-linear fees and the effect of a regulation of real-estate brokerage fees.

<!-- [Preprint](http://andras.niedermayer.ch/wp-content/uploads/2017/12/LNempirics-2017-12-09-main.pdf){: .btn--research} -->

## Detecting Collusion in Auctions 
Andras Niedermayer

>A major difficulty of detecting collusion in auctions is that estimation techniques usually require the knowledge of the members of the collusive bidding ring or at least have bidders who can be excluded from being suspected as members of the bidding ring ([Marmer and Niedermayer (mimeo)]() and [Marmer, Shneyerov and Kaplan (2017)](https://ideas.repec.org/p/ubc/pmicro/vadim_marmer-2016-3.html)). Running the estimation for all combinations of potential bidding ring members has the drawback that the number of combinations increases exponentially with the number of bidders. A Bayesian estimation method using Monte Carlo simulations solves this problem since it attributes a higher posterior probability to combinations that are more likely given the data.




