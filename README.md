# Credit Card Fraud Detection Using Predictive Models

## Project Overview

This project focuses on building and evaluating machine learning models to detect fraudulent credit card transactions. Fraud detection is a classic **imbalanced classification problem**, where fraudulent cases represent a very small fraction of total transactions. The goal is to maximize fraud detection while minimizing false positives that can inconvenience legitimate customers.

The project demonstrates an end-to-end **applied machine learning workflow**, including data preprocessing, exploratory analysis, feature engineering, model training, and evaluation using appropriate metrics for imbalanced datasets.

---

## Objectives

* Identify fraudulent credit card transactions using predictive modeling
* Handle severe class imbalance effectively
* Compare multiple machine learning algorithms
* Evaluate models using business-relevant metrics

---

## Data
The dataset used in this project is the **Credit Card Fraud Detection Dataset** from Kaggle.

🔗 Dataset link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## Models Implemented

The following models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting / XGBoost (if applicable)

Each model was assessed using metrics suitable for imbalanced data rather than accuracy alone.

---

## Evaluation Metrics

Given the imbalance in the dataset, the following metrics were emphasized:

* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

Special focus was placed on **Recall**, as missing fraudulent transactions is typically more costly than flagging legitimate ones.

---

## Techniques Used

* Data cleaning and preprocessing
* Feature scaling
* Handling class imbalance (e.g., resampling / class weighting)
* Model comparison and selection
* Performance visualization

---

## Tools & Technologies

* Python
* Jupyter Notebook
* Pandas & NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

##  Key Insights

* Tree-based ensemble models significantly outperform linear models on fraud detection tasks
* Proper handling of class imbalance is critical for meaningful results
* Accuracy alone is misleading in highly imbalanced datasets

## License

This project is for educational and portfolio purposes.

