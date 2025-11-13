# 🎓 Student Performance Factor — Exploratory Data Analysis (EDA)

## 📘 Project Overview
This project explores factors that influence students’ exam performance using data-driven insights.  
Through exploratory data analysis (EDA), the project identifies the key academic and socio-economic variables affecting student outcomes and provides actionable recommendations for improving overall performance.

---

## 💼 Business Problem
Educational institutions often struggle to identify why some students perform better than others.  
The main objectives of this project are:
- To analyze factors (attendance, study time, parental involvement, etc.) that influence student performance.
- To discover patterns and correlations between socio-economic and behavioral attributes.
- To provide recommendations for educators and parents to help improve students’ academic outcomes.

---

## 📊 Dataset
**File:** `Dataset.csv`  

**Description:**  
The dataset contains various features related to student demographics, study behavior, and academic results.  
- Hours Studied  
- Attendance
- Parental_Involvement
- Access_to_Resources
- Extracurricular_Activities
- Sleep_Hours
- Previous_Scores
- Motivation_Level
- Internet_Access
- Tutoring_Sessions
- Family_Income
- Teacher_Quality
- School_Type
- Peer_Influence
- Learning_Disabilities
- Parental_Education_Level
- Distance_from_Home
- Gender
- Exam_Score
---

## 🧠 Technologies Used
- **Jupyter Notebook**

### Python Libraries:
- `pandas` — Data manipulation and analysis  
- `numpy` — Numerical operations  
- `matplotlib` & `seaborn` — Data visualization  
- `scikit-learn` — Machine learning (for correlation and prediction)  

---

## ⚙️ Workflow

1. **Data Loading**
   - Import dataset using `pandas.read_csv()`.
   - Inspect the structure with `head()`, `info()`, and `describe()`.

2. **Data Cleaning**
   - Handle missing or null values.
   - Convert incorrect data types.
   - Remove duplicates.
   - Standardize categorical values.

3. **Exploratory Data Analysis (EDA)**
   - Univariate analysis using histograms and boxplots.
   - Bivariate analysis using correlations and pair plots.
   - Identify outliers using IQR or boxplot visualization.
   - Analyze relationships between features.

---

## 🏆 Results & Recommendations

- Encourage **consistent attendance** through attendance-based monitoring.  
- Motivate students to **dedicate more weekly study hours**.  
- Involve **parents** more through workshops or engagement programs.  
- Provide **targeted tutoring sessions** for low-performing students.  
- Use **predictive analysis** to identify students at risk of poor performance early.

---

## 🧩 How to Run Step-by-Step

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/komal9918/Student_Performance_Factor_python-EDA-
