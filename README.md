#Fraud_Transactions_Detection_Model

A machine learning system designed to detect fraudulent financial transactions using transaction behavior, account balance changes, and transfer patterns.

This project focuses on solving one of the biggest challenges in fraud analytics: **extreme class imbalance**, where fraudulent transactions represent only a very small percentage of total transactions.

The system compares multiple machine learning models and selects **XGBoost** as the best-performing model to maximize fraud detection while minimizing false negatives.

---

## 📌 Project Overview

Financial fraud causes billions in losses every year. Traditional rule-based systems often fail to identify new fraud patterns.

This project uses machine learning to:

- Detect suspicious transactions in real-time
- Identify hidden fraud patterns
- Reduce false negatives
- Improve fraud investigation efficiency

---

## 🚀 Features

✅ Data preprocessing and cleaning  
✅ Feature engineering  
✅ Class imbalance handling  
✅ Exploratory Data Analysis  
✅ Multiple model comparison  
✅ Hyperparameter tuning  
✅ Performance evaluation  
✅ Fraud probability prediction  

---

## 📂 Dataset

The dataset contains over **6 million transaction records** with transaction-related features such as:

| Feature | Description |
|---------|-------------|
| step | Time step |
| type | Transaction type |
| amount | Transaction amount |
| oldbalanceOrg | Sender balance before transaction |
| newbalanceOrig | Sender balance after transaction |
| oldbalanceDest | Receiver balance before transaction |
| newbalanceDest | Receiver balance after transaction |
| isFraud | Fraud label |

---

## ⚙️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-Learn**
- **XGBoost**
- **Matplotlib**
- **Seaborn**

---

## 🛠 Project Workflow

### 1. Data Preprocessing

- Missing value handling
- Duplicate removal
- Data type optimization
- Feature scaling
- Encoding categorical variables

### 2. Exploratory Data Analysis

- Transaction distribution analysis
- Fraud vs non-fraud comparison
- Correlation analysis
- Outlier detection

### 3. Class Imbalance Handling

Fraud datasets are highly imbalanced.

Techniques used:

- Random undersampling
- SMOTE
- Class weighting

### 4. Model Training

Models tested:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### 5. Model Evaluation

Metrics used:

- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

Special focus was given to **Recall**, since missing fraud transactions is costly.

---

## 🏆 Best Model

### XGBoost Classifier

XGBoost achieved the best overall performance:

- High Recall
- Low False Negatives
- Strong ROC-AUC Score
- Robust performance on imbalanced data

---

## 📊 Results

Example performance:

| Metric | Score |
|--------|-------|
| Accuracy | 99%+ |
| Precision | High |
| Recall | High |
| ROC-AUC | Excellent |

> Final scores may vary depending on train-test split.

---

## 📁 Project Structure

```bash
Fraud_Transactions_Detection_Model/
│
├── data/
├── notebooks/
├── models/
├── images/
├── src/
├── requirements.txt
├── fraud_detection.ipynb
└── README.md
```

---

## 🔧 Installation

Clone repository:

```bash
git clone https://github.com/syed-sadain/Fraud_Transactions_Detection_Model.git
```

Move into project:

```bash
cd Fraud_Transactions_Detection_Model
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run notebook:

```bash
jupyter notebook
```

Or run python script:

```bash
python fraud_detection.py
```

---

## 📈 Future Improvements

- Real-time fraud detection API
- Streamlit dashboard
- Deep learning models
- Model deployment on cloud
- Explainable AI with SHAP

---

## 👨‍💻 Author

**Syed Sadain**

- GitHub: https://github.com/syed-sadain
- LinkedIn: Add your LinkedIn profile here

---

## ⭐ If you found this project useful, please give it a star.
