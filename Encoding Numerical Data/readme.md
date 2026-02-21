Discretization(binning) is the process of transforming continous variables into discrete variables by creating a set of contiguous intervals that span the range of the variable's value. Discretization is also called binning , where bin is an alternative name for and interval.

Why to use Discretization :

1. To handle outliers
2. To improve the value spread

Types :

1. Unsupervised binning - equal width binning , equal frequency binning , kmeans binning
2. Supervised binning - decision tree binning
3. Custom binning

Equal Width binning :

You have to decide number of bins
formula applied = max-min / number of bins

Quantile binning :

binning based on frequency on ranges
no equal range

kmeans binning:

uses kmeans clustering to form bins
