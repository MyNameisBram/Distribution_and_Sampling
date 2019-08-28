# Distribution_and_Sampling

## Statistical Distributions
We're going to start by reviewing what we've learned about Uniform, Normal and Binomial distributions and look at real world use cases for problem solving using statistical distributions. We then introduce the Negative Binomial distribution and the kinds of questions it can be used to answer. Next up, we look at the Geometric distribution and how it can be used to calculate the probability distribution of repeated, independent events.

After some practice working with Negative Binomial and Geometric distributions, we then introduce the Poisson distribution and how it can be used to predict things like the number of times a given event might happen within a time period.

We finish up the distributions section by introducing the Exponential distribution. In some ways it can be thought of as the inverse of a Poisson distribution, allowing us to answer questions about the amount of time it might take before a given event occurs.

## Sampling
Next, we provide an introduction to the idea of sampling - selecting a subset of a population to survey. Then we introduce the central limit theorem and how it can be used for parameter estimation. We then start to introduce some statistics related to sampling, explaining and showing how to calculuate the standard error.

From there, we then go on to introduce and calculate confidence intervals, and see how we can use T-distributions to calculate confidence intervals when we don't know the standard deviation of the population.

## Summary
Distributions and sampling - Some of the key takeaways include:
* There are two types of distributions - continuous, where (subject to measurement and/or storage precision) there are effectively an infinite number of possible values, and discrete, where there are a distinct, non-infinite number of options. For example, a persons height is continuous - assuming a suitably precise tape measure - whereas the number of bedrooms in a house is discrete
* One type of discrete distribution deals with a series of boolean events or trials - often called Bernoulli Trials
* With a Uniform distribution, every possible outcome is equally likely. Both continuous and discrete sets can have a Uniform distribution
* A Normal distribution is the classic "bell curve" wiuth 68% of the probability mass within 1 sd of the mean, 95% within 2 sd's and 99.7% within 3 sd's
* The Binomial distribution is the discrete version of a normal distribution
* Negative Binomial trials are used to answer questions like "how many times can I flip a coin until I fail (get a tails) 3 times in total?"
* The Negative binomial distribution reflects the probability distribution for a negative binomial trial
* A Geometric distribution is a special case of a Negative Binomial distribution where the cumulative number of failures is fixed as 1. So "how many times can I flip a coin before I get one tails?"
* The Poisson distribution can be used to display the likelihood of a given number of successes over a given time period - e.g. "how likely is it that 25 people walk into a store in a given hour?"
* The Exponential distribution can be used to describe the probability distribution of the amount of time it may take before a given event occurs
* The Central Limit Theorem states that often, independent random variables summed together will cnverge to a normal distribution as the number of variables increases
* Using Central Limit Theorem, we can work with non-normally distributed data sets as if they were normally distributed
* The Standard Error is a measure of spread - it is the standard deviation of samples from the sample mean
* A Confidence Level is used to describe how confident we are that a given parameter is within a given range. E.g. "there's an 80% chance (confidence level of 80%) the person is between 5'5 and 6'2"
* That range is called the Confidence Interval
* The z-critical value is the number of standard deviations you'd have to go from the mean of the normal distribution to capture the proportion of the data associated with the desired confidence level.
* If you don't know the standard deviation for a population, you also need to use T-distributions
