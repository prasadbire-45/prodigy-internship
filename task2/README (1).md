# Task-02: Exploratory Data Analysis on Titanic Dataset

## 📌 Objective
The objective of this task is to perform **Exploratory Data Analysis (EDA)** on the **Titanic dataset** to understand the factors that influenced passenger survival using data cleaning, visualization, and statistical analysis.

---

## 📊 Dataset
- **Name:** Titanic Dataset
- **File:** `titanic.csv`
- **Rows:** 891
- **Columns:** 12
- **Target Variable:** `Survived`
  - `0` → Did not survive  
  - `1` → Survived  

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Handled missing values:
  - Filled missing `Age` values using the median
  - Filled missing `Embarked` values using the mode
- Dropped the `Cabin` column due to excessive missing values
- Removed duplicate records
- Encoded `Sex` column (`male = 0`, `female = 1`)
- Created a new feature: **FamilySize**

---

## 📈 Exploratory Data Analysis
The following visualizations and analyses were conducted:
- Survival count distribution
- Gender distribution
- Age distribution
- Survival comparison by gender
- Survival comparison by passenger class
- Age vs survival analysis
- Survival based on family size
- Correlation heatmap for numerical features

---

## 🔍 Key Insights
- Females had a significantly higher survival rate than males
- Passengers in **1st class** had better survival chances compared to 3rd class
- Younger passengers were more likely to survive
- Passengers with **smaller families** showed higher survival rates

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
Task 02/
├── titanic.csv
├── task_02.ipynb
└── README.md


---

## ✅ Conclusion
This analysis provides valuable insights into survival patterns aboard the Titanic and demonstrates how exploratory data analysis and visualization can help uncover hidden trends in real-world datasets.

---

## 👨‍💻 Author
**Om Dhaigude**  
Prodigy InfoTech – Data Science Internship
