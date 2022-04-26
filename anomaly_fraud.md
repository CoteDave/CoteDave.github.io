# Anomaly Detection
## Health claims Fraud Detection
![](/images/anomaly_detect.png)

**Project description:** Highlight anomalous claims and extract data rules to understand them and help improve the overall claim analysis process.

### 1. Data
* Batch ETL pipeline to refresh claims features.

### 2. Model
* Unsupervised Ensemble of multivariate models (Isolation Forest, KNN, UMAP-HDBSCAN...) and univariate statistics (Median Absolute Deviation (MAD), standard deviation...)
* Supervised Decision Tree and RuleFit models on predicted anomalies class to extract and understand the most important rules

[Back](https://cotedave.github.io/)
