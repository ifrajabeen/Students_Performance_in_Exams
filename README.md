# 🧠 Students Performance Data Analysis

This project analyzes the **"Students Performance in Exams"** dataset using Python to explore how factors like gender, parental education, lunch type, and test preparation affect students' scores in Math, Reading, and Writing.

---

## 📦 Dataset

- **Source:** [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Rows:** 1000
- **Columns:** 8
- **Features Include:**
  - Gender
  - Race/Ethnicity
  - Parental level of education
  - Lunch type
  - Test preparation course status
  - Math score
  - Reading score
  - Writing score

---

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas 📊
- NumPy 🔢
- Seaborn 📉
- Matplotlib 📈

---

## 📊 Analysis Performed

- Data loading & cleaning
- Null value inspection
- Data formatting & column normalization
- Group-wise aggregations (Gender, Education Level, etc.)
- Exploratory Data Analysis (EDA) with visualizations
- Correlation heatmap
- Created new feature: `average_score` (mean of Math, Reading, Writing)

---

## 🔍 Key Insights

- 🎯 **Female students** performed better **on average** than male students.
- 📈 Students who **completed the test preparation course** scored significantly **higher** than those who didn’t.
- 🧑‍🎓 Parental education level shows some effect on students’ writing scores.
- 📉 Strong **positive correlation** found among math, reading, and writing scores.

---

## 📂 Folder Structure
students-performance-analysis/
├── Students_Performance_in_Exams.ipynb
├── StudentsPerformance.csv
├── README.md

---

## 🚀 Future Work

- Build a predictive model to classify high vs low performing students
- Apply clustering to segment students based on performance
- Deploy dashboard using Streamlit or Flask

---

## 🙌 Acknowledgements

- Dataset by: [Kaggle - SPS](https://www.kaggle.com/spscientist)

