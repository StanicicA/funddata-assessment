# Normal Distribution

Normal distribution is the default probability for many real-world scenarios. It represents a symmetric distribution where most of the observations cluster around the central peak called as mean of the distribution. A normal distribution can be thought of as a bell curve or Gaussian Distribution which typically has two parameters: mean and standard deviation (SD).

## Mean – The mean is the usual average. The sum of total points divided by the total number of points.

## Standard Deviation – Standard deviation tells us how “spread out” the data is. It is a measure of how far each observed value is from the mean.
Here are some of the properties of the normal distribution of the population:

>The points in the normal distribution are symmetric. The normal distribution can not be used to model skewed distributions.
>The mean, median, and mode of the normal distribution are equal.
>Half of the population is less than the mean and half is greater than the mean.
>The empirical rule of the normal distribution goes like the following: 68% of the observations fall within +/- 1 standard deviation from the mean, 95% of the observations fall within +/- 2 standard deviation from the mean and 99.7% of the observations fall within +/- 3 standard deviations from the mean.

Following is the formula for the Normal Distribution:
![image](https://user-images.githubusercontent.com/98254584/211112342-34258291-8db0-422f-9cd4-a7e6f56e4e6c.png)

An easily understood application for Calculus lies in statistics, in the forms of the normal or Gaussian distribution. The normal distribution or "bell curve" looks like this when plotted:
![Normal Distribution](![image](https://user-images.githubusercontent.com/98254584/211110543-84a4b9da-7373-4f91-8e1d-0ff14a74006c.png)

*To get the above plot, I've used the below code importing the following:

![code normal distribution](https://user-images.githubusercontent.com/98254584/211111064-08ad4b51-cd94-4663-9ff6-40f5d09c9a7b.jpg)

## Some of the basic Normal Distribution content:

**Probability Density Function**
The normal distribution density function simply accepts a data point along with a mean value and a standard deviation and throws a value which we call probability density. Here is the probability density function for normal distribution:

![image](https://user-images.githubusercontent.com/98254584/211111337-6947de8b-8a54-46d1-a058-8b72f1d3d3fe.png)

**Cumulative Distribution Function**
For many purposes we need to integrate the Probability Density Function to be able to quantify and characterize natural distributions, but, in spite of its great importance to the field of statistics, there is no analytical integral for the PDF — integration of the PDF is carried out numerically. The much-used Cumulative Distribution Function (CDF) is only ever an approximation based on carefully designed numerical methods.

**Percent point function**
ppf is the inverse of cdf and it is called the Percent point function. Given the mean of 1 and the standard deviation of 3, we can find the quantile a in 𝑃(𝑋<𝑎)=0.506 by using ppf.

**Interval between variables**
To find the probability of an interval between certain variables, you need to subtract cdf from another cdf.

**Multivariate Normal Distribution**
The multivariate normal distribution is often used to describe any set of correlated real-valued random variables.

+*Here is the summary of what we have learned in relation to Normal distribution*:

- Normal distribution is a symmetric probability distribution with equal number of observations on either half of the mean.

- The parameters representing the shape and probabilities of the normal distribution are mean and standard deviation

- Python Scipy stats module can be used to create a normal distribution with mean and standard deviation parameters using method norm.

- scipy.stats.norm gives us parameters such as loc and scale to specifies the standard deviation. It also has a variety of methods such as rvs, cdf, sf, ppf, interval, and isf

- Standard normal distribution is normal distribution with mean as 0 and standard deviation as 1.

- In normal distribution, 68% of observations lie within 1 standard deviation, 95% of observations lie within 2 standard deviations and 99.7% observations lie within 3 standard deviations from the mean.

## Resources:
```bash
* https://arachnoid.com/IPython/normal_distribution.html
* https://docs.sympy.org/dev/modules/stats.html#module-sympy.stats
* https://vitalflux.com/normal-distribution-explained-python-examples/
* https://www.askpython.com/python/normal-distribution
* https://towardsdatascience.com/exploring-normal-distribution-with-jupyter-notebook-3645ec2d83f8
* https://notebook.community/iRipVanWinkle/ml/Data%20Science%20UA%20-%20September%202017Lecture%2003%20-%20Basic%20Statistics/Overview_of_distributions
* https://integratedmlai.com/normal-distribution-an-introductory-guide-to-pdf-and-cdf/
* https://medium.com/analytics-vidhya/writing-github-readme-e593f278a796
* https://www.w3schools.com/python/numpy/numpy_random_normal.asp
* https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html
* https://www.investopedia.com/terms/n/normaldistribution.asp
* https://www.mathsisfun.com/data/standard-normal-distribution.html
```


