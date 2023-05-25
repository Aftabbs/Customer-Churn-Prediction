# Customer Churn Prediction
This project focuses on predicting customer churn in the telecommunications industry. The objective is to determine whether a customer is likely to switch to a different telecommunications provider, commonly referred to as "churning."
![image](https://github.com/Aftabbs/Customer-Churn-Prediction/assets/112916888/4d44d451-f98b-4d66-92ba-af0cdb692321)

# Dataset Description
The training dataset consists of 4,250 samples, each containing 19 input features and 1 target variable. The target variable, "churn," is a boolean variable indicating whether the customer has churned or not. The 19 input features provide various information about the customers.
The test dataset has 750 rows and 18 columns

# Data Cleaning and Preprocessing
Before building the predictive model, several data cleaning and preprocessing steps were performed:

* Dropping Insignificant Columns: Some columns that were deemed irrelevant or had a high number of missing values were dropped from the dataset. This step helped to focus on the most relevant features for churn prediction.

* Encoding Categorical Columns: Certain categorical columns were encoded using appropriate techniques such as one-hot encoding or label encoding. This process transformed categorical variables into numerical representations that can be used by machine learning algorithms.

*Univariate,Bivariate and Multivariate Plots
![image](https://github.com/Aftabbs/Customer-Churn-Prediction/assets/112916888/d61eb11e-3ddf-499a-a903-388536fb2e1f)
![image](https://github.com/Aftabbs/Customer-Churn-Prediction/assets/112916888/38452c9b-4c10-4728-8dec-cdbbceb06582)
![image](https://github.com/Aftabbs/Customer-Churn-Prediction/assets/112916888/decba51e-5c72-4cfd-9e42-90ed296b804d)

# Model Selection and Evaluation
To identify the best performing model for customer churn prediction, the LazyPredict classifier was utilized. This classifier provides a quick overview of the performance of various machine learning models without the need for extensive manual tuning. By using LazyPredict, it was possible to identify the model with the highest accuracy score.
![image](https://github.com/Aftabbs/Customer-Churn-Prediction/assets/112916888/21d0784b-ccab-46da-801b-00557eadea7a)

The LGBM (Light Gradient Boosting Machine) classifier was selected as the best performing model for customer churn prediction. Initially, the model achieved an accuracy score of base model is   96.58% . Subsequently, the model was fine-tuned, resulting in an improved accuracy score of 96.70%. The fine-tuning process involved optimizing hyperparameters to enhance the model's performance.

# Conclusion
This project successfully predicts customer churn in the telecommunications industry using machine learning techniques. By cleaning and preprocessing the dataset, encoding categorical variables, and utilizing the LGBM classifier, an accurate model was developed with a final accuracy score of 96.7%. The insights gained from this project can assist telecommunications companies in identifying customers at risk of churning, allowing them to take proactive measures to retain valuable customers.

# Industrial Use Case
The ability to predict customer churn has significant implications for the telecommunications and Other industries . By leveraging machine learning models, telecom companies can proactively identify customers who are likely to switch providers. This knowledge enables targeted retention efforts, such as personalized offers or improved customer service, to increase customer loyalty and reduce churn rates. Ultimately, accurate churn prediction can contribute to improved business performance and customer satisfaction.





