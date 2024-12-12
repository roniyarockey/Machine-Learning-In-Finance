# Machine-Learning-In-Finance
This repository implements the DBSCAN algorithm to identify potential anomalies in stock market trading data. The focus is on detecting outlier trades and traders in a selected stock from the given dataset.

Project Outline:

Stock markets allow trading of company stocks where participants submit buy/sell orders matched by the market based on price and quantity.
The provided Trades.csv dataset contains trade data from multiple traders and stocks.
The objective is to use DBSCAN, an unsupervised learning technique, to identify:
Outlier Trades: Trades with anomalous quantities.
Outlier Traders: Traders whose activity significantly deviates from the norm.

DBSCAN Overview:

Density-Based Spatial Clustering of Applications with Noise (DBSCAN) groups data points based on density:
Core Points: Points in dense regions.
Border Points: Points close to core regions.
Outliers: Points in low-density regions.
DBSCAN is effective for anomaly detection because it does not require specifying the number of clusters and can identify arbitrarily shaped clusters.

Application:

Select a specific stock from the dataset.
Apply DBSCAN to identify:
Trades with abnormal quantities.
Traders with outlier behaviors (e.g., trading unusually large or small volumes).
This approach helps uncover trading anomalies without assuming prior knowledge of the data's structure.
