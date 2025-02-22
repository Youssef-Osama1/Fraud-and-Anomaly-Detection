# Fraud and Anomaly Detection in Financial Transactions

This repository contains two projects aimed at detecting fraudulent transactions and identifying anomalies in financial data. Both **supervised** and **unsupervised** machine learning techniques are applied to improve financial security.

## 📌 Project Overview

- **Fraud Detection**: A **supervised learning** approach using a neural network to classify transactions as fraudulent or legitimate.  
- **Anomaly Detection**: An **unsupervised learning** approach utilizing **Isolation Forest** and **Local Outlier Factor (LOF)** to identify unusual transaction patterns.  

## 🚀 Methodology

### 🔹 Fraud Detection (Supervised Learning)
1. **Data Preprocessing**
   - Handled missing values and standardized numerical features using `StandardScaler`.
   - Performed **Exploratory Data Analysis (EDA)** to understand data distribution.
2. **Model Selection**
   - Implemented a **Neural Network** with multiple hidden layers for classification.
   - Applied **ReLU** activation function and **Adam optimizer** for better learning.
3. **Evaluation**
   - Assessed model performance using:
     - **Confusion Matrix**
     - **Accuracy, Precision, Recall, and F1-Score**
   - Addressed class imbalance using **undersampling**.

### 🔹 Anomaly Detection (Unsupervised Learning)
1. **Feature Engineering & Scaling**
   - Applied `StandardScaler` to normalize data for better model performance.
2. **Anomaly Detection Models**
   - **Isolation Forest**: Detects anomalies by isolating points in fewer splits.
   - **Local Outlier Factor (LOF)**: Measures local deviation of data points from their neighbors.
3. **Model Evaluation**
   - Compared anomaly detection results across models.
   - Visualized detected anomalies using **boxplots and scatter plots**.

## 📊 Results and Insights

### **Fraud Detection Model (Neural Network)**
- **Accuracy**: **99.8%**
- **Precision**: **94.1%**
- **Recall**: **89.6%**
- **F1-Score**: **91.8%**
- The model effectively detects fraudulent transactions with **high precision and recall**, minimizing false positives and false negatives.

### **Anomaly Detection Models**
- **Isolation Forest** identified **X%** of transactions as potential anomalies.
- **Local Outlier Factor (LOF)** flagged **Y%** of transactions as anomalies.
- **(Mention which model performed better based on your observations).**  

## 🔍 Conclusion

- The **Fraud Detection Model** achieved **99.8% accuracy**, demonstrating **strong classification performance** in identifying fraudulent transactions.  
- The **Anomaly Detection Models** provided valuable insights by flagging suspicious transaction patterns without requiring labeled data.  
- **Combining supervised and unsupervised approaches** can enhance fraud detection systems by detecting both **known fraud patterns** and **previously unseen anomalies**.  
