## 🚦 Accident Prediction System

A machine learning system designed to analyze and predict the likelihood of road accidents based on historical and environmental data.

-----------------------------------------------

## 📘 Overview

This project focuses on building an Accident Prediction Model that helps identify factors leading to road accidents and predict the probability of future occurrences.

The system leverages advanced machine learning algorithms and structured data preprocessing to deliver accurate and efficient predictions.

-----------------------------------------------

## 🧩 Project Progress & Model Evolution
🧠 Initial Approach — SVM (Support Vector Machine)

Started with an SVM-based model to classify accident likelihood.

Faced performance challenges:

Long training time on large datasets

Poor generalization on test data

Low accuracy and weak handling of nonlinear patterns

⚡ Improvement — LightGBM Implementation

Transitioned to LightGBM (Light Gradient Boosting Machine) for better performance.

Benefits achieved:

⚡ Significantly faster training

🎯 Improved accuracy and R² score

📉 Lower Mean Absolute Error (MAE) and RMSE

🧠 Better handling of feature importance and missing values

-------------------------------------------------------------------------------

## 📊 Model Performance
Metric	Score
Mean Absolute Error (MAE)	0.0437
Root Mean Squared Error (RMSE)	0.0562
R² Score	0.8854

-----------------------------------------------------------------------------------

## 🧰 Tech Stack

Programming Language: Python 🐍

Libraries & Tools:

pandas, numpy — data processing

matplotlib, seaborn — visualization

scikit-learn — preprocessing and evaluation

lightgbm — machine learning model

Environment: Jupyter Notebook
