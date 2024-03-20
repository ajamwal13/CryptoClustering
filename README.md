# CryptoClustering

## Overview
Cryptocurrencies exhibit dynamic price movements across different timeframes. In this project, we explore how K-means clustering and Principal Component Analysis (PCA) can help classify cryptocurrencies based on their historical price changes. By analyzing data over intervals ranging from 24 hours to 1 year, we aim to identify distinct groups of cryptocurrencies with similar price behavior.

## Key Steps
1. **Data Collection**:
   - Gather historical price data for a diverse set of cryptocurrencies.
   - Include features representing price changes over various timeframes (24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year).

2. **Feature Engineering**:
   - Calculate percentage price changes for each cryptocurrency across different intervals.
   - Normalize the features to ensure comparability.

3. **Principal Component Analysis (PCA)**:
   - Apply PCA to reduce dimensionality while preserving essential information.
   - Identify the most influential features (principal components) that explain the variance in price changes.

4. **K-means Clustering**:
   - Use K-means to group cryptocurrencies based on their PCA-transformed features.
   - Determine the optimal number of clusters using techniques like the elbow method or silhouette score.

5. **Interpretation and Visualization**:
   - Visualize the clusters in a reduced-dimensional space (e.g., 2D scatter plot).
   - Analyze the characteristics of each cluster (e.g., high volatility, stable growth).

6. **Model Evaluation**:
   - Evaluate the quality of the clustering results.
   - Assess the interpretability and usefulness of the identified clusters.

## Expected Outcomes
- Insights into distinct cryptocurrency groups based on price fluctuations.
- A clear understanding of which timeframes contribute most to the clustering.
- A well-documented project with code, visualizations, and explanations.

## Conclusion
By combining K-means and PCA, we can gain valuable insights into the behavior of cryptocurrencies and potentially identify investment opportunities. 
