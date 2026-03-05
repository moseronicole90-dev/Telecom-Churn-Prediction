# Telecom-Churn-Prediction
"A machine learning project using Random Forest to predict customer churn in the telecom industry."
# 📞 Telecom Customer Churn Prediction

## 🚀 Project Goal
The goal of this project is to predict which customers are likely to leave a telecom provider. By identifying these customers early, the company can offer incentives to keep them.

## 🛠️ Tools Used
* **Python** (Pandas, Scikit-Learn, Joblib)
* **Random Forest Classifier** (Machine Learning Model)
* **Kaggle** (Development Environment)

## 📊 Key Findings
After training the model on 3,333 customer records, I discovered:
* **Customer Service Calls:** The more times a customer calls support, the more likely they are to churn.
* **Daily Usage:** High "Day Minutes" and "Day Charges" are strong indicators of potential churn.

## 📁 Repository Contents
* `Project_1.ipynb`: The full data cleaning and ML process.
* `churn_model.pkl`: The saved (serialized) model.
* `model_columns.pkl`: The specific columns needed for future predictions.

## ✅ Results
The model achieved high accuracy and a strong recall rate, meaning it is effective at catching customers before they leave.
