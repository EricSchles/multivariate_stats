# Multivariate Statistical Analysis

The goal of this library is to provide robust multivariate statistical analysis tools in Python.

## Why this library

To date, Python has focused on "Machine Learning" libraries, rather than statistics, for the most part.  What should be clear from the increasing division of the "statistics" and "machine learning" communities is really a separation of tasks and concerns, rather than a difference in tools.  

Statisticians tend to be interested in exploratory analysis and report generation.  While Machine Learning practicioners primary concern is productionization of a model.  The same or similar tools will be used to get the model to a state where it can add business value.  However the audience and therefore tooling around the two tasks are fairly different.  

If your end result is a report, then you probably only care about the graphs of your model as well as reporting various statistics with respect to your model.  Similarly, if your goal is productionization, you may never document your models statistics, and quiet frankly may never care passed some measures of performance.

## A review of current main stream libraries

I feel that the true way to bring the full potential of data science to the business context is by serving both the function of the statistician and the machine learning practicioner.  We need to not be bound by anything as we seek truth.  And we also need to be able to verify what is true, once we think we've found some.  I believe libraries like scikit-learn, keras, tensorflow, and pytorch serve the machine learning practicitioner well.  But for classical statistics only seems to have statsmodels (a truly wonderful library), with limited multivariate statistics functionality.  For this reason I have decided to start work on multivariate-stats.  A new collection of statistical, rather than machine libraries.  

## Supported functionality (planned)

* casual modeling
* confirmatory factor analysis
* multivariate analysis of variance
* log-linear analyses of multi-way contingency tables
* logistic regression
* stepwise regression
* hierarchical regression
* probablistic regression
* tobit regression
* backward elimination
* forward elimination
* path analysis
* exploratory factor analysis
* multidimensional scaling
* meta-analysis
* discriminant analysis
* clustering
* latent structure discovery
* multivariate hypothesis testing
* outlier detection
* partial least squares

References:
* http://www.statgraphics.com/multivariate-methods
* https://www.statisticshowto.datasciencecentral.com/principal-component-analysis-2/#Redundancy
* https://newonlinecourses.science.psu.edu/stat505/
* https://python-for-multivariate-analysis.readthedocs.io/index.html
* https://www.kaggle.com/xdurana/multivariate-analysis-and-correlation-matrix
* https://www.statsmodels.org/stable/multivariate.html
* https://www.dummies.com/programming/big-data/data-science/python-for-data-science-developing-a-multivariate-approach-to-find-outliers/
* https://en.wikipedia.org/wiki/Multivariate_analysis
* https://en.wikipedia.org/wiki/Multivariate_statistics
* https://www.amazon.com/Methods-Multivariate-Analysis-Alvin-Rencher/dp/0470178965?ref_=fsclp_pl_dp_2
