# Predictive Analytics for Churn Reduction at Ola

**Project Overview**

In response to the significant challenge of driver churn faced by Ola, our project focused on predicting driver attrition based on a range of attributes including demographics, tenure information, and historical performance data. By leveraging ensemble learning techniques and addressing class imbalance, we aimed to develop a robust predictive model to identify drivers at risk of leaving the company.

**Solution Approach**

We utilized ensemble learning methods such as Bagging and Boosting, along with KNN Imputation for handling missing values, to develop a predictive model for driver attrition. Additionally, we implemented strategies to address class imbalance in the dataset, ensuring the model's effectiveness in predicting churn.

**Data Collection and Preprocessing**

Our dataset included monthly information for drivers spanning 2019 and 2020, covering attributes such as demographics, tenure, and performance metrics. We performed data preprocessing tasks including imputing missing values, standardizing features, and handling class imbalance to prepare the data for model training.

**Model Training and Evaluation**

We trained multiple models, including Random Forest and XGBoost classifiers, using GridSearchCV for hyperparameter tuning. Evaluation metrics such as precision, recall, F1 score, and ROC AUC curve were used to assess the performance of each model on predicting driver churn.

**Results and Recommendations**

The developed models achieved promising results in predicting driver attrition, with precision, recall, and F1 scores indicating effective performance. Insights from the model can guide Ola in implementing targeted retention strategies and addressing specific issues contributing to driver churn.

**Actionable Insights & Recommendations**

1. **Increase Driver Payments** Consider adjusting driver payments based on driver activities and performance metrics to incentivize retention and reduce churn.

2. **Improve Driver Ratings** Encourage customers to provide positive ratings for drivers, as higher ratings correlate with driver retention. Implement initiatives to enhance customer satisfaction and improve driver ratings.

3. **Address Demographic Trends** Focus on addressing issues specific to demographic groups with higher churn rates, such as younger drivers aged 20-35, and drivers in cities with higher churn rates like C20. Tailor retention strategies to meet the needs of these groups.

4. **Investigate Low-Income Driver Issues** Analyze the reasons behind drivers dropping rides without attending and explore solutions to address these issues. Consider payment structures based on the number of rides per month to incentivize consistent driver participation.

**Model Deployment**

The best-performing model can be deployed for real-time predictions of driver churn. The trained model has been saved as a file ('driver_churn.sav') for easy deployment and integration into Ola's operational systems.

By implementing these recommendations and deploying the predictive model, Ola can effectively mitigate the challenges of driver churn, improve driver retention rates, and ultimately enhance operational efficiency and customer satisfaction.
