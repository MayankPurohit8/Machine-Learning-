Outliers affect algorithms that work on weights such as linear regression, logistic regression.

Treating outliers:

1. Trimming - removing outliers
2. Capping
3. Treat outliers as missing values
4. Discretization

Outliers Detection:

1. normal dist. = z-score
2. skequed dist. = interquartile range

zscore :

    xi* = xi - x.mean / x.std

in IQR outliers are:
smaller than Q1 - 1.5*IQR
greater than Q2 + 1.5*IQR

can be recognized in a boxplot easily

Steps :

1. check if the data is normally distributed or skequed , by displot seaborn
2. if normal use zscore else use IQR method
