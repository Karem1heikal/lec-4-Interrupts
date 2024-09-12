Clustering and GAM Project
Overview
This project explores three powerful clustering techniques: KMeans, Hierarchical Clustering, and Generative Additive Models (GAM). The goal is to understand how different cluster numbers affect the results, especially with KMeans, and the effects of GAM in classification models.

Project Highlights
1. Data Preprocessing
Cleaned and normalized the dataset.
Handled missing values.
Converted categorical variables into numerical formats.
Engineered new features such as material properties to improve predictive performance.
2. Principal Component Analysis (PCA)
Applied PCA using both built-in functions and custom implementations.
Reduced dimensionality to enhance the clustering process by focusing on the most significant features.
3. KMeans Clustering
Experimented with different values for n_clusters:
2 clusters
3 clusters
4 clusters
Achieved the best separation and clearest distinction between data points with 3 clusters.
4. Hierarchical Clustering
Built clusters in a hierarchical tree structure.
Analyzed dendrograms to decide the number of clusters without predefining them.
5. Generative Additive Model (GAM)
Extended the generalized linear model (GLM) for more flexible, non-linear relationships between predictor and response variables.
Found GAM particularly effective in time series analysis.
Outcome
KMeans: Best results with 3 clusters.
Hierarchical Clustering: More flexibility without predefining clusters.
GAM: Excellent for time series analysis.
