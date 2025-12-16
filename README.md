# Credit Card Fraud Detection using Machine Learning

A machine learning project that identifies fraudulent credit card transactions by learning patterns from historical transaction data. The goal is to detect fraud accurately while minimizing false alerts for genuine users.

---

## 📌 Project Overview
Credit card fraud causes major financial losses every year. Since fraudulent transactions are very rare compared to normal ones, traditional systems fail to detect them effectively. This project uses machine learning techniques to classify transactions as **fraudulent** or **genuine** based on learned patterns.

---

## 🎯 Objective
- Detect fraudulent credit card transactions accurately
- Reduce false positives for genuine users
- Handle highly imbalanced transaction data

---

## 📂 Dataset
- Historical credit card transaction data
- Numerical features only (for privacy reasons)
- Target column:
  - `0` → Genuine transaction
  - `1` → Fraudulent transaction
- Highly imbalanced dataset

---

## ⚙️ Data Preprocessing
- Checked and handled missing values
- Feature scaling for better model performance
- Addressed class imbalance
- Split data into training and testing sets

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed fraud vs non-fraud transaction distribution
- Studied transaction behavior patterns
- Identified imbalance in target classes

EDA helped in selecting proper evaluation metrics beyond accuracy.

---

## 🤖 Model Used
- **Logistic Regression**

Chosen for its simplicity, interpretability, and strong baseline performance in binary classification problems.

---

## 📈 Model Evaluation Metrics
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

These metrics provide a complete view of performance, especially for imbalanced data.

---

## ✅ Results
The model achieved strong performance across all metrics:
- High **precision** reduced false fraud alerts
- High **recall** ensured most fraud cases were detected
- Strong **ROC-AUC** showed good class separation

---

## 🔧 Possible Improvements
- Use advanced models like Random Forest or XGBoost
- Add behavior-based features
- Optimize classification threshold
- Train with larger and real-time datasets

---

## 🚀 Future Scope
- Real-time fraud detection integration
- Continuous model retraining
- Explainable AI for transparency
- Deployment in banking or fintech systems

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure
