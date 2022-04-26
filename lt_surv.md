# Survival Analysis
## Long-term disability claims duration
![](/images/surv_funcs.png)

**Project description:** Estimate the duration of long-term disability claims to support actuarial decisions and to optimize claims management.

### 1. Data
* Batch ETL pipeline to refresh claims features, events and durations.

### 2. Model
* Forcasting: Ensemble of CoxRegression, DeepLearning and Gradient Boosting models.
* Predict the survival functions for each claim.
* Calculate the conditional time to event (Predicted Duration)
* Calculate the survival probabilities at critical times for each claim.

[Back](https://cotedave.github.io/)
