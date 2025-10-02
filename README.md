# Web Page Phishing Detection using Machine Learning
Machine learning-based phishing website detection using URL features.

## 📌 Overview
A machine learning project for detecting phishing websites based on URL features.  
The dataset is sourced from [Kaggle - Web Page Phishing Dataset](https://www.kaggle.com/datasets/danielfernandon/web-page-phishing-dataset/data).  
We analyzed the data, engineered features, and trained multiple models to classify websites as **phishing (1)** or **legitimate (0)**.

---

## ⚙️ Models and Performance
| Model                | Accuracy | ROC-AUC |
|-----------------------|----------|---------|
| Logistic Regression   | 85.63%   | 0.93    |
| Random Forest         | 89.09%   | 0.95    |
| XGBoost (Best Model)  | 89.18%   | 0.96    |

**XGBoost provided the most balanced performance across precision, recall, and F1-score.**

---

## 📊 Evaluation
- **Metrics Used:** Accuracy, Confusion Matrix, Classification Report, ROC-AUC.  
- **Findings:** Ensemble models (Random Forest, XGBoost) outperform linear models.  
- **Best Trade-off:** XGBoost achieved strong precision and recall on both classes.

---

## 🔑 Insights
- URL-based features are effective in distinguishing phishing from legitimate websites.  
- Advanced models capture complex patterns better than simple linear classifiers.  
- Feature engineering and class imbalance handling can further enhance performance.

---

## 🚀 Future Work
- Hyperparameter optimization for improved accuracy.  
- Additional feature engineering.  
- Exploring deep learning methods.  
- Deployment of the best model for real-time phishing detection.
