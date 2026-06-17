
Model Card — Churn Prediction
Intended Use
Predict customers at risk of churn in next 60 days to enable targeted retention.

Data Used

Orders, RFM features
Support tickets
Web/app activity
Churn labels


Model Approach

Baseline: Logistic Regression
Final: Random Forest


Performance

ROC-AUC: 0.86
Recall prioritized for business value


Key Drivers

Recency
Frequency
Support complaints
Web engagement


Limitations

Limited historical depth
External factors not captured


Ethical Risks

Over-targeting customers with offers
Bias from incomplete behavior data


Monitoring

Data drift
Prediction distribution
Recall drop
Monthly retraining
