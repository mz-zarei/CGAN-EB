# CGAN-EB: A Non-parametric Empirical Bayes Method for Crash Hotspot Identification Using Conditional Generative Adversarial Networks
link to paper with simulated crash data: https://arxiv.org/abs/2112.06925
linkto paper with real-world crash data: https://arxiv.org/abs/2112.10588


A new non-parametric empirical Bayes approach called CGAN-EB is proposed for approximating empirical Bayes (EB) estimates in traffic locations (e.g., road segments) which benefits from the modeling advantages of deep neural networks, and its performance is compared in a simulation study with the traditional approach based on negative binomial model (NB-EB). The NB-EB uses negative binomial model in order to model the crash frequency data and is the most common approach in practice. To model the crash frequency data in the proposed CGAN-EB, conditional generative adversarial network is used, which is a powerful deep neural network based method that can model any types of distributions. 

A number of simulation experiments are designed and conducted to evaluate the CGAN-EB performance in different conditions and compare it with the NB-EB. The results show that CGAN-EB performs as well as NB-EB when conditions favor the NB-EB model (i.e. data conform to the assumptions of the NB model) and outperforms NB-EB in experiments reflecting conditions frequently encountered in practice, specifically low sample means, and when crash frequency does not follow a log-linear relationship with covariates.

The proposed methodology is also applied to a real-world data set collected for road segments from 2012 to 2017 in Washington State, USA. The performance of CGAN-EB in terms of model fit, predictive performance and network screening outcomes is compared with the conventional approach (NB-EB) as a benchmark. The results indicate that the proposed CGAN-EB approach outperforms NB-EB in terms of prediction power and hotspot identification tests.
