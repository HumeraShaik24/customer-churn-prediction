# customer-churn-prediction
"End-to-end AI-based Customer Churn Prediction using Machine Learning"
# 📊 Customer Churn Prediction

## 📁 Project Title

Customer Churn Prediction Using Machine Learning (Random Forest Classifier)

## ❓ Problem Statement

Telecom companies face significant revenue loss when customers discontinue their services. Early identification of potential churners enables proactive retention strategies. This project aims to develop a predictive model that accurately identifies customers who are likely to churn.

## 🌟 Objective

To build a machine learning model that predicts customer churn using demographic, account, and service-related features from a telecom dataset.

## 🧠 Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook
* Git & GitHub

## 🗂️ Dataset

The dataset includes:

* 7,000+ customer records
* 30 input features (e.g., tenure, monthly charges, contract type)
* 1 target variable: `Churn` (Yes/No)

## 🧪 Data Preprocessing

* Removed duplicates and missing values
* Converted categorical variables using one-hot encoding
* Scaled numeric features using StandardScaler

```python
![Screenshot (31)](https://github.com/user-attachments/assets/0c383836-0cf8-4d9f-98be-2900d08e1070)

```
## 📈 Exploratory Data Analysis (EDA)

Key findings:

* Customers with shorter tenure and higher monthly charges are more likely to churn.
* Contract type and internet service have a significant impact.

![Churn Distribution](visualizations/churn_distribution.png)
![Contract Type Impact](visualizations/contract_type_vs_churn.png)

```## 🧠 Model Building

```
Used a `RandomForestClassifier` for high interpretability and performance.
```
![Screenshot (32)](https://github.com/user-attachments/assets/2e78a9fa-70a7-4367-bb61-6ee3484dc66f)


```

## 📊 Model Evaluation

* **Accuracy**: `79.03%`
* **Precision (Churn)**: `64%`
* **Recall (Churn)**: `48%`
* **F1 Score (Churn)**: `55%`

![Screenshot (33)](https://github.com/user-attachments/assets/9105edfb-a6c6-4f34-aec0-0eec8905d9aa)
```

## ✅ Results & Impact

The model achieved nearly **79% accuracy**, helping to proactively identify potential churners. This can potentially reduce churn-related losses by targeting at-risk customers with retention strategies.

## 🚀 Future Improvements

* Use ensemble techniques like XGBoost for better performance
* Hyperparameter tuning using GridSearchCV
* Deployment using Flask or Streamlit

## 🔗 Links

* 📂 [Project Notebook](link-to-notebook)
* 📊 [Dataset Source](link-to-dataset)
* 📸 [Visualizations Folder](link-to-images)
* 📌 [Live Demo (if available)](link-to-demo)

## 🙋‍♀️ Author

**Humera Shaik**
GitHub: [HumeraShaik24](https://github.com/HumeraShaik24)
