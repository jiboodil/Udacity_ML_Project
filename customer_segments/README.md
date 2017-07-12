# Customer Segmentation

## Overview
In this project, I applied unsupervised learning to analyze constomer data and unconver underlying patterns. The high dimensional customer data was first transformed into 2 dimensions by using **Principal Component Analyisis**. The principal components revealed crucial information on what features or combination of features are most relevant for capturing the variation. The transformed data was then clustered using **Gaussian Mixture Model** and compared to real clusters.

## Result
Two groups of very distince spending pattern can be clearly visualized, one being the wholesaler and the other retailer. The clustering results from Gaussian Mixture Model are fairly consistent with the actual consumer categories.

## Further Work
Since we have successfully clustering the data into 2 groups, we can train a supervised learner for predicting the types of customer for new data.
