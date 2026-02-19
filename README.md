# 🌱 Smart Crop Recommendation System

A Machine Learning-based Crop Recommendation System that predicts the most suitable crop based on soil nutrients and environmental conditions.

---

## 📌 Project Overview

This project uses a supervised Machine Learning model (Random Forest Classifier) to recommend the best crop to grow based on:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Value
- Rainfall

The model is deployed using FastAPI as a REST API for real-time predictions.

---

## 🚀 Features

- Data preprocessing and model training using Scikit-learn
- Random Forest classification model
- Model persistence using Joblib
- REST API built with FastAPI
- Interactive API documentation using Swagger UI

---

## 🛠 Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- FastAPI
- Joblib

---


## 📂 Project Structure

SMART-CROP-RECOMMENDATION/

├── data/
│ └── raw/
│ └── Crop_recommendation.csv
│
├── models/
│ └── crop_model.pkl
│
├── src/
│ ├── api/
│ │ └── app.py
│ └── models/
│ ├── train_model.py
│ └── predict.py
│
├── requirements.txt
├── README.md
└── .gitignore

