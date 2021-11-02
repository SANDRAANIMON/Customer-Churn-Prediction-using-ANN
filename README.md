# Customer-Churn-Prediction-using-ANN
**A customer churn prediction model using artificial neural network or ANN. Customer churn measures how and why are customers leaving the business. WE will use telecom customer churn dataset from kaggle (link below) and build a deep learning model for churn prediction.**
<img src="data:image/jpeg;base64,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">
