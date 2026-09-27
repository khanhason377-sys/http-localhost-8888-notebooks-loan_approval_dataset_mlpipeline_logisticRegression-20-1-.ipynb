# http-localhost-8888-notebooks-loan_approval_dataset_mlpipeline_logisticRegression-20-1-.ipynb
# 🏦 Loan Approval Prediction using Logistic Regression

## 📌 Project Overview

This project predicts whether a loan application will be **Approved** or **Rejected** using **Machine Learning**.

The project uses the **Loan Approval Dataset** and applies a complete Machine Learning pipeline, including:

* Data Loading
* Data Preprocessing
* Handling Missing Values
* Encoding Categorical Data
* Feature Scaling
* Train-Test Split
* Machine Learning Pipeline
* Logistic Regression Model
* Model Evaluation
* Prediction on New Data

---

## 🎯 Objective

The main objective of this project is to build a machine learning model that can predict loan approval based on applicant information.

The model learns patterns from historical loan application data and predicts the loan approval status for new applicants.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Logistic Regression
* Machine Learning Pipeline

---

## 📂 Project Structure

```text
Loan-Approval-Prediction/
│
├── loan_approval_dataset_mlpipeline_logisticRegression.ipynb
├── README.md
└── loan_approval_dataset.csv
```

---

## 🔄 Machine Learning Workflow

The project follows these steps:

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Data Preprocessing
   ↓
Categorical Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
ML Pipeline
   ↓
Logistic Regression
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

---

## 🧹 Data Preprocessing

Before training the model, the dataset is prepared for Machine Learning.

The preprocessing includes:

1. Checking the dataset
2. Handling missing values
3. Separating features and target
4. Identifying numerical and categorical columns
5. Encoding categorical values
6. Scaling numerical features

Scikit-learn's preprocessing tools are used to make the data suitable for the Logistic Regression model.

---

## 🤖 Machine Learning Model

### Logistic Regression

**Logistic Regression** is a classification algorithm used to predict categorical outcomes.

In this project, it is used to classify loan applications into two possible classes:

* `Approved`
* `Rejected`

The model learns from the training data and then predicts the approval status of unseen applications.

---

## 🔗 Machine Learning Pipeline

A Machine Learning Pipeline is used to combine preprocessing and model training into a single workflow.

The pipeline helps to:

* Keep preprocessing organized
* Prevent data leakage
* Apply the same transformations to training and testing data
* Make predictions on new data easily
* Keep the code clean and reusable

---

## 📊 Model Evaluation

The trained model can be evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics help determine how well the model predicts loan approval.

---

## 🔮 Prediction

After training the model, new applicant information can be passed to the pipeline to predict whether the loan should be approved or rejected.

Example:

```python
prediction = pipeline.predict(new_data)

print(prediction)
```

The output represents the predicted loan approval status.

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project

Open the project folder in **Jupyter Notebook** or **VS Code**.

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn jupyter
```

### 4. Open the Notebook

Open:

```text
loan_approval_dataset_mlpipeline_logisticRegression.ipynb
```

### 5. Run All Cells

Run the notebook cells from top to bottom.

---

## 📁 Dataset

The project uses a Loan Approval Dataset containing applicant-related information and loan approval status.

The dataset is used to train and evaluate the Logistic Regression classification model.

---

## 💡 Key Learning Outcomes

Through this project, I learned:

* How to preprocess a real-world dataset
* How to handle numerical and categorical features
* How to use `ColumnTransformer`
* How to encode categorical data
* How to scale numerical data
* How to create an ML Pipeline
* How to train a Logistic Regression model
* How to evaluate a classification model
* How to make predictions using a trained pipeline

---

## 🚀 Future Improvements

The project can be improved by:

* Testing other classification algorithms
* Hyperparameter tuning
* Cross-validation
* Feature selection
* Comparing multiple models
* Deploying the model using Streamlit
* Creating a web interface for loan prediction

---

## 👨‍💻 Author

**Umar Tariq**

This project was created as part of Machine Learning practice and coursework.

---

## ⭐ Conclusion

This project demonstrates a complete Machine Learning workflow for **Loan Approval Prediction** using **Logistic Regression and Scikit-learn Pipeline**.

It provides a practical example of how raw data can be processed, transformed, used to train a classification model, and finally used to make predictions on new loan applications.
