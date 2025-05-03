# Titanic Survival Prediction 🚢 | Machine Learning Project

This project is a classic binary classification problem focused on predicting the survival of passengers aboard the Titanic. Developed as part of **NeuroNexus Task 1**, it applies various supervised learning models on the widely used Titanic dataset from Kaggle, leveraging both data preprocessing and model evaluation techniques.

---

## 📌 Project Overview

The aim is to build multiple machine learning models that predict whether a passenger survived the Titanic disaster, using features such as age, gender, passenger class, family aboard, and fare.

The notebook includes:

- 📊 Data cleaning and preprocessing  
- 📈 Exploratory Data Analysis (EDA) with visualizations  
- 🧠 Model training using multiple ML algorithms  
- 🧪 Evaluation of model performance  
- 🔧 Hyperparameter tuning for optimization  

---

## 📁 Dataset

The dataset used is the **Titanic dataset from Kaggle**, which includes:

- `train.csv`: Training set to build models  
- `test.csv`: Test set for final evaluation  

Key features:

- `Pclass`: Passenger class (1st, 2nd, 3rd)  
- `Sex`: Gender  
- `Age`: Age in years  
- `SibSp`: Number of siblings/spouses aboard  
- `Parch`: Number of parents/children aboard  
- `Fare`: Passenger fare  
- `Embarked`: Port of embarkation (C, Q, S)

---

## 🛠️ Technologies Used

- **Python 🐍**  
- **Pandas & NumPy** for data manipulation  
- **Seaborn & Matplotlib** for visualizations  
- **Scikit-learn** for model training and evaluation  
- **LightGBM & XGBoost** for gradient boosting models  
- **Jupyter Notebook** for interactive analysis  

---

## 🤖 Models Implemented

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  

Each model is evaluated using:

- ✅ Accuracy score  
- 📉 Confusion matrix  
- 📄 Classification report (Precision, Recall, F1-score)  

---

## 📊 Sample Visualizations

- Survival rates by gender and passenger class  
- Age distribution of survivors vs non-survivors  
- Correlation heatmaps of numerical features  
- Box plots comparing fare distributions  
- Count plots for categorical variables like `Embarked`, `Pclass`, and `Sex`

---

## 🧪 Evaluation & Results

- The project compares multiple ML models side by side  
- Hyperparameter tuning (e.g., `n_estimators`, `max_depth`) is used for boosting models  
- Feature importance is visualized for models like Random Forest and XGBoost  
- Final model selected based on overall accuracy and F1-score on the test data  

---

## 🧠 Conclusion

This notebook successfully demonstrates an end-to-end supervised machine learning workflow, including data preprocessing, feature engineering, model evaluation, and improvement. It highlights how diverse algorithms can be used and compared for real-world binary classification tasks.
