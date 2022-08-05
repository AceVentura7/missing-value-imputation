Missing values is one of the most common problems that you will come across when performing data analysis. Furthermore, machine learning models require that a dataset does not contain any missing values before they can be fitted to the data. Therefore, it is crucial that we learn how to properly handle them.

There are mainly two ways that we can deal with missing values in a dataset:

If there are only a few rows with missing values or if a column has an overwhelming number of missing values, we can simply drop them from the dataset without running into the risk of losing too much information.

An alternative approach to handling missing values is via imputation. Imputation is the process whereby the missing values in a dataset are replaced with some substituted values.

For the purpose of this tutorial, we will examine the process of imputation and more specifically, we will learn the difference between a univariate approach to imputing versus a multivariate approach to imputing.

Univariate imputation implies that we are only considering the values of a single column when performing imputation. Multivariate imputation, on the other hand, involves taking into account other features in the dataset when performing imputation.

The multivariate approach to imputing is generally preferred over the univariate approach as it is more robust and provides our model with a more accurate representation of the missing values in order to make better predictions.

In this tutorial, we will explore 3 different imputation techniques with reference to the Titanic dataset on Kaggle:

1. Simple imputer
2. Iterative imputer
3. KNN Imputer
