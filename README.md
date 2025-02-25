# **Principal Component Analysis (PCA)**

* It is a dimensionality reduction technique that transforms a dataset with correlated variables into a set of lineraly uncorrelated variables called principal components. The goal is to reduce the number of features while preserving as much variance as possible.

* It reduces the number of dimensions in large datasets to principal components that retain most of the original information.

* PCA is commonly used for data preprocessing for use with machine learning algorithms. It can extract the most informative features from large datasets while preserving the most relevant information from the initial dataset.

* PCA reduces dimensionality to improve computational efficiency, helps in visualizing high-dimensional data, removes redudancy in correlated features, and reduces overfitting by eliminating less significant features.

**How PCA works:**

**1) Standardize data**

- Since PCA is affected by different feature scales, we first normalize the data to have mean of 0 and variance of 1.

**2) Compute the covariance matrix**

- The covariance matrix captures the relationships between features.

**3) Compute eigenvalues and eigenvectors**

- Eigenvalues represent the magnitude of variance in particular direction;
- Eigenvectors represent the directions (principal components) in which variance is maximum.

**4) Sort eigenvectors by eigenvalues**

- The eigenvectors with the highest eigenvalues correspon to the most important principal components.

**5) Project the data onto the principal components**

- The data is transformed into a new coordinate system defined by selected principal components.

