# 🔋 Battery Health Prediction using AI

A Flask-based web app that predicts battery health status (Good, Weak, or Dead) using six ML models: SVM, Decision Tree, Random Forest, Naive Bayes, KNN, and Deep Neural Network. Real-time predictions are also integrated via external API.

## 🚀 Features
- User authentication (register & login)
- Upload and train models using a CSV dataset
- Predict battery condition using AI
- Real-time API integration to monitor live battery data
- Accuracy & F1-score displayed for each ML model

## 💻 Tech Stack
- Python, Flask, HTML/CSS
- Machine Learning (scikit-learn, joblib)
- Models: RF, SVM, DT, NB, KNN, DNN
- MySQL (for login system)

## 📁 Project Structure
- `app.py`: Main backend Flask app
- `Main_training.py`: Model training pipeline
- `Main_Testing.py`: Individual model testing
- `models/`: Contains all serialized model files
- `templates/`: HTML pages
- `Dataset.csv`: Battery health training dataset

## 🔧 Setup Instructions
```bash
pip install -r requirements.txt
python app.py

