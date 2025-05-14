# student-exam-performance-analysis
Data analysis of student exam performance by demographic and preparation factors.
# Student Exam Performance Analysis

## Project Overview
This project explores how various factors — such as gender, parental education level, lunch type, and test preparation — affect student exam performance in math, reading, and writing.

It includes data cleaning, exploratory data analysis (EDA), statistical testing, visualizations, and actionable recommendations.

---

## Dataset
- Source: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- 1000 student records
- Features: gender, parental level of education, lunch type, test prep course, scores in math, reading, and writing

---

## Objectives
- Understand score distributions by subject
- Analyze the impact of demographic and preparation factors
- Test hypotheses statistically
- Offer data-driven recommendations for educational interventions

---

## Key Findings
- Students who completed test prep scored significantly higher across all subjects.
- Female students outperformed males in reading and writing.
- Strong correlations exist between all three exam scores.

---

## Techniques Used
- Python (Pandas, Seaborn, Matplotlib, SciPy)
- Data cleaning & transformation
- Exploratory Data Analysis (EDA)
- T-tests for statistical significance
- Correlation heatmaps

---

## Tools
- Jupyter Notebook
- Python 3.13.3
- Git/GitHub

---

## Recommendations
1. Invest in test prep programs for all students.
2. Provide reading/writing support especially for male students.
3. Use subject performance trends to predict and support students at risk.

---

## Project Structure
```bash
├── student-performance-analysis/
│   ├── data/
│   │   └── StudentsPerformance.csv
│   ├── notebooks/
│   │   └── student_exam_analysis.ipynb
│   ├── README.md
│   └── visuals/
│       └── score_distributions.png
