# 🔋 Battery Health Prediction using AI/ML

A Flask-based AI application that predicts the health condition of a battery using six machine learning models:  
**Random Forest, Support Vector Machine, Decision Tree, Naive Bayes, KNN, and Deep Neural Network.**

Users can log in, upload a dataset, run predictions, and also test real-time data from external APIs.  
This project was built as part of an AI/ML academic exploration with a focus on system accuracy, model comparison, and user interaction.

---

## 🚀 Features

- ✅ User login/register with session management
- ✅ Upload CSV files to analyze battery performance
- ✅ Compare accuracy of 6 machine learning models
- ✅ Real-time battery status prediction using API data
- ✅ Display accuracy, F1-score & prediction result
- ✅ UI built with Flask + HTML/CSS (Jinja templates)

---

## 🛠️ Tech Stack

| Layer       | Tools/Tech                 |
|-------------|----------------------------|
| Language    | Python, HTML/CSS           |
| Backend     | Flask, Jinja2              |
| Machine Learning | scikit-learn, joblib     |
| Models      | SVM, DT, RF, NB, KNN, DNN  |
| Storage     | MySQL (for login system)   |

---

## 📷 Screenshots

### 🔹 Login Page
![Login Page](screenshots/login.png)

### 🔹 Home Dashboard
![Home Dashboard](screenshots/home.png)

### 🔹 Battery Health Result
![Prediction Result](screenshots/result.png)

### 🔹 AI Model Comparison
![AI Chart](screenshots/chart.png)

> 📁 Place your screenshots in a folder named `/screenshots/` in your project repo.

---

## 🧠 Model Output Example

```text
Model        | Accuracy | F1 Score
-------------|----------|----------
RandomForest | 94.3%    | 0.94
SVM          | 92.1%    | 0.91
NaiveBayes   | 84.6%    | 0.83
