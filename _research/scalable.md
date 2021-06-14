---
title: "Development of scalable SMC methodology for large dimensional problems"
layout: single-portfolio
collection: research
order_number: 40
---

The following are some projects under this workstream. 

## Diffusion Schrödinger Bridge with Applications to Score-Based Generative Modeling
Valentin De Bortoli, James Thornton, Jeremy Heng and Arnaud Doucet

>Progressively applying Gaussian noise transforms complex data distributions to approximately Gaussian. Reversing this dynamic defines a generative model. When the forward noising process is given by a Stochastic Differential Equation (SDE), [Song et al. (2021)](https://arxiv.org/abs/2011.13456) demonstrate how the time inhomogeneous drift of the associated reverse-time SDE may be estimated using score-matching. A limitation of this approach is that the forward-time SDE must be run for a sufficiently long time for the final distribution to be approximately Gaussian. In contrast, solving the Schrödinger Bridge problem (SB), i.e. an entropy-regularized optimal transport problem on path spaces, yields diffusions which generate samples from the data distribution in finite time. We present Diffusion SB (DSB), an original approximation of the Iterative Proportional Fitting (IPF) procedure to solve the SB problem, and provide theoretical analysis along with generative modeling experiments. The first DSB iteration recovers the methodology proposed by [Song et al. (2021)](https://arxiv.org/abs/2011.13456), with the flexibility of using shorter time intervals, as subsequent DSB iterations reduce the discrepancy between the final-time marginal of the forward (resp. backward) SDE with respect to the prior (resp. data) distribution. Beyond generative modeling, DSB offers a widely applicable computational optimal transport tool as the continuous state-space analogue of the popular Sinkhorn algorithm ([Cuturi, (2013)](https://papers.nips.cc/paper/2013/hash/af21d0c97db2e27e13572cbf59eb343d-Abstract.html)).

[arXiv Preprint](https://arxiv.org/abs/2105.04912){: .btn--research}

## On Unbiased Score Estimation for Partially Observed Diffusions
Jeremy Heng, Jeremie Houssineau and Ajay Jasra

>We consider the problem of statistical inference for a class of partially-observed diffusion processes, with discretely-observed data and finite-dimensional parameters. We construct unbiased estimators of the score function, i.e. the gradient of the log-likelihood function with respect to parameters, with no time-discretization bias. These estimators can be straightforwardly employed within stochastic gradient methods to perform maximum likelihood estimation or Bayesian inference. As our proposed methodology only requires access to a time-discretization scheme such as the Euler-Maruyama method, it is applicable to a wide class of diffusion processes and observation models. Our approach is based on a representation of the score as a smoothing expectation using Girsanov theorem, and a novel adaptation of the randomization schemes developed in [Mcleish (2011)](https://www.degruyter.com/document/doi/10.1515/mcma.2011.013/html), [Rhee and Glynn (2015)](https://doi.org/10.1287/opre.2015.1404), [Jacob et al. (2020a)](https://doi.org/10.1080/01621459.2018.1548856). This allows one to remove the time-discretization bias and burn-in bias when computing smoothing expectations using the conditional particle filter of [Andrieu et al. (2010)](https://doi.org/10.1111/j.1467-9868.2009.00736.x). Central to our approach is the development of new couplings of multiple conditional particle filters. We prove under assumptions that our estimators are unbiased and have finite variance. The methodology is illustrated on several challenging applications from population ecology and neuroscience.

[arXiv Preprint](https://arxiv.org/abs/2105.04912){: .btn--research}
[GitHub Repo](https://github.com/jeremyhengjm/UnbiasedScore){: .btn--research}

## Sequential Monte Carlo algorithms for agent-based models of disease transmission
Nianqiao Ju, Jeremy Heng and Pierre E. Jacob

>Agent-based models of disease transmission involve stochastic rules that specify how a number of individuals would infect one another, recover or be removed from the population. Common yet stringent assumptions stipulate interchangeability of agents and that all pairwise contact are equally likely. Under these assumptions, the population can be summarized by counting the number of susceptible and infected individuals, which greatly facilitates statistical inference. We consider the task of inference without such simplifying assumptions, in which case, the population cannot be summarized by low-dimensional counts. We design improved particle filters, where each particle corresponds to a specific configuration of the population of agents, that take either the next or all future observations into account when proposing population configurations. Using simulated data sets, we illustrate that orders of magnitude improvements are possible over bootstrap particle filters. We also provide theoretical support for the approximations employed to make the algorithms practical.

[arXiv Preprint](https://arxiv.org/abs/2101.12156){: .btn--research}
[GitHub Repo](https://github.com/nianqiaoju/agents){: .btn--research}

## A simple Markov chain for independent Bernoulli variables conditioned on their sum
Jeremy Heng, Pierre E. Jacob, Nianqiao Ju

> We consider a vector of $N$ independent binary variables, each with a different probability of success. The distribution of the vector conditional on its sum is known as the conditional Bernoulli distribution. Assuming that $N$ goes to infinity and that the sum is proportional to $N$, exact sampling costs order $N^2$, while a simple Markov chain Monte Carlo algorithm using 'swaps' has constant cost per iteration. We provide conditions under which this Markov chain converges in order $N\log N$ iterations. Our proof relies on couplings and an auxiliary Markov chain defined on a partition of the space into favorable and unfavorable pairs.

[arXiv Preprint](https://arxiv.org/abs/2012.03103){: .btn--research}

## Designing efficient SMC samplers based on Schr&ouml;dinger bridges. 
Espen Berton, Arnaud Doucet, Jeremy Heng and Pierre Jacob

> The goal of constructing efficient samplers can be reduced to designing dynamics that move samples from an initial distribution to a target distribution. Most state-of-the-art approaches are based on MCMC methods that require many iterations if the initial and target distributions are distant. In this project, we exploit ideas from optimal transport and stochastic processes to improve upon existing MCMC algorithms. Our approach is based on the Schr&ouml;dinger bridge problem that was first studied by Erwin Schr&ouml;dinger in 1931 because of its connections to quantum mechanics. Although its theoretical properties are now well-understood (see [Leonard (2014)](http://www.aimsciences.org/article/doi/10.3934/dcds.2014.34.1533) for a thorough review), an efficient numerical implementation is challenging in high dimensional continuous spaces (see [Reich (2019)](https://doi.org/10.1017/S0962492919000011) for a recent review). In this project, we build upon recent work in [Heng et al. (2020)](https://doi.org/10.1214/19-AOS1914) and show that such numerical challenges can be overcome. This allows us to develop novel SMC samplers that can overperform state-of-the-art methods at a fixed computational complexity.

[arXiv Preprint](https://arxiv.org/abs/1912.13170){: .btn--research}

## An invitation to sequential Monte Carlo samplers
Chenguang Dai, Jeremy Heng, Pierre E. Jacob and Nick Whiteley

>Sequential Monte Carlo samplers provide consistent approximations of sequences of probability distributions and of their normalizing constants, via particles obtained with a combination of importance weights and Markov transitions. This article presents this class of methods and a number of recent advances, with the goal of helping statisticians assess the applicability and usefulness of these methods for their purposes. Our presentation emphasizes the role of bridging distributions for computational and statistical purposes. Numerical experiments are provided on simple settings such as multivariate Normals, logistic regression and a basic susceptible-infected-recovered model, illustrating the impact of the dimension, the ability to perform inference sequentially and the estimation of normalizing constants.

[arXiv Preprint](https://arxiv.org/abs/2007.11936){: .btn--research}
[GitHub Repo](https://github.com/pierrejacob/smcsamplers){: .btn--research}
