# Statistics-and-probability

### Codes for distributions, probabilities and key machine learning concepts

##### [Functions for statistical inference](https://github.com/Vitomir84/Statistics-and-probability/blob/master/Hypothesis_testing.ipynb)

Here you can find the several functions for creating probability density functions, cumulative distributions functions, calculating the percentiles,
as well as p - probability that we get some results under assumption that hypothesis (usually called zero hypothesis) is true. Here you can see the 
very good examples for understanding basic statistical concepts. 

##### [Implementation of hypothesis testing, distributions, plotting and other](https://github.com/Vitomir84/Statistics-and-probability/blob/master/Distributions.ipynb)

Here you can find the different plots of different distribution types. We plot first Uniform distribution, then Normal and Gamma distribution.
For Normal and Gamma distribution we variate the key parameters (mean and standard deviation for normal, alpha and beta for Gamma) in order
to get more familiar with distribution characheristics. 

##### [Box-Cox transformation of variable to a normal distributiuon](https://github.com/Vitomir84/Statistics-and-probability/blob/master/Box%20Cox%20transformation.ipynb)

Here we make the illustration how we can use the Box-Cox transformation to transform some data distribution to normal, by searcing and finding the 
adequate parameter lambda.

A Box Cox transformation is a transformation of non-normal dependent variables into a normal shape. Box and Cox proposed a parametric power transformation technique defined by a single parameter λ, aimed at reducing anomalies in the data and ensuring that the usual assumptions for a linear model hold. This transformation results from modifying the family of power transformations defined by Tukey to account for the discontinuity at λ = 0.

##### [Explanation of gradient and programming of gradient descent from the scratch and plotting for several epochs](https://github.com/Vitomir84/Statistics-and-probability/blob/master/Gradient%20and%20programming%20gradient%20descent.ipynb)

This code is essence of machine learning. Understending how gradient descent works is the most fundamental thing. It is easier to understand it
how it works on linear regression, and then it will be no pain to understand how it works in Deep Learning, Reinforcment learing function approximation
and how more advanced optimisers works (e.g. famous Adam).

##### [Creating ROC curve from the scratch](https://github.com/Vitomir84/Statistics-and-probability/blob/master/Creating%20ROC%20curve.ipynb) 

Receiver Operating Characteristics (ROC) curve gives us the estimation for model performance based on comparing true positive and false positive rate for various tresholds of our binary target variable.

Good excersice for understanding the sensitivity, recall and f1 as harmonic mean of the first to metrics. According to problem, carefull selection
of adequate metric can be a crucial thing. 

##### [Programming the VIF - variance inflation factor for tackling multicolinearity](https://github.com/Vitomir84/Statistics-and-probability/blob/master/VIF.ipynb)

This is simple method for checking multicolinearity in predictors. All predictors are interchangebly taken as a predictor, while looped predictor is a target, then we take metrics 
$'\frac{1}{1-R^2}'$ 
where 
$'R^2'$ 
is coefficient of determination.


##### [Plotting different types of distributions and examples of distributions in relation to Tukey's lambda](https://github.com/Vitomir84/Statistics-and-probability/blob/master/VIF.ipynb)

The Tukey Lambda PPCC plot, with shape parameter λ, is particularly useful for symmetric distributions. It indicates whether a distribution is short or long tailed and it can further indicate several common distributions. Specifically,

λ = -1: distribution is approximately Cauchy

λ = 0: distribution is exactly logistic

λ = 0.14: distribution is approximately normal

λ = 0.5: distribution is U-shaped

λ = 1: distribution is exactly uniform

##### [Monte Carlo simulation](https://github.com/Vitomir84/Statistics-and-probability/blob/master/MonteCarlo_sampling.ipynb)

Here we use the simplest example of Monte Carlo simulation in the task when we want to know the most probable sum of rolling 12 six sided dices. 

##### [Gibbs sampling](https://github.com/Vitomir84/Statistics-and-probability/blob/master/Gibbs_Sampling.ipynb)

We use Gibbs sampling when we are unable to sample directly from multivariate distribution consisted of two or more univariate distributions, but we can do sampling from various (in this case two) conditional distributions. The point of Gibbs sampling is that given a multivariate distribution it is simpler to sample from a conditional distribution than to marginalize by integrating over a joint distribution. Code is from blog: https://towardsdatascience.com/gibbs-sampling-8e4844560ae5 but with some additions and clarifications.
