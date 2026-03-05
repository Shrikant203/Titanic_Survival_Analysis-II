# 🚢 Titanic Survival Analysis – II

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns that influenced passenger survival. The analysis focuses on demographic, socio-economic, and family-related factors.

The goal of this task was to clean the dataset, perform statistical analysis, and visualize important relationships using Python.

---

## Objectives

• Clean the dataset and handle missing values  
• Analyze survival patterns based on age groups, embarkation ports, and family size  
• Visualize important insights using charts and heatmaps  

---

## Dataset

The dataset used is the **Titanic dataset**, which contains passenger information such as:

- Passenger ID
- Age
- Passenger Class
- Fare
- Family relationships
- Survival status

---

## Data Cleaning Steps

The following preprocessing steps were performed:

- Missing values in **Age** were filled using the **mean age**
- The **Cabin** column was removed due to excessive missing values
- A new feature **Family_Size** was created using `SibSp + Parch + 1`

---

## Analysis Performed

### 1️⃣ Survival Rate by Age Group
Passengers were categorized into age groups to analyze how survival probability varied across different age ranges.

### 2️⃣ Survival Rate by Embarkation Port
Passengers boarded the Titanic from three ports:

- Cherbourg (C)
- Queenstown (Q)
- Southampton (S)

The analysis shows differences in survival rates across these embarkation points.

### 3️⃣ Survival Rate by Family Size
Family size was calculated using the number of siblings/spouses and parents/children aboard. This helped determine whether traveling alone or with family affected survival chances.

---

## Visualizations

The following visualizations were created:

• Age Distribution Histogram  
• Correlation Heatmap  
• Survival Rate by Family Size (Bar Plot)

These visualizations helped identify patterns and relationships between variables in the dataset.

---

## Key Insights

• Most passengers were **young adults between 20–40 years old**.

• **Passenger class and fare** were strongly associated with survival probability.

• Passengers traveling with **small families (2–4 members)** had the highest survival rates.

• Passengers traveling alone or in very large families had lower survival chances.

---

## Tools and Technologies

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Jupyter Notebook

---

## Conclusion

This project demonstrates how exploratory data analysis can be used to extract meaningful insights from real-world datasets. By analyzing demographic and social factors, we can better understand patterns that influenced survival during the Titanic disaster.

---

## Future Improvements

• Apply Machine Learning models to predict survival  
• Perform feature importance analysis  
• Create more advanced visualizations and dashboards

---
