# 🏡 House Price Prediction with MLflow

## 📑 Table of Contents

* 🌟 Overview
* 🛠️ Technologies Used
* 🎯 Project Objectives
* 🚀 Key Features
* 🛠️ Methodology
* 🧠 Model Training and Evaluation
* 🎉 Conclusion
* 🙏 Acknowledgments
* 🔮 Future Work
* 🛠️ How to Use

---

## 🌟 Overview

This project demonstrates how to build a house price prediction model using the California housing dataset and integrates MLflow to track experiments, hyperparameters, metrics, and model versions.

---

## 🛠️ Technologies Used

* Python
* scikit-learn
* Pandas
* Matplotlib
* MLflow
* California Housing Dataset (from `sklearn.datasets`)

---

## 🎯 Project Objectives

* Build a regression model to predict house prices.
* Perform hyperparameter tuning using GridSearchCV.
* Track experiments using MLflow.
* Register and version the best-performing model.
* Visualize and log evaluation metrics and artifacts.

---

## 🚀 Key Features

* Hyperparameter tuning using `GridSearchCV`
* MLflow tracking of parameters, metrics, and artifacts
* Model versioning and registry
* Evaluation visualization (MSE plot)

---

## 🛠️ Methodology

1. Load and preprocess the California housing dataset.
2. Split the dataset into training and test sets.
3. Define a hyperparameter grid and train the model with `GridSearchCV`.
4. Log hyperparameters, metrics, and artifacts using MLflow.
5. Register the best model.

---

## 🧠 Model Training and Evaluation

* **Model Used:** RandomForestRegressor
* **Metrics Tracked:** Mean Squared Error (MSE)
* **Best Parameters:** Tuned using 3-fold CV
* **Evaluation Artifact:** Saved and logged MSE bar plot

---

## 🎉 Conclusion

This project showcases a full ML pipeline with experiment tracking and model management using MLflow. It provides an effective approach to building and tracking regression models.

---

## 🙏 Acknowledgments

Thanks to the open-source community and the developers of MLflow and scikit-learn for the incredible tools that made this project possible.

---

## 🔮 Future Work

* Add other regressors (e.g., XGBoost, LightGBM)
* Include automated model comparison
* Deploy the registered model via REST API

---

## 🛠️ How to Use

1. Clone the repository.
2. Install required packages: `pip install -r requirements.txt`
3. Start MLflow UI: `mlflow ui`
4. Run the script: `python house_price_prediction.py`
5. Open `http://127.0.0.1:5000` in your browser to view the experiment logs.
