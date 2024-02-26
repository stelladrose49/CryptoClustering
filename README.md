# CryptoClustering

CryptoClustering Overview

# Introduction
Utilize Python and unsupervised learning to predict the impact of 24-hour or 7-day price changes on cryptocurrencies.


# Data Sources
Located within the Resources Folder:

crypto_market_data.csv


# Key Findings
Elbow Curve Analysis:
Elbow Curve

<img width="788" alt="Screenshot 2024-02-27 at 7 22 33 AM" src="https://github.com/stelladrose49/CryptoClustering/assets/141170388/5d806cf6-66e2-4d36-96ca-0f2b40577c4f">


Elbow Curve for PCA Data

<img width="703" alt="Screenshot 2024-02-27 at 7 23 14 AM" src="https://github.com/stelladrose49/CryptoClustering/assets/141170388/a1b54531-ba0d-4b5d-8eff-093acfb8ad9a">


The second elbow curve for PCA data displays a lower inertia value compared to the first curve for the original data. This suggests that using fewer features reduces the sum of squared distances within clusters, indicating better clustering performance and tighter grouping of data points.
Cluster Scatter Plot Analysis:
cluster1
cluster2

Original Data (Cluster Graph 1): Overlapping clusters with no clear separation or distinctiveness, indicating a potential failure to capture underlying patterns.

PCA Data (Cluster Graph 2): Non-overlapping clusters with clear separation, showcasing four distinct clusters. Using fewer features through PCA potentially reduces noise and reveals more distinct patterns, resulting in meaningful and separable clusters.

**Conclusion
The utilization of fewer features (PCA data) for K-Means clustering of cryptocurrency data has positively impacted the results. It has led to well-defined and separable clusters compared to using the original data. The reduction in features through PCA likely emphasizes essential patterns, reduces noise, and enhances the accuracy of clustering results.

