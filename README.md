# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, and the goal is to accurately identify fraudulent transactions while minimizing false positives.
---

## 📂 Dataset
- **Source:** Kaggle – Credit Card Fraud Detection Dataset
- **link**: [creditcard.csv](https://www.kaggle.com/datasets/fatimarizvi2/credit-card)
- **Total Transactions:** 284,807  
- **Fraudulent Transactions:** 492  
- **Legitimate Transactions:** 284,315  

The dataset contains anonymized features (`V1`–`V28`) generated using PCA to protect sensitive customer information, along with `Time`, `Amount`, and `Class` (target variable).

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔍 Project Workflow

### 1. Data Loading & Exploration
- Loaded dataset using Pandas
- Displayed summary statistics
- Analyzed class imbalance between fraud and normal transactions

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of transaction amounts
- Correlation heatmap to understand feature relationships
- Separate analysis for fraudulent and valid transactions

### 3. Data Preprocessing
- Split data into features (`X`) and target (`y`)
- Performed train-test split (80% training, 20% testing)
- Handled missing values using `SimpleImputer`

### 4. Model Building
- Implemented **Random Forest Classifier**
- Trained the model on transaction data
- Generated predictions on test data

### 5. Model Evaluation
- Accuracy Score
- Precision, Recall, F1-score
- Matthews Correlation Coefficient
- Confusion Matrix visualization

---

## 📊 Results
- The Random Forest model achieved high accuracy on test data
- Confusion matrix visualization highlights fraud vs normal predictions
- Evaluation metrics demonstrate the effectiveness of the model on imbalanced data

---

## 📈 Visualizations
- Correlation heatmap
- Transaction amount distribution
- Confusion matrix heatmap
