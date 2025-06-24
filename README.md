# 🛳️ Titanic Project – Prodigy Infotech Task-02

This project performs **data cleaning** and **exploratory data analysis (EDA)** on the famous [Titanic dataset](https://www.kaggle.com/c/titanic/data). It generates insights about passenger survival patterns and exports professional visualizations into a single PDF file.

---

## 📌 Task Objective

> Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

---

## 📁 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- File used: `train.csv` (should be placed in the same directory as the script)

---

## ⚙️ Tools Used

- **Python**  
- **Jupyter Notebook / IPython**
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**

---

## 📊 What the Code Does

1. **Loads and displays** the Titanic dataset
2. **Cleans missing data** from:
   - Age (filled with median)
   - Embarked (filled with mode)
   - Drops Cabin (too many missing values)
3. **Adds a new feature**: `FamilySize = SibSp + Parch`
4. **Saves** cleaned data preview and statistics as
