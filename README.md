# 📊 Student Performance Dataset Analysis

## 📌 Overview
This project is a complete **Exploratory Data Analysis (EDA)** of the **Student Performance** dataset from the UCI Machine Learning Repository.  
The objective is to investigate how various demographic, social, and lifestyle factors influence students’ academic performance and provide **data-driven recommendations** for improvement.

---

## 📂 Dataset Information
- **Source:** UCI Machine Learning Repository – Student Performance  
- **Subject:** Mathematics course performance in Portuguese secondary schools  
- **Records:** 395 students  
- **Features:** 33 attributes (grades, demographics, lifestyle, and school-related details)  
- **Target Variable:** `G3` (Final Grade)  

---

## ⚙️ Project Workflow

### 1. Data Loading & Setup
- Imported libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `missingno`
- Loaded dataset into a pandas DataFrame

### 2. Data Typing & Memory Optimization
- Converted column data types to reduce memory usage
- Downcasted numerical columns to prevent overflow

### 3. Missing Data Analysis
- Visualized missing data with `missingno`
- Confirmed dataset completeness

### 4. Data Cleaning
- Removed redundant or irrelevant data
- Standardized column names and formats

### 5. Feature Engineering
- Created new variables for deeper insights (e.g., total grades, combined performance metrics)

### 6. Encoding Categorical Variables
- Applied **Binary Encoding** and **One-Hot Encoding**

### 7. Data Visualization & Insights
- Descriptive statistics
- Correlation heatmaps for identifying strong predictors of performance
- Factor-by-factor analysis: parental education, study time, gender differences, school type, urban vs. rural, alcohol consumption, absences, age

---

## 📊 Key Insights
- **Parental Education Matters:** Higher parental education is linked to better student grades.  
- **Study Time Is Critical:** Longer study time improves performance but benefits plateau after a certain point.  
- **Absences Negatively Impact Grades:** High absence counts strongly correlate with lower final grades.  
- **Lifestyle Choices Influence Results:** Higher alcohol consumption is associated with reduced academic performance.  
- **Gender Differences Exist:** Female students slightly outperform male students.  
- **School Type & Location Play a Role:** Urban schools generally outperform rural ones.  

---

## ✅ Recommendations
- **Parental Engagement Programs:** Encourage parental involvement, especially for families with lower educational backgrounds.  
- **Encourage Consistent Study Habits:** Provide workshops on study techniques and time management.  
- **Reduce Absenteeism:** Implement attendance tracking and interventions for high-absence students.  
- **Health & Lifestyle Awareness:** Promote awareness of the negative effects of excessive alcohol consumption.  
- **Targeted Support for At-Risk Groups:** Offer tutoring and mentorship for students from rural or low-resource schools.  

---

## 📦 Requirements
```bash
pandas
numpy
matplotlib
seaborn
missingno
