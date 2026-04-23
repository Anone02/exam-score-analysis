# 📊 Exam Score Analysis

## 📌 Overview

This project explores student exam performance data to uncover patterns, distributions, and key factors influencing academic scores. The analysis focuses on **math, reading, and writing scores** across different student groups.

---

## 🎯 Objectives

* Analyze score distribution across different groups
* Identify factors affecting student performance
* Compare performance based on:

  * Gender
  * Parental education level
  * Lunch type
* Generate insights using data visualization and preprocessing

---

## 🗂️ Dataset

The dataset is adapted from the **Students Performance dataset** available on Kaggle.

### Features:

* `gender` → student gender
* `group` → ethnicity group
* `edukasi_ortu` → parental education level
* `lunch` → lunch type (standard / free-reduced)
* `math_score` → math exam score
* `reading_score` → reading exam score
* `writing_score` → writing exam score

---

## 🧪 Data Preprocessing

Steps performed:

* Checked for missing values (none found)
* Converted data types where necessary
* Encoded categorical variables using:

  * Label Encoding
  * One-Hot Encoding
* Feature scaling using StandardScaler
* Train-test split for modeling preparation

---

## 📈 Exploratory Data Analysis (EDA)

The following visualizations were created:

* Histogram of math scores by group
* Bar chart of student distribution across groups
* Pie chart of group proportions
* Line and scatter plots for group comparisons
* Heatmap 

---

## 🔍 Key Insights

* 📌 Average math score is around **66**, indicating moderate performance overall
* 📌 Students with **standard lunch** tend to perform better
* 📌 Certain groups show higher concentration of students (e.g., Group C)
* 📌 High-performing students (score ~100) are relatively rare but present across multiple groups

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn

---

## 📁 Project Structure

```
exam-score-analysis/
│── analysis.ipynb
│── README.md
│── data/ 
```

---

## 🚀 How to Run

1. Clone this repository:

```
git clone https://github.com/your-username/exam-score-analysis.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook:

* Open `analysis.ipynb` using Jupyter Notebook or VS Code

---

## 📌 Future Improvements

* Add machine learning model for score prediction
* Improve visualization (more advanced plots)
* Perform correlation analysis between features
* Deploy as interactive dashboard

---

## 💡 Conclusion

This project demonstrates basic data analysis and preprocessing techniques applied to an educational dataset. It highlights how simple exploratory analysis can reveal meaningful insights about student performance.

---

## 📬 Contact

Feel free to reach out for collaboration or feedback!
