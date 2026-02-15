#  Kaggle Titanic Competition – Machine Learning Project

This project is a machine learning solution developed for the **Kaggle Titanic Competition**.  
The goal is to predict passenger survival based on various features such as age, gender, ticket class, and fare.

---

##  Project Overview

The Titanic dataset is a classic binary classification problem where:

- **Target Variable:** `Survived`
- **Problem Type:** Binary Classification
- **Objective:** Predict whether a passenger survived or not

---

##  Dataset

The dataset includes:

- `train.csv` → Training data with survival labels  
- `test.csv` → Test data without labels  
- `submission.csv` → Final predictions for Kaggle submission  

Main features used:

- Passenger Class (`Pclass`)
- Sex (`Sex`)
- Age (`Age`)
- Fare (`Fare`)
- Embarked (`Embarked`)
- Family-related features (`SibSp`, `Parch`)

---

##  Data Preprocessing

Key preprocessing steps:

✔ Handling missing values (Age, Embarked, etc.)  
✔ Encoding categorical variables (`Sex`, `Embarked`)  
✔ Feature selection  
✔ Preparing training & test sets  

---

##  Model

A machine learning classification model was used:

- Model Type: **Random Forest Classifier**
- Purpose: Survival prediction

Why this model?

✔ Works well with tabular data  
✔ Handles non-linear relationships  
✔ Reduces overfitting compared to simple models  

---

##  Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help measure classification quality beyond simple accuracy.

---

##  Results

The model was trained on the Kaggle Titanic dataset and used to generate predictions:

✔ Survival predictions created  
✔ Submission file generated  
✔ Uploaded to Kaggle competition  

---

##  Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

##  How to Run

1️1) Clone the repository:

```bash
git clone https://github.com/doganaysesena11-gif/Kaggle-Competition-Titanic
```

2️) Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3️) Open the notebook:

```bash
jupyter notebook Titanic.ipynb
```

---

##  Project Goal

This project was developed as part of a machine learning learning journey, focusing on:

✔ Data preprocessing  
✔ Classification modeling  
✔ Evaluation metrics  
✔ Kaggle workflow  
