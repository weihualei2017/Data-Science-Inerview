# Data-Science-Inerview

## Hypothesis testing

### Steps
1. 

## Clustering Algorithms
### K-Means
The K-means algorithm clusers data by trying to separate samples in k groups which minimize within-cluster sum-of-squares (variance).

\sum_{i=0}^{n}\min_{\mu_j \in C}(||x_i - \mu_j||^2)

## What are the assumpations for the linear regression?

1. Linearity: the mean of the variate (dependent variable) is a linear combination of the covariates(independent variables)
2. No or little multicollinearity: 
3. Constant variance: the variance of the dependent variable does not depend on the mean (use robust regression or specify the variance as a function of the mean)
4. The error follows a gaussion distribution, otherwise a generalized linear model is needed (The dependent variable is count : Poisson regression etc)
5. The erros are uncrorrelated: we assumed the errors of the dependent variables are uncorrelated. (mutivariate regression)


## SVM
### Advantages:
1. SVM works relatively well when there is a clear margin of separation between classes.
2. SVM is more effective in high dimensional spaces.
3. SVM is effective in cases where the number of dimensions is greater than the number of samples.
4. SVM is relatively memory efficient
### Disadvantages:
1. SVM algorithm is not suitable for large data sets.
2. SVM does not perform very well when the data set has more noise i.e. target classes are overlapping.
3. In cases where the number of features for each data point exceeds the number of training data samples, the SVM will underperform.
4. As the support vector classifier works by putting data points, above and below the classifying hyperplane there is no probabilistic explanation for the classification.
