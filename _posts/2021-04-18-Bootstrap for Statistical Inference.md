---
published: true
---
We live in the most data-driven era in history. The websites we scroll through, coffee shops we visit, even our voter registrations are bits of data that are being collected daily; however, none of these data sets are perfect. Typically, data analysis involves making informed estimations of population characteristics using a sample of the population of interest. Sometimes these sample sizes are very small relative to the population and with a high degree of variance. 

This article is a summary of my self-selected Senior Exercise in Theoretical Mathematics focusing on the classical background and modern applications of the Bootstrapping Algorithm. The full paper is available at [Bootstrapping for Statistical Inference](https://www.linkedin.com/in/alyssaraywilliams/detail/treasury/education:256028703/?entityUrn=urn%3Ali%3Afsd_profileTreasuryMedia%3A(ACoAABdluQwBnbuo1o62aarNsG0cKXLLQqvVGkI%2C1617934975822)&section=education%3A256028703&treasuryCount=1&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3B57ft9Hy6Qo28Qm3%2FsQi4qg%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_profile_view_base-treasury_thumbnail_cell). At the end of the paper you should be able to answer:

1. What is the Bootdtrapping Algorithm & when is it a useful technique for statistical inference?

2. What are the characteristics of a bootsample?

3. How does increasing the repetition of resampling relate to a more accurate estimation of a population parameter?

4. What are the appropriate applications of the bootstrapping algorithm for enabling statistical inference? 

## The Bootstrapping Algorithm 

Bootstrapping, as a method of statistical inference, is rising to influence because of recent growth in computational power. It is a representation of the gains that can be made through weaving together innovative software development and data analysis. 

  The bootstrap algorithm for estimating the population parameter θ:
  1. Randomly choose a sample X_1, X_2, ..., X_n from the population without replacement. 
  2. Select _B_ independent bootstrap samples X^1, X^2, ..., X^B of size _n_ randomly and with replacement from the empirical distribution function _F_. 
  3. Compute the bootstrap statistic for each bootstrap sample, 
  θ^b = g(X^b) b = 1, 2, ..., _B_ 
  4. Evaluate the bootstrap statistics using the desired method such as confidence intervals or a hypothesis test.
  
Note: The methods described in the paper can be expanded beyond one-dimensional data and to more precise confidence intervals and hypothesis tests.

## Application: Bootstrapping Backlink Volume Mean for SEO

THE CLIENT: Imagine you are the marketing director of an online factoring marketplace. You have researched information about ranking factors in Google and decided to pursue an aggressive link-building strategy to increase web traffic. You are interested in increasing the number of links pointing to your website from other domain names, also known as backlinks. To set reasonable and informed goals for your team you would like to learn how many backlinks your competitors currently average so you can try to exceed this baseline. 

THE PROBLEM: You only have about twelve true online factoring broker competitors with a large enough web presence to collect data. You gather the number of backlinks for these twelve competitors. Your sample has a mean value of 11, 194.42 with a standard deviation of 23, 002.81. 

THE SOLUTION: Since your sample size is small, only the twelve competitors, with a high amount of variability the bootstrap algorithm can be used to estimate the true mean number of backlinks an average factoring broker would have in their profile. We use a bootstrap procedure to estimate the mean number of competitor backlinks, using two different confidence interval methods. This volume can then be reported to the marketing director to strategize implementation. 

## Overview of Contents

- Section 1: Defines the bootstrapping algorithm in the context of the backlink mean application
- Section 2: Illustrates the iterative bootstrap procedure through estimating a mean. 
- Section 3: We use the ideal bootstrap estimate of the standard error of a statistic to demonstrate how bootstrapping is an innovative method for evaluating the accuracy of statistical estimates when the number of iterations is large. 
- Sections 4 and 5: We use a selection of 2016 Presidential Election polls and data from Factor Finders, LLC. to create bootstrap estimates of means and confidence intervals. 
- Section 6: Outlines a bootstrap hypothesis test. 

## Sources | Suggested Reading

1. Sheld Ross. _A First Course in Probability_. Macmillan Publishing Co., Inc., New York, NY, 1976. 
2. Roxy Peck and Jay L. Devore. _Statistics: The Exploration & Analysis of Data_. Brooks/Cole, Boston, Massachusetts, 2012. 
3. Bradley Efron and Robert J. Tibshirani. _An Introduction to the Bootstrap_. Chapman & Hall, New York, New York, 1993. 
4. Ann R. Cannon et. al. _STAT2:Building models for a world of data_. W.H. Freeman, New York, New York, 2013. 
5. John A. Rice. _Mathematical Statistics and Data Analysis_. Brooks/Cole, Cengage Learn ing, Belmont, California, 2007. 
7. A. C. Davison and D.V. Hinkley. _Bootstrap Methods and Their Application_. Cambridge University Press, New York, New York, 1997.
