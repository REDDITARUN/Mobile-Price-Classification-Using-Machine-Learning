# 📱 Mobile Price Classification Project

**[Check out the full article on this project here!](https://medium.com/@teendifferent/a-beginners-journey-into-mobile-price-classification-with-machine-learning-d10238a0acdd)**

Welcome to the Mobile Price Classification project! This beginner-friendly machine learning project uses various models to predict mobile phone price ranges based on key specifications. This repository contains the project code, analysis, and insights gained from exploring different classification techniques.

## 🚀 Project Overview

In this project, we classify mobile phones into price ranges based on technical features like RAM, battery power, and screen width. This prediction model can help companies assess competitive pricing and provide consumers with a better understanding of smartphone values.

## 📊 Dataset

The dataset contains 2,000 samples with 21 features such as:
- `battery_power`: Battery capacity in mAh
- `ram`: RAM in MB
- `px_height` and `px_width`: Screen resolution dimensions
- `four_g` and `three_g`: Network support features
- `price_range`: The target variable indicating price categories (0-3)

The dataset has been preprocessed for accuracy, with irrelevant features removed, such as `talk_time`.

## 🧠 Machine Learning Models

Four machine learning models were trained and evaluated to determine the best approach for this task:
1. **Logistic Regression**  
2. **Support Vector Machine (SVM)**
3. **Naive Bayes**
4. **Decision Tree Classifier**

Each model was tested, and the SVM model achieved the best performance with an accuracy of 86% and an AUC score of 0.96.

## 🔍 Key Findings

- **Feature Selection:** The most significant predictors of price range were `RAM`, `battery_power`, and `px_width`.
- **Model Performance:** SVM showed the best results, followed closely by the Decision Tree classifier.
- **Evaluation Metrics:** Both accuracy and AUC were used to determine model effectiveness across different price ranges.

## 📈 Results Summary

| Model                     | Accuracy | AUC Score |
|---------------------------|----------|-----------|
| Logistic Regression       | 78%      | 0.94      |
| Support Vector Machine    | 86%      | 0.96      |
| Naive Bayes               | 82%      | 0.94      |
| Decision Tree Classifier  | 83%      | 0.96      |

