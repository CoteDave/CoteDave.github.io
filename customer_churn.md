# Survival Analysis
## Customer Churn
![](/images/customer_churn2.png)

**Project description:** For new submissions and renewals, estimate the conditional time to event (churn) to help actuarial decisions.

### 1. Data
* Batch ETL pipeline to refresh customer features, events and durations.

### 2. Model
* Forcasting: Ensemble of CoxRegression, DeepLearning and Gradient Boosting models.
* Predict the survival function for each customer.
* Calculate the conditional time to event (Predicted Duration)
* Calculate the survival probabilities at critical times for each customer and compare them with the probability distribution of their respective segment to compute individual risk scores.

[Back](https://cotedave.github.io/)
