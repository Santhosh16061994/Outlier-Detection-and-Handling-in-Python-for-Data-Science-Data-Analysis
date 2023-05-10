# Outlier-Detection-and-Handling-in-Python-for-Data-Science-Data-Analysis

## Detecting outliers by boxplot method.

Boxplots are commonly used to detect outliers in a dataset. A boxplot is a visual representation of the distribution of a dataset through five summary statistics: minimum, first quartile (Q1), median, third quartile (Q3), and maximum. The box part of the plot covers the interquartile range (IQR), which is the range between the Q1 and Q3 quartiles, and the whiskers extend to the minimum and maximum values that are not considered outliers. Any data point outside the whiskers is considered an outlier.

## Detecting outliers by IQR method.

The Interquartile Range (IQR) method is a commonly used statistical method for detecting outliers in a dataset. The IQR is a measure of variability that is based on dividing a dataset into quartiles. It is defined as the difference between the first quartile (Q1) and the third quartile (Q3), that is, IQR = Q3 - Q1. Any data point that is below Q1 - 1.5IQR or above Q3 + 1.5IQR is considered an outlier.

## Handling outliers by Quantile based flooring and capping

Quantile-based flooring and capping is a technique used to handle outliers in a dataset by setting the extreme values to a certain percentile value. Flooring involves setting values below a certain percentile to a fixed value, while capping involves setting values above a certain percentile to a fixed value. The idea is to replace the extreme values with values that are more representative of the data while preserving the overall distribution.


## Handling outliers by Mean/Median imputation for outliers

Mean/Median imputation is a technique used to handle missing data in a dataset by replacing outliers values with the mean or median value of the non-missing values in the same variable. However, it can also be used to handle outliers by replacing extreme values with the mean or median value. This approach assumes that the outliers are due to measurement errors or other random fluctuations, and that the mean or median value is more representative of the underlying data than the extreme values.

## Happy Learning........................
