# EDA-for-Traffic-Density-Dataset
## Lab Based Continuous Assessment for Machine Learning Subject, dated 23rd Feb 2024, Sem 6

## Relationship Between Economy and Traffic Density

Using a barplot, we analyzed the relationship between the economy and traffic density in the dataset. We observed that the traffic density drastically drops during recession periods. Surprisingly, it remains stable during both booming and stable economic periods.

## Clustering Labels vs. Traffic Density and Scatter Plot Analysis

Utilizing k-means clustering, we examined the labels versus traffic density and produced a scatter plot showcasing speed versus traffic density. We noticed significant overlapping for the three clusters due to the number of features for X. However, the scatter plot effectively illustrates the distribution of speed variables versus density, highlighting clear outliers.

## Pairplot Analysis

Using `pairplot`, we conducted various plotting tasks from the Seaborn library in one go. This analysis allowed us to visualize the correlation between individual features and traffic density. Furthermore, the correlation matrix provided insights into strong and weaker learners for XGBoost, which we employed for modeling purposes.
