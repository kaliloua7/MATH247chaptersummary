
#### Plus Four confidence interval

is a method for computing confidence intervals for a process from a sample proportion. We add 4 more observation to the total number of observation among which 2 are successes and 2 are failures. The plus four method has a high coverage-rate compared to other methods.

$\tilde{p}\pm z^{*} \sqrt{\tilde{p}(1-\tilde{p}/n+4)}$

#### Parameter and Statistic:

A parameter is a metric that describes the whole population, we denote the population mean and proportion by $\mu$ and $\pi$. A statistic is the same metric but calculated for sample, we denote the sample mean and proportion by $\bar{x}$ and $\hat{p}$.

#### Biased and Unbiased samples

The statistic values of a biased sample are systematically different from the parameter values of the population. An unbiased sample's statistic values are much more closer to the parameter values.


#### Simple random sample

Is a technique that gives every observational entities in the population an equal chance of being sampled. 

#### Sampling from a finite population

When sampling from a finite population without replacement, trials are no longer considered independent. The probability of successive events is not constant throughout events anymore. 

The central limit theorem also applies when sampling from large finite population with a large sampling size. It states that the distribution of sample proportions will be modeled by a normal distribution with mean=$\pi$. The sample is considered large enough if there are at least 10 successes and 10 failures, the population is considered large enough if it's more than 20 times the sample size.

Note the two desirable properties of sample means when we using random samples from a
large population:
    • The distribution of sample means centers at the population mean (so the sampling method is
unbiased).
    • The distribution of sample means has less sample to sample variability when we increase the sample
size (producing increased precision).

Notice that sample proportion variability is dependent on the sample size. Large samples have less variability than small ones.

#### Non-sampling errors:

Are errors associated with sources of bias after the sample has been selected. It's anything that suggests  to the participants that a certain answer is preferred over the others.

#### Hypergeometric Random Variable

Are random variable used when:
    1. trials are no longer independent
    2. there are two distinct types of objects in the population.
    
An hypergeometric random variable is similar to a binomial rand var in that both variables require that there are 2 types of distinct object in the population. An hypergeometric var is used when the population is finite and trials are no longer considered independent of each other.

