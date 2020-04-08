Critical Infrastructures such as a power grid, thermal plants, water metering etc produce large
amounts of time series data. This project aimed to explore the data of electric consumption in
some foreign electrical power grid and figure anomalies by developing univariate and 
multivariate models, moving averages and One Class SVM. Data was explored to find 
appropriate time windows during a weekday day and a weekend day. Feature selection was 
based on correlation coefficients of the training data set. Principle Component Analysis was used 
to determine the most useful features in the training data set. Contextual anomalies were 
determined by building hidden Markov models. The models were built upon training data to 
replicate normal behavior and said models were used on test data where their log likelihoods 
were compared to evaluate anomalous behavior. Anomalies were further detected by using the 
method of moving averages and finally these anomalies were visually represented in the data 
with the help of a python library called pandas using a variation of a machine learning model 
called One Class SVM. Based on our models, the log likelihoods, and the different anomaly 
detection methods we use we determined that the test data sets are either quite anomalous or our 
models are not an accurate representation of the normal behavior.
