
### Explaining the situation
We've moved from the realm of probability to statistics where we have unknown population i.e. all we know is that we have data and statistics computed from the data. Our objective is to estimate the sampling distribution of statistic.

### What is Bootstrap technique?
Bootstrap is a technique that uses the ***given sample as the population*** (from which this sample is drawn) and creates a new distribution called ***Bootstrap Distribution***. This bootstrap distribution is then used for ***approximating the sampling distribution of mean (or other statistics).***  

### The Method for finding the bootstrap distribution of statistic

We draw bootstrap samples i.e. resamples of size n from the original sample with replacement and compute the desired statistic for each of the resample. 

The idea behind the bootstrap is that if the given sample is a representative of the population then the bootstrap distribution of the mean (or any other statistic) will resemble approximately to the sampling distribution of mean (or the statistic under consideration). This means, that ***"bootstrap distribution of mean will have roughly the same shape and spread as that of the sampling distribution of the mean".***
However, the eman of the bootstrap distribution will have the mean of the sample and not necessarily that of the population from which this sample came.
