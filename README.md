# 📊 Employee Sentiment Analysis

This repository contains an analysis of an **Employee Engagement & Satisfaction Survey Dataset**.  
The dataset includes responses from **138 employees** across **75 survey questions**, covering leadership, culture, role satisfaction, work environment, supervisor relationships, pay & benefits, and overall engagement.

The goal of this project is to **quantify employee sentiments**, uncover key factors influencing satisfaction, and provide insights into organizational strengths and weaknesses.

---

employee-sentiment-analysis/
│
├── data/
│   └── Book Original.xlsx        # Raw employee survey dataset
│
├── notebooks/
│   ├── combinedanalysis.ipynb    # Notebook with combined EDA & visualizations
│   ├── EmployeeSentiments0-1.ipynb # Notebook for sentiment encoding (0–1 scale)
├── README.md                     # Main project documentation


---

## 📌 Dataset Overview
- **Rows (Employees):** 138  
- **Columns (Survey Questions):** 75  
- **Key Categories Covered:**
  - Organization Leadership & Planning  
  - Culture & Communication  
  - Role in the Organization  
  - Work Environment  
  - Supervisor Relationship  
  - Employee Development  
  - Pay & Benefits  
  - Engagement & Overall Satisfaction  

---

## 🛠️ Methodology
1. **Data Preprocessing**
   - Cleaned raw survey data (removed unused columns, handled missing values).
   - Standardized Likert-scale responses (e.g., “Disagree Strongly”, “Agree Strongly”).
   - Encoded responses into numeric sentiment scores (0–1 scale).

2. **Exploratory Data Analysis (EDA)**
   - Examined employee demographics (age, experience, department).
   - Identified patterns in satisfaction & engagement levels.
   - Performed correlation analysis between organizational factors.

3. **Sentiment Mapping**
   Responses were mapped to a **0–1 sentiment scale**:
Disagree Strongly → 0.0
Somewhat Disagree → 0.25
Neutral → 0.5
Agree Somewhat → 0.75
Agree Strongly → 1.0
