# Clustering Financial Data: A Machine Learning Approach to Stock Performance Analysis

This repository contains the implementation of our project on clustering stock performance data to identify meaningful patterns and groupings. By leveraging advanced machine learning techniques and time series analysis, we aimed to uncover hidden relationships in stock price movements, enabling better investment strategies, portfolio diversification, and risk management.

## Objectives

- Analyze time series data of stock prices.
- Identify clusters of stocks with similar movement patterns using machine learning techniques.
- Provide actionable insights for financial analysts, investors, and traders.

## Key Features

- **Time Series Analysis:** Feature engineering with moving averages, exponential moving averages (EMAs), and volatility ratios.
- **Clustering Algorithms:**
  - K-Means with Euclidean and Dynamic Time Warping (DTW) distances.
  - LSTM Autoencoders for dimensionality reduction.
  - Hierarchical Clustering for nested groupings.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) and LSTM Autoencoders to reduce feature space complexity.
- **Evaluation Metrics:** Silhouette score, inertia, and comparison with sector labels to validate clustering quality.

## Methodology

1. **Data Acquisition:** Stock price dataset with financial indicators for 491 companies sourced from [Kaggle](https://www.kaggle.com/datasets/iveeaten3223times/massive-yahoo-finance-dataset).
2. **Feature Engineering:**
   - Moving Averages (7-day, 30-day, 90-day).
   - EMAs (up to 3 years).
   - Volatility Ratio and Rate of Change (ROC).
3. **Clustering Techniques:**
   - K-Means with DTW and PCA.
   - LSTM Autoencoder followed by K-Means.
   - Hierarchical Clustering with dendrogram visualizations.
4. **Visualization:**
   - Elbow and Silhouette plots to determine the optimal number of clusters.
   - t-SNE for cluster visualization in reduced dimensions.

## Results

- **K-Means with PCA:** Improved silhouette score of 0.34 compared to non-PCA data.
- **LSTM Autoencoder:** Achieved a silhouette score of 0.46, effectively capturing temporal dependencies.
- **Hierarchical Clustering:** Produced 14 distinct clusters aligned with industry patterns, achieving a silhouette score of 0.45.

## Future Work

- Incorporating additional features like sentiment analysis and macroeconomic indicators.
- Exploring advanced techniques like Deep Clustering models.
- Integrating time-series forecasting for dynamic cluster analysis.

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Clustering-Financial-Data.git


## Authors
- Dharmil Yogesh Karia
- Darsh Chetan Pandya
- Hiba Khan
