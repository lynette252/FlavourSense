# FlavourSense
Predicts taste preferences (Sweet, Salty, etc.) using a Decision Tree trained on lifestyle features like sleep cycle and climate zone. Explores how habits influence sensory choices. Includes EDA, model visualization, and insights.


# 🍽️ FlavorSense: Taste Preference Prediction with Decision Trees

This project explores how lifestyle and behavioral patterns can be used to predict an individual’s **preferred taste** — Sweet, Salty, Sour, or Spicy — using a **Decision Tree classifier**. 

---

## 📊 Project Overview

- Used personal and lifestyle features such as:
  - `age`
  - `sleep_cycle`
  - `exercise_habits`
  - `climate_zone`
  - `historical_cuisine_exposure`
- Target variable: `preferred_taste`

The goal was to build an interpretable ML model that links everyday habits to flavor preferences.

---

## 🧪 Methods

- Performed **data cleaning** and handled missing values
- Used **One-Hot Encoding** for categorical features
- Trained a **Decision Tree Classifier** with `scikit-learn`
- Visualized the decision tree with `plot_tree`
- Evaluated using accuracy, confusion matrix, and classification report

---

## 🛠️ Tools & Technologies

- Python (Jupyter Notebook)
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## 📈 Sample Insight

> Users who are **Night Owls**, live in **temperate climates**, and have **moderate exercise habits** are more likely to prefer **Sweet** or **Sour** flavors.

---
## 🚀 Future Improvements

- Try alternative models (Random Forest, XGBoost)
- Deploy as a web app with Streamlit
- Add food or product recommendations based on predicted taste

---

## 📂 Project Structure

