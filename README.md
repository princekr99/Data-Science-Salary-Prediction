# Data-Science-Salary-Prediction
# Data-Science-Salary-Prediction

A machine learning project to predict **Data Science salaries** based on job-related features. This repository contains a trained model, preprocessing artifacts, a Flask app for inference, and the dataset used for training.

---

## 📁 Repository Structure

```
Data-Science-Salary-Prediction/
├── app.py               # Flask application for salary prediction
├── Untitled.ipynb       # Jupyter notebook (EDA, training, evaluation)
├── ds_salaries.csv      # Dataset used for training
├── gridsvr.pkl          # Trained ML model (GridSearch + SVR)
├── scaler.pkl           # Feature scaler used during training
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 🚀 Features

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature scaling
* Model training using **Support Vector Regression (SVR)** with GridSearch
* Salary prediction via a **Flask web app**
* Ready-to-use saved model and scaler

---

## 🛠️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/princekr99/Data-Science-Salary-Prediction.git
   cd Data-Science-Salary-Prediction
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Run the Application

```bash
python app.py
```

* Open your browser and go to: `http://127.0.0.1:5000/`
* Enter the required details to get a **salary prediction**

---

## 📊 Dataset

* **File:** `ds_salaries.csv`
* Contains information such as job role, experience level, employment type, company size, and salary.

---

## 🧠 Model Details

* Algorithm: **Support Vector Regression (SVR)**
* Hyperparameter tuning: **GridSearchCV**
* Preprocessing: **StandardScaler**
* Model file: `gridsvr.pkl`
* Scaler file: `scaler.pkl`

---

## 📌 Future Improvements

* Add frontend UI (HTML/CSS)
* Deploy on cloud platforms (Render / Heroku / AWS)
* Add more models for comparison
* Improve feature engineering

---

## 👤 Author

**Prince Kumar**
GitHub: [princekr99](https://github.com/princekr99)

---

⭐ If you like this project, consider giving it a star!
