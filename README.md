# Weather Prediction
## Algorithmic Machine Learning - Challenge 1
The Weather Prediction problem at hand consists of dealing with pairs of meteorological features and target values at a particular
latitude/longitude and time. The task is affected by the mismatch between training and deployment data. This is due to training data sampled from a distribution, which is different from the one where test data is drawn from. More specifically, while the distribution of inputs may change over time, the labeling function, i.e. the conditional distribution $P(y|x)$, does not change. This phenomenon is known as covariate shift because it arises due to a shift in the distribution of the covariates, namely the features.
