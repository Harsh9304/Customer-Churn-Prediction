# Customer Churn Prediction

A machine learning notebook project that analyzes telecom customer churn and predicts whether customers will stay, leave, or join. The repository includes the dataset, notebook, and project metadata needed to reproduce the analysis.

## 📌 Problem Statement
The dataset contains information from a California telecommunications company with 7,043 customers and includes demographics, service subscriptions, tenure, account information, and churn status. The goal is to predict whether a customer will churn, stay, or join using classification models.

## 🚀 What’s Included
- `src/Customer_Churn_Prediction.ipynb`: Jupyter notebook with data cleaning, exploratory data analysis, feature preparation, model training, evaluation, and visualization.
- `Datasets/telecom_customer_churn.csv`: Customer churn dataset used in the notebook.
- `assets/`: Visual assets and charts used in the notebook.
- `LICENCE`: Project license file.
- `.gitignore`: Files and folders excluded from version control.
- `requirements.txt`: Python package dependencies.

## 📊 Models Evaluated
- Random Forest
- Logistic Regression
- Gaussian Naive Bayes
- Decision Tree
- XGBoost

## ✅ Key Results
- XGBoost achieved the highest accuracy among the evaluated models.
- The notebook also includes comparison metrics, confusion matrix, and ROC/PR visualizations.

## 📁 Project Structure
```text
Customer-Churn-Prediction-main/
├── LICENCE
├── README.md
├── .gitignore
├── requirements.txt
├── Datasets/
│   └── telecom_customer_churn.csv
├── assets/
│   └── [visualization images]
└── src/
    └── Customer_Churn_Prediction.ipynb
```

## 🧰 Setup Instructions
1. Clone the repository or copy the files to your local machine.
2. Create a Python virtual environment:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook src/Customer_Churn_Prediction.ipynb
   ```

## 📌 Notes
- The notebook relies on the `Datasets/telecom_customer_churn.csv` file.
- If you want to run the notebook on Google Colab, upload the dataset and update the file path accordingly.

## 🧾 License
This project is licensed under the MIT License. See the `LICENCE` file for details.

## ✍️ Author
- [Himanshu Agarwal](https://github.com/himanshu-03)
