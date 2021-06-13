---
title: "Application of SMC methods to reduced form models in economics and finance"
layout: single-portfolio
collection: research
order_number: 20
---

The following are some projects under this workstream. 

## Estimation of Option Pricing Models Using large Option Panels 
Andras Fulop and Jeroen Rombouts

>The estimation of modern parametric option pricing models can be cast as a non-linear and non-Gaussian filtering problem, due to the non-linear option pricing function, conditional non-normality and stochastic volatility (see e.g. [Fulop and Li (2019)](https://doi.org/10.1016/j.jeconom.2018.11.014)). Solving the option pricing function can be computationally quite demanding in up-to-date models that can describe the observed price dynamics well. Hence to make the estimation computationally feasible, most existing studies only use a limited time-series and cross-sectional option samples, throwing away information. In this research stream, we propose to develop methods that allow one to use the full option price sample through computationally efficient approximations of the measurement density. 

## Pricing of Idiosyncratic Equity and Variance Risks 
Elise Gourier and Alexander Kontoghiorghes 

>Standard asset pricing theories predict that idiosyncratic risks can be diversified, and should therefore not be priced. However, explanations have been provided in the literature to justify why they may, in fact, be priced. These explanations are based on the presence of market imperfections or investors' preferences that would prevent them from holding a perfectly diversified portfolio. This project examines the pricing of equity and variance risks using an integrated panel of stocks and option data. We estimate a parametric jump-diffusion model of stock dynamics, which enables us to decompose equity and variance risk premia into systematic and idiosyncratic components, each of which can be further decomposed into parts stemming from diffusion and jump risks. The model is flexible but yet tractable: indeed, it allows valuing options in semi closed-form, up to the resolution of ODEs. The estimation is performed using a particle filter, applied to market returns, option prices and realized variances from 1996 to 2016. Preliminary results indicate that investors not only require compensation for the systematic movements in returns and variance, but also for non hedgeable idiosyncratic risks. For the stocks of the S&P 100 index, these risks account for more than half, on average, of the equity and variance risk premia. We uncover strong differences in the prices of idiosyncratic risks depending on the sector a given stock belongs to. In particular, idiosyncratic risks are highly priced in the Energy, Financial and Consumer Discretionary sectors. We link these findings to the market frictions that hinder the efficiency of these sectors. Other sectors are found to be appealing alternatives for investors who are not willing to be exposed to risks they cannot diversify.

[Preprint](https://www.econstor.eu/handle/10419/175218){: .btn--research}

## Sparse Change-point VAR models 
Arnaud Dufays, Zhuo Li, Jeroen Rombouts and Yong Song

>It is well known that economic and ﬁnancial time series observed over a long period are subject to structural breaks the dates of which are unknown. As a consequence, structural break or change-point (CP) time series models have been developed to identify substantial but infrequent parameter changes. The modelling of multivariate time series makes the problem of structural breaks more complex, since for example the break dates potentially diﬀer among the time series. Direct extensions from the univariate to the multivariate structural break model have been implemented by [Pettenuzzo and Timmermann (2011)](https://doi.org/10.1016/j.jeconom.2011.02.019), though the lack of sparsity makes it diﬃcult to estimate the models in practice given the large number of parameters even for standard low dimensional models with few lags. This project proposes a sparse change-point vector autoregressive model, or sparse CP-VAR, to model multivariate time series subject to multiple unknown structural breaks. It relaxes the assumption that all parameters need to change when detecting automatically for structural breaks. This is achieved by shrinking irrelevant break-parameters towards zero in our estimation procedure which is based on a sampling scheme tailored to CP models.

[Preprint](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3461692){: .btn--research}

## Systemic Credit Risk in Microcredit Markets: A Copula Approach 
Andréas Heinen, Malika Hamadi and Jérémie Juste

>We introduce a measure of systemic credit risk in microcredit markets by estimating the determinants of the dependence of the portfolio quality of microfinance institutions (MFIs) in a given country. We introduce a panel model of equidependent Gaussian copulas based on an empirical density estimation for the marginals. This new methodology allows us to control for country effects. The methodology is based on the idea that a higher level of dependence among MFIs in a given country is an indicator of potential fragility of the sector. Given the highly non-linear nature of the model, we will rely on SMC methods for its estimation. We will analyze the effect of measures of competition, market penetration, commercialization and fast growth of the sector, as well as the level of interest rates charged by MFIs in a country on the systemic credit risk in the microfinance sector. With this measure of systemic risk, we further compute the probability that a proportion of at least 20% of MFIs in a country are experiencing serious repayment problems


