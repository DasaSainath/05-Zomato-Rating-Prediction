# 🍽️ Zomato Rating Prediction

## 📌 Overview
This project predicts **restaurant ratings** based on user inputs and restaurant details. It uses **Machine Learning (ML) models** to analyze Zomato review data and forecast ratings. Additionally, a **Flask-based web application** allows users to input restaurant details and receive predicted ratings dynamically.

## 🎯 Project Goals
1. **Data Preprocessing & Cleaning**: Handle missing values, remove outliers, and extract relevant features.
2. **Exploratory Data Analysis (EDA)**: Analyze rating distributions, user reviews, and feature importance.
3. **Feature Engineering**: Convert categorical data into numerical format for model training.
4. **Model Development**: Train a **Machine Learning model** to predict restaurant ratings.
5. **Performance Optimization**: Tune hyperparameters for improved prediction accuracy.
6. **Web App Development**: Build a **Flask-based UI** where users can enter restaurant details and get rating predictions.
7. **Deployment**: Integrate the ML model with a **Flask web app**, using **HTML, CSS, and JavaScript** for a seamless user experience.

## 🚀 How It Works
- Users **select food items and restaurant details** through an HTML interface.
- The **Flask app (`app.py`) processes user inputs** and sends them to the ML model (`model.pkl`).
- The **trained model predicts the restaurant rating** and displays it on the webpage.

## 🛠️ Tech Stack
- **Python, Flask** (Backend & API)
- **Pandas, NumPy, Scikit-learn** (Data Processing & ML)
- **HTML, CSS, JavaScript** (Frontend UI)
- **Pickle** (Model Serialization)

## 📂 Project Structure
```
📁 Zomato-Rating-Prediction
│-- 📄 README.md  # Project Documentation
│-- 📄 app.py  # Flask Web Application
│-- 📄 model.pkl  # Trained Machine Learning Model
│-- 📁 templates/  # HTML Files (index.html)
│-- 📁 static/  # CSS and JS Files
│-- 📄 zomato_rating.ipynb  # Jupyter Notebook (Data Processing & Model Training)
```

## 📜 License
This project is open-source and available under the **MIT License**.

---
🍕 **Predict restaurant ratings and enhance user experience!**
