# 🚢 Titanic Survival Prediction using Machine Learning

> *A beginner-friendly yet professional machine learning project built using Google Colab and Python to predict passenger survival on the Titanic.*

---
⚠️ Note: If the notebook preview does not load on GitHub, please click "Download" or "Open in Colab".

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1czA112e6bKp0_SMSPez7yKLG2WVr5Aon?usp=sharing)



## 📌 Project Overview

The **Titanic Survival Prediction** project aims to predict whether a passenger survived the Titanic disaster based on personal and travel-related information. This is a classic binary classification problem and is widely used as an introductory machine learning project.

In this project, the complete machine learning workflow is followed:

* Data loading and understanding
* Data cleaning and preprocessing
* Feature engineering
* Model building and evaluation
* Visualization and interpretation of results

The project is designed to be **simple for beginners**, yet **accurate, well-structured, and visually appealing**.

---

## 🧠 Problem Statement

Given passenger details such as age, gender, ticket class, fare, and family information, build a machine learning model that can predict:

> **Did the passenger survive the Titanic disaster?**

Output:

* `1` → Survived
* `0` → Did not survive

---

## 📂 Dataset Information

* **Source:** Kaggle – Titanic Dataset- Provided by CODSOFT.
* **Link:** [https://www.kaggle.com/datasets/yasserh/titanic-dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
* **Type:** Structured CSV data

### Key Columns Used:

* `Pclass` – Passenger class
* `Sex` – Gender
* `Age` – Age of passenger
* `Fare` – Ticket fare
* `SibSp` – Siblings / spouse aboard
* `Parch` – Parents / children aboard
* `Embarked` – Port of embarkation
* `FamilySize` – Engineered feature (SibSp + Parch + 1)

---

## 🔧 Tools & Technologies Used

* **Python**
* **Google Colab** (Online notebook environment)
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models & evaluation
* **GitHub** – Project hosting and version control

---

## 🔍 Exploratory Data Analysis (EDA)

The following visual analyses were performed to better understand survival patterns:

* Survival count distribution
* Survival comparison by gender
* Survival comparison by passenger class
* Confusion matrix visualization

These visualizations help in identifying trends such as:

* Higher survival rate among females
* Higher survival rate in first-class passengers

---

## ⚙️ Data Preprocessing & Feature Engineering

Steps followed:

1. Handling missing values using median and grouped strategies
2. Encoding categorical variables (`Sex`, `Embarked`)
3. Creating a new feature `FamilySize`
4. Selecting the most impactful features for training
5. Splitting data into training and testing sets

This preprocessing significantly improves model performance.

---

## 🤖 Model Used

### Random Forest Classifier

* Chosen for better performance on structured data
* Handles non-linearity and feature importance well
* Reduces overfitting compared to single decision trees

### Model Configuration:

* Number of trees: 200
* Max depth: 8

---

## 📈 Model Performance

* **Accuracy:** ~85% – 90%
* Evaluation Metrics:

  * Accuracy Score
  * Precision
  * Recall
  * F1-Score
  * Confusion Matrix

The model performs well in distinguishing survivors and non-survivors.

---

# 🎥 Project Demonstration

A short demo video showcasing this project has been shared on **LinkedIn** as part of the internship submission using:  
`#codsoft #internship #datascience`

Link- https://www.linkedin.com/posts/aditi-dinesh_codsoft-machinelearning-datascience-activity-7416001846843990016-scX7?utm_source=share&utm_medium=member_android&rcm=ACoAAFNLxl8B9j-vCNkh1KQW2R58JwSXN10KbGk
---

## 📊 Sample Prediction

The model can predict survival for a new passenger based on input features such as:

* Passenger Class
* Gender
* Age
* Fare
* Family Size

This demonstrates real-world usability of the trained model.

---

## 🚀 How to Run This Project

1. Click **Open in Colab** (recommended)
2. Upload the dataset (`train.csv`) if not already available
3. Run cells sequentially from top to bottom

> ⚠️ If the notebook preview does not load on GitHub, please download the file or open it in Google Colab.

---

## 🌟 Future Improvements

* Try advanced models like XGBoost or Gradient Boosting
* Perform hyperparameter tuning for further accuracy
* Build a simple web app using Streamlit
* Add cross-validation and ROC curve analysis

---

## 👩‍💻 Author

**Aditi Dinesh**
B.Tech Student | Machine Learning Beginner

---

## 📌 Conclusion

This project demonstrates the complete machine learning pipeline in a clear, beginner-friendly manner while achieving strong accuracy and professional presentation. It serves as a solid foundation for learning and further exploration in data science and machine learning.

⭐ *If you found this project helpful, feel free to star the repository!*
