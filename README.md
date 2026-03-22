# 📊 NVIDIA Stock Analysis (1999–2026)

## 🚀 Overview
This project is part of **Week 4** of the Microsoft-affiliated Data Science Internship.  
The goal is to analyze NVIDIA stock data from **1999 to 2026** using the **One-vs-Rest (OvR)** classification algorithm.

We transform stock trends into a classification problem and apply machine learning techniques to understand patterns and predict stock movement categories.

---

## 🎯 Objectives
- Analyze historical NVIDIA stock data (1999–2026)
- Apply **One-vs-Rest (OvR)** classification
- Categorize stock movements (e.g., Up, Down, Stable)
- Evaluate model performance using standard metrics
- Gain practical experience in machine learning workflows

---

## 🧠 What is One-vs-Rest (OvR)?
One-vs-Rest (OvR) is a strategy used for **multi-class classification** problems.

- It splits a multi-class problem into multiple binary classification problems
- Each class is trained against all other classes
- Final prediction is based on the classifier with the highest confidence

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 📂 Dataset
- Historical NVIDIA stock data (1999–2026)
- Features include:
  - Open price
  - Close price
  - High / Low
  - Volume
  - Derived indicators (optional)

---

## ⚙️ Project Workflow

### 1. Data Collection
- Load historical stock data
- Clean and preprocess dataset

### 2. Feature Engineering
- Create new features such as:
  - Daily returns
  - Moving averages
  - Volatility indicators

### 3. Label Creation
- Convert stock movement into categories:
  - 📈 Up
  - 📉 Down
  - ➖ Stable

### 4. Model Training
- Apply **One-vs-Rest classifier**
- Use models such as:
  - Logistic Regression
  - SVM (optional)

### 5. Evaluation
- Accuracy score
- Confusion matrix
- Classification report

---

## 📊 Results
- The OvR model successfully classified stock movements into multiple categories
- Performance depends on:
  - Feature quality
  - Data preprocessing
  - Model selection

---

## 📈 Future Improvements
- Add more technical indicators (RSI, MACD)
- Use deep learning models (LSTM)
- Perform hyperparameter tuning
- Deploy as a web app/dashboard

---

## 💡 Key Learnings
- Understanding multi-class classification using OvR
- Applying machine learning to real-world financial data
- Importance of feature engineering in model performance

---

### 👨‍💻 Author
Mohammed Zuoriki
Cybersecurity Student | Aspiring Cloud Security Architect | Self-Driven Technologist
<br> LinkedIn: https://www.linkedin.com/in/mohammed-zuoriki-856133250/

------

### ⭐ Contributing

Contributions, feedback, and ideas are welcome.
Feel free to fork the repository or open an issue.
