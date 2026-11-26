# AgroPredict 🌱
### Smart Crop Prediction Using Machine Learning

## 📌 Project Overview

AgroPredict is a machine learning-based crop prediction project that predicts suitable crops based on soil nutrients and environmental conditions.

The project uses two supervised machine learning algorithms, K-Nearest Neighbors (KNN) and Gaussian Naive Bayes, to classify suitable crops.

## 🎯 Objectives

- Develop a machine learning-based crop prediction system.
- Analyse soil and weather parameters.
- Implement and compare KNN and Gaussian Naive Bayes algorithms.
- Evaluate model performance using different classification metrics.

## 📊 Dataset Description

The Crop Recommendation Dataset contains:

- Total records: 2,200
- Total features: 7
- Target variable: `label`
- Number of crop classes: 22

### Input Features

| Feature | Description |
|---|---|
| N | Nitrogen |
| P | Phosphorus |
| K | Potassium |
| Temperature | Temperature |
| Humidity | Humidity |
| pH | Soil pH |
| Rainfall | Rainfall |

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 🤖 Machine Learning Algorithms

**1. K-Nearest Neighbors (KNN)**
- Distance-based classification algorithm.
- Number of neighbors: 7.
- StandardScaler used for feature scaling.

**2. Gaussian Naive Bayes**
- Probabilistic classification algorithm.
- Based on Bayes' theorem.
- Uses Gaussian distribution assumptions.

## 📈 Model Performance

| Evaluation Metric | KNN | Naive Bayes |
|---|---:|---:|
| Training Accuracy | 98.25% | 99.55% |
| Testing Accuracy | 95.91% | 99.39% |
| Precision | 96.47% | 99.46% |
| Recall | 95.91% | 99.39% |
| F1-score | 95.85% | 99.39% |

## 🏆 Conclusion

Both machine learning algorithms achieved good classification performance.

Gaussian Naive Bayes performed better than KNN, achieving a testing accuracy of 99.39%.

This project demonstrates the application of machine learning in agricultural crop prediction.

## 🚀 Future Scope

- Integration of real-time weather data.
- Inclusion of additional agricultural parameters.
- Development of a user-friendly web application.
- Testing with larger and more diverse datasets.

## 👩‍💻 Project Author

**SHAHINA SHAJAHAN**


