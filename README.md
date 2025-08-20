# 📊 Exploratory Data Analysis of County Health Rankings

A comprehensive analysis of the **"County Health Rankings"** dataset to uncover insights into public health across the United States.

---

## 📝 Overview
This project provides a detailed **Exploratory Data Analysis (EDA)** of factors influencing public health across various U.S. counties.  
The process involves:
- Rigorous data cleaning
- Univariate and bivariate analysis
- Visualization of key relationships between health indicators

---

## 💾 Dataset
The analysis is based on the **`County_Health_Rankings.csv`** dataset, which aggregates public health indicators from counties across the United States.  
Each row represents a specific health measure for a county during a defined time period.

**Key Data Columns:**
- **State / County:** The specific state and county  
- **Year span:** The time frame of the data collection  
- **Measure name:** The health indicator being measured (e.g., Children in poverty, Adult smoking, Violent crime rate)  
- **Numerator:** The number of observed cases for the indicator  
- **Denominator:** The total population relevant to the indicator  
- **Raw value:** The calculated value of the measure (rate or percentage)  

---

## 🛠️ Technology Stack & Libraries
This project leverages the following Python libraries for data analysis and visualization:

- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `missingno`

---

## 📈 Analysis Workflow
The analysis is structured into two main phases:

### 1️⃣ Data Cleaning and Preprocessing
- **Missing Value Imputation:**  
  Analyzed missing data patterns and imputed numerical values using the **median** to minimize the effect of outliers.  

- **Duplicate Removal:**  
  Identified and eliminated duplicate records to ensure data integrity.  

- **Data Type Correction:**  
  Converted columns to appropriate data types for efficient analysis.  

---

### 2️⃣ Exploratory Data Analysis (EDA)
- **Univariate Analysis:**  
  Examined the distribution of individual numerical features using histograms and boxplots, revealing that most were highly skewed.  

- **Outlier Management:**  
  Applied a **log transformation** to skewed variables to normalize their distributions and reduce the impact of extreme values.  

- **Bivariate Analysis:**  
  Investigated relationships between variable pairs, highlighting a strong correlation between **Numerator** and **Denominator**.  

- **Correlation Analysis:**  
  Generated a **correlation matrix** to quantify the strength and direction of linear relationships between key numerical variables.  

---

## 💡 Key Findings & Conclusion
- **Population size** is a dominant factor influencing many health indicators.  
- The application of **log transformation** was crucial for normalizing data distributions, thereby enhancing the reliability of the statistical analysis.  
- The project successfully identified different patterns of missing data (**MAR, MCAR, MNAR**) and demonstrated an effective workflow for cleaning, analyzing, and deriving insights from a complex public health dataset.  

