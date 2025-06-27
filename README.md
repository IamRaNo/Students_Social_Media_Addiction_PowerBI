# 📊 Students' Social Media Addiction Analysis

## 🧠 Project Goal
To clean, analyze, and visualize a dataset related to **students' social media usage and its potential impact on mental health and academic performance**, using **Python** for data cleaning and **Power BI** for reporting.

---

## 🔍 Dataset Overview

- **Rows**: 705  
- **Columns**: 13 (7 numerical, 6 categorical)  
- **Target Age Group**: 18–24 years  
- **Gender Balance**: Approximately equal male and female participants  
- **Education Levels**: High School, Undergraduate, Graduate  
- **Geographical Scope**: Multiple countries  

---

## 📂 Data Quality Summary

- ✅ No null values  
- ✅ No duplicate records  
- ✅ No single-valued columns  
- 📉 `mental_health_score`: Range in data is 4–9 (expected 1–10)  
- 📉 `addicted_score`: Range in data is 2–9 (expected 1–10)  

---

## 🧹 Data Cleaning Steps (Using Python)

1. ✅ Renamed all column headers to **lowercase** and replaced underscores for consistent formatting.
2. ✅ Dropped the **`student_id`** column as it had no analytical value.
3. ✅ Verified absence of missing or duplicate values.
4. ✅ Exported the cleaned dataset for visualization in Power BI.

---

## 📊 Power BI Dashboard Structure

### 1️⃣ Overview Page
- Demographic breakdown (age, gender, academic level, country)
- Summary statistics on usage, addiction, and mental health

### 2️⃣ Time vs Usage
- Relationship between **average daily usage** and **sleep hours**
- Usage trends by platform, country, and academic level

### 3️⃣ Mental Health vs Academics
- Analysis of how social media impacts **mental health** and **academic performance**
- Scatter plots and trend visuals

### 4️⃣ Platform Influence Analysis *(New)*
- Impact of various platforms on **addiction and mental health**
- Platform usage distribution by gender and country

### 5️⃣ Relationship & Conflict Dynamics *(New)*
- Influence of **relationship status** and **social media conflicts** on addiction
- Analysis of emotional well-being and social interaction issues

---

## 🛠 Tools & Technologies Used

- **Python** (for data cleaning & preprocessing)
- **Pandas**, **NumPy**, **Jupyter Notebook**
- **Power BI** (for dashboard creation)
- **GitHub** (version control and project tracking)

---

