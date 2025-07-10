# battery-health-ai-predictor
A Flask-based web app that predicts battery health using AI/ML models
battery-health-app/
├── app.py
├── Dataset.csv
├── Main_training.py
├── Main_Testing.py
├── models/
│   ├── pipe_RF.joblib
│   ├── pipe_SVM.joblib
│   ├── pipe_DT.joblib
│   ├── pipe_KNN.joblib
│   ├── pipe_NB.joblib
│   └── pipe_DNN.joblib
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── contact.html
│   ├── battery.html
│   ├── ai.html
│   └── realtime.html
├── static/            # if you have CSS, JS, images
│   └── style.css
├── README.md
├── requirements.txt
└── .gitignore
