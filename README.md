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
![Login Page](screenshots/[login](https://github.com/user-attachments/assets/2c3e9fdc-5c1f-4284-a9f7-695e971b2d19)
gin.png)

### 🔹 Ai Results
![Home Dashboard](screenshots/[Ai results](https://github.com/user-attachments/assets/c69863d7-7877-422d-b587-5400f9eccf64)
e.png)

### 🔹 Battery Health Result
![Prediction Result](https://github.com/user-attachments/assets/0fae9c56-a0b5-4d8f-827e-4d55e883e819)

### 🔹 Real time prediction
[Real time prediction](https://github.com/user-attachments/assets/ec85bc44-55bb-4943-a8c9-e444dad97f54)
ng)
### 🔹 Regestration
![Regestration](https://github.com/user-attachments/assets/ce1b7ad1-6ecd-4e54-b68d-ca04ab0296bc)
### 🔹 Contact
![contact](https://github.com/user-attachments/assets/27ccba6a-a98b-4823-8062-6544fa956e80)

## 🧠 Model Output Example

```text
Model        | Accuracy | F1 Score
-------------|----------|----------
RandomForest | 94.3%    | 0.94
SVM          | 92.1%    | 0.91
NaiveBayes   | 84.6%    | 0.83
