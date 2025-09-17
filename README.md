# 🏥 Insurance Dataset EDA  

This project is part of my **Data Analyst Learning Journey (Day 31)** where I performed **Exploratory Data Analysis (EDA)** on an Insurance dataset using Python, Pandas, Matplotlib, and Seaborn.  

---

## 📊 Dataset Information  

The dataset contains the following columns:  

- `age` → Age of the individual (years)  
- `sex` → Gender (male/female)  
- `bmi` → Body Mass Index (BMI = weight/height²)  
- `children` → Number of dependents  
- `smoker` → Smoker status (yes/no)  
- `region` → Residential area (northeast, northwest, southeast, southwest)  
- `charges` → Medical insurance costs  

---

## 🔍 EDA Performed  

### 🔹 Univariate Analysis  
- Age Distribution → Most people fall between 20–50 years.  
- BMI Distribution → Centered around 25–35, with some outliers.  
- Charges Distribution → Right-skewed → few very high charges.  
- Gender Count → Almost equal male vs female distribution.  
- Smoker Count → Majority non-smokers.  
- Region Count → Fairly balanced.  

### 🔹 Bivariate Analysis  
- Age vs Charges → Charges increase with age; smokers pay more.  
- BMI vs Charges → Higher BMI linked to higher charges, especially for smokers.  
- Charges by Smoker Status → Smokers pay significantly higher.  
- Charges by Gender → No major difference.  
- Charges by Region → Consistent across regions.  

### 🔹 Correlation Analysis  
- Strongest positive correlation: **Charges with Smoker, BMI, Age**.  
- Gender and Region → Minimal impact.  

---

## 📌 Key Insights  

- 🚬 **Smoking is the biggest factor impacting charges**.  
- 📈 **Age and BMI** also increase medical costs.  
- 🌍 **Gender and Region** have minimal effect on charges.  

---

## 🔧 Tools Used  

- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 💡 Learnings  

This project helped me strengthen my **EDA skills** and better understand how health and lifestyle factors influence **insurance costs**.  

---
### Name - Shashank Tiwari
### Date - 17-09-2025
