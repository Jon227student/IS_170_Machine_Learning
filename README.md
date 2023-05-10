Principal Component Analysis (PCA)

Principal Component Analysis (PCA) is a technique used in data science to reduce the number of variables in a dataset while retaining the most important information. It does this by creating new variables, known as principal components, which are linear combinations of the original variables.

These principal components are ranked in order of importance based on the amount of variance they explain in the original data. The first principal component explains the most variance, followed by the second.

PCA is useful in data analysis because it can simplify complex datasets by reducing the number of variables needed to explain the variation in the data. This can make it easier to visualize and interpret the data, and can also improve the accuracy and efficiency of machine learning algorithms by reducing the dimensionality of the dataset.

In the HW file below I took a dataset pertaining to wind speeds and its assosiation with rain. I limited it down to its two most important Variables. The produced numbers showed the variability of the dataset based on these Variables. The Explained Variation per principal compnent was [0.31381248 0.17597993]. The first principal component explains 31.38% of the variation in the data, while the second principal component explains 17.60% of the variation. 
