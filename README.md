# Telecom_Churn_Prediction

With rapid growth of digital systems and associated information technologies, there is an emerging trend in the global economy to build digital customer realtionsip management(CRM) systems. Customer churn prediction is critical feature of modern telecom CRM systemms as contract terminations would damage their revenue stream severly. Research has shown that the average monthly churn rate among the top 4 wireless carriers in the US is 1.9% - 2%. Churn analytics porvides valuable capabilities to predict customer churn and also define the underlying reasons that drive it. 

In this analysis: I first conducted a detailed exploratory data analysis(EDA) to to gain some insights into the possible causes of churn, and developed some hypothesis based on my findings. My next step was to leverage machine learning models to indetify the customers who are likely to churn, and also to access and compare the performance of different models based on various metrics. 

Data Preprocessing Steps:
 - Checking missing values, correlated variables
 - One-hot encoding 
 - EDA
 - Scaling all variables
 - Splitting data into training and testing sets

Modeling Techniques: 

  1. Logistic Regression 
  2. Random Forests
  3. LightGBM
  4. Neural Net 
    4.1 Simple 2layers NN
    4.2 2layers NN with regularization 
    4.3 3layers NN with regularization 

Model Evaluation Metrics:

- Accuracy score 
- ROC/AUC curve 
- Precision-Recall-Curve
- F1 Score 
- Feature weights 
- Confusion metrics
