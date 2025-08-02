# 🚢 Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

This project explores the **Titanic dataset** from Kaggle using Python. It involves **data cleaning**, **exploratory data analysis**, and visualization to uncover insights into the factors affecting passenger survival.

---

## 📁 Dataset

- Dataset Used: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- File: `titanic.csv`

---

## 📌 Objectives

- Handle missing data and perform essential data cleaning.
- Explore relationships between different features and survival rate.
- Visualize trends and patterns using Seaborn and Matplotlib.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🧹 Data Cleaning Steps

- Filled missing values in `Age` and `Fare` using median.
- Dropped unnecessary columns: `PassengerId`, `Name`, `Ticket`.
- Converted `Sex` and `Embarked` columns to categorical type.
- Created new feature: `FamilySize = SibSp + Parch`.

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations and analysis included:
- ✔️ Overall survival count
- ✔️ Age distribution of passengers
- ✔️ Survival by gender (`Sex`)
- ✔️ Survival by passenger class (`Pclass`)
- ✔️ Survival by port of embarkation (`Embarked`)
- ✔️ Survival by family size
- ✔️ Correlation heatmap for numeric features
- ✔️ Violin plots for age vs survival by gender
- ✔️ Average fare comparison by class and survival

---

## 📈 Sample Visualizations

- `sns.countplot()`
- `sns.histplot()`
- `sns.violinplot()`
- `sns.heatmap()`
- `sns.barplot()`

---

## ✅ Outcome

The EDA reveals:
- Women had a higher survival rate than men.
- First-class passengers had a better chance of survival.
- Passengers with smaller families were more likely to survive.
- Embarked location and fare also influenced survival.


