# titanic-survival-analysis

**Data Science with Python Internship – Task 2**

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand survival patterns based on **gender**, **passenger class**, and **age groups**.  
The analysis is implemented in Python using Pandas, NumPy, Matplotlib, and Seaborn.

---

## 📌 Project Objectives

### 1️⃣ Data Cleaning
- Filled missing **Age** values using **median** (as required in Task 2)
- Dropped **Cabin** column due to excessive missing values
- Handled missing values in **Embarked**

### 2️⃣ Feature Engineering
- Created **AgeGroup** categories:
  - Child (0–12)
  - Teen (13–18)
  - Young Adult (19–30)
  - Adult (31–50)
  - Senior (51+)

### 3️⃣ Analysis Questions
The notebook answers the following:

- **A. Who survived more — males or females?**
- **B. Did passenger class affect survival?**
- **C. What is the survival rate across different age groups?**

### 4️⃣ Visualizations
The notebook includes:
- Histogram of passenger ages  
- Survival rate by **Gender** (Bar plot)  
- Survival rate by **Passenger Class** (Bar plot)  
- Survival rate by **Age Group** (Bar plot)


