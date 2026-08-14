# 📊 Global Cybersecurity Threat Analysis

![Global Cybersecurity Threat Analysis](Images/cybersecurity_thumbnail.png)

---

## 📊 Project Overview:

This project presents an Exploratory Data Analysis (EDA) of global cybersecurity incidents from **2015–2024**.

The analysis explores:

* Cyberattack types and sources
* Target industries
* Security vulnerabilities
* Financial losses
* Number of affected users
* Defense mechanisms
* Incident resolution time
* Trends and patterns across countries and years

---

## 📊 View Project:

🔹 **Option 1: Explore Interactive Streamlit Dashboard (Recommended)**

* Live Dashboard: *Coming soon*
* Interactive dashboard with:

  * Dynamic filters
  * Interactive visualizations
  * Cyberattack analysis
  * Financial loss and affected-user analysis
  * Security vulnerability insights
  * Key findings

🔹 **Option 2: Browse the GitHub Repository**

* GitHub Repository: *Coming soon*
* Includes:

  * EDA notebook
  * Streamlit application
  * Dataset
  * Analysis workflow
  * Project documentation

---

## 📊 Objectives:

* Analyze global cybersecurity incidents from **2015–2024**
* Identify the most common attack types and sources
* Analyze industries most affected by cyberattacks
* Examine common security vulnerabilities
* Analyze financial losses and affected users
* Study the use of different defense mechanisms
* Analyze incident resolution time
* Identify important cybersecurity patterns and trends

> Note: Objectives may be refined or updated as the analysis progresses and new patterns are identified.

---

## 📊 Dataset Information:

* **Source:** Kaggle
* Dataset Link: Kaggle Dataset
* **Time Period:** 2015–2024
* **Rows:** 3,000
* **Columns:** 10
* **File Used:** `global_cybersecurity_threat_dataset.csv`

### Key Features:

* `Country` **(10 unique)**
* `Year` **(10 unique)**
* `Attack Type` **(6 unique)**
* `Target Industry` **(7 unique)**
* `Financial Loss (in Million $)`
* `Number of Affected Users`
* `Attack Source` **(4 unique)**
* `Security Vulnerability Type` **(4 unique)**
* `Defense Mechanism Used` **(5 unique)**
* `Incident Resolution Time (in Hours)`

### Data Types:

* **6 categorical columns**
* **3 integer columns**
* **1 float column**

---

## 📊 Tools & Libraries Used:

* **Python**
* **Pandas:** Data inspection and manipulation
* **Scipy:** Statistical Analysis
* **NumPy:** Numerical operations
* **Matplotlib:** Data visualization
* **Seaborn:** Statistical visualization
* **Streamlit:** Interactive dashboard

---

## 📊 Analytics Workflow:

```text
Raw Dataset
     ↓
Data Import
     ↓
Data Inspection
     ↓
Data Cleaning & Transformation
     ↓
Exploratory Data Analysis (EDA)
     ↓
Charts & Visualizations
     ↓
Interactive Streamlit Dashboard
```

---

## 📊 Data Inspection:

🔹 Key Findings:

- Dataset contains 3,000 records and 10 columns covering 2015–2024.
- The dataset contains 6 categorical and 4 numerical features.
- No missing values and no duplicate rows were found.
- No negative or invalid numerical values were found.
- No significant outliers were found in Financial Loss, Number of Affected Users, or Incident Resolution Time columns.
- Overall, the dataset appears clean, balanced, and well-structured, suggesting it may be synthetically generated or carefully curated.
- Despite this, the dataset is suitable for EDA and identifying cybersecurity trends and patterns.


## 📊 Data Cleaning & Transformation:

Since the dataset is already clean, no major data cleaning is required.

The next step will be to:

* Create a copy of the raw dataset to **preserve the original data and avoid accidental changes**
* Work only on the **copied dataset** for further modifications
* Perform necessary feature engineering and data transformations
* Prepare the dataset for EDA

