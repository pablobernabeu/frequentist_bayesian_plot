# frequentist_bayesian_plot

R function for presenting frequentist and Bayesian estimates in the same plot. To this end, the frequentist results are merged into a plot from `brms::mcmc_plot()`. 

Three arguments are required for this function: 

1. a summary of an 'lmerTest' model,
2. confidence intervals from `lme4::confint.merMod()`,
3. a plot from `brms::mcmc_plot()`.

The function is equipped to accept the slight differences between the names of the predictors in the frequentist results and in the Bayesian results.

https://pablobernabeu.github.io/2022/why-can-t-we-be-friends-plotting-frequentist-lmertest-and-bayesian-brms-mixed-effects-models
