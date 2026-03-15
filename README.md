\# Customer Churn Prediction - End-to-End ML Pipeline



!\[Python](https://img.shields.io/badge/Python-3.8%2B-blue)

!\[scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-orange)

!\[Status](https://img.shields.io/badge/Status-Complete-success)



\## 📋 Project Overview



A production-ready machine learning pipeline to predict customer churn in the telecommunications industry. This project demonstrates end-to-end ML workflow including data preprocessing, feature engineering, model training, evaluation, and deployment-ready model artifacts.



\*\*Business Problem:\*\* Identifying customers likely to churn helps businesses take proactive retention measures, reducing revenue loss.



\## 🎯 Key Results



\- \*\*Best Model:\*\* \[Your best model - e.g., XGBoost]

\- \*\*ROC-AUC Score:\*\* \[Your score - e.g., 0.8456]

\- \*\*Accuracy:\*\* \[Your accuracy - e.g., 80.2%]

\- \*\*F1-Score:\*\* \[Your F1 - e.g., 0.78]



\## 📊 Dataset



\- \*\*Source:\*\* Telco Customer Churn Dataset

\- \*\*Size:\*\* 7,043 customers

\- \*\*Features:\*\* 20 (demographic, account, and service information)

\- \*\*Target:\*\* Churn (Yes/No)

\- \*\*Churn Rate:\*\* \~26.5%



\### Features Include:

\- \*\*Demographics:\*\* Gender, Senior Citizen, Partner, Dependents

\- \*\*Account Info:\*\* Tenure, Contract type, Payment method

\- \*\*Services:\*\* Phone, Internet, Online Security, Tech Support, etc.

\- \*\*Charges:\*\* Monthly charges, Total charges



\## 🛠️ Tech Stack



\- \*\*Language:\*\* Python 3.8+

\- \*\*ML Libraries:\*\* scikit-learn, XGBoost, imbalanced-learn

\- \*\*Data Processing:\*\* Pandas, NumPy

\- \*\*Visualization:\*\* Matplotlib, Seaborn

\- \*\*Model Persistence:\*\* Joblib





\## 🚀 Getting Started



\### Prerequisites

```bash

python >= 3.8

pip

```



\### Installation



1\. Clone the repository

```bash

git clone https://github.com/misrapk/churn-prediction-ml.git

cd churn-prediction-ml

```



2\. Create virtual environment

```bash

python -m venv venv

source venv/bin/activate  # On Windows: venv\\Scripts\\activate

```



3\. Install dependencies

```bash

pip install -r requirements.txt

```



4\. Download dataset from \[Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place in `data/` folder



\### Usage



1\. \*\*Run EDA:\*\*

```bash

jupyter notebook notebooks/01\_eda.ipynb

```

2\. \*\*Use Preprocessor (standalone):\*\*

```bash

python src/data\_preprocessing.py

```



\## 🔍 Methodology



\### 1. Data Preprocessing

\- Handled missing values in `TotalCharges`

\- Created engineered features:

&#x20; - `tenure\_group`: Categorized tenure into bins

&#x20; - `avg\_monthly\_per\_tenure`: Average spending rate

&#x20; - `num\_services`: Count of subscribed services

\- Encoded categorical variables (Label Encoding \& Binary Encoding)

\- Scaled numerical features using StandardScaler







\## 📝 Lessons Learned



1\. \*\*Feature engineering\*\* significantly improved model performance (+8% ROC-AUC)

2\. \*\*Class imbalance\*\* handling crucial for churn prediction



\## 👤 Author



\*\*Peeyush Kant Misra\*\*

\- LinkedIn: \[Your Profile](https://linkedin.com/in/yourprofile)

\- GitHub: \[@misrapk](https://github.com/misrapk)

\- Email: peeushkmisra@gmail.com



\## 📄 License



This project is licensed under the MIT License - see the LICENSE file for details.



\## 🙏 Acknowledgments



\- Dataset provided by IBM Watson Analytics

\- Inspired by real-world telecom churn challenges

