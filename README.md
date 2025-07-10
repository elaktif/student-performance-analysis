# student-performance-analysis

## Project Overview

This project looks at how student performance is affected by things like family background, lifestyle, and school support. It is part of the Code\:You Data Analysis Capstone.

I used two real datasets with information about students in Math and Portuguese classes. I compare how students do in both subjects and see how things like parents’ education, alcohol use, or internet access might affect grades.

---

## Datasets Used

### 1. Student Performance in Math

* **Source**:https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics?select=student_math_clean.csv
* **File**: `student-mat.csv`
* **Rows**: 395
* **Columns**: 33
* Includes things like age, gender, absences, family job, and grades.

### 2. Student Performance in Portuguese

* **Source**:https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics?select=student_portuguese_clean.csv
* **File**: `student-por.csv`
* **Rows**: 649
* **Columns**: 33
* Has similar structure as Math dataset.

---

## Project Structure

* `data/`: Dataset files
* `notebooks/`: Jupyter notebooks
* `images/`: Graphs and charts
* `requirements.txt`: List of Python packages
* `README.md`: This file

---

## Objective

To understand how things like family, school, and habits affect grades in Math and Portuguese classes. I also want to compare student results in both subjects.

---

 ## Data Dictionary (Some Columns)

| Column           | Description               |
| ---------------- | ------------------------- |
| `school`         | School name               |
| `sex`            | Gender (F/M)              |
| `age`            | Age                       |
| `address`        | Urban or rural            |
| `famsize`        | Family size               |
| `Pstatus`        | Parents together or apart |
| `Medu`           | Mother’s education        |
| `Fedu`           | Father’s education        |
| `Mjob`           | Mother’s job              |
| `Fjob`           | Father’s job              |
| `studytime`      | Weekly study time         |
| `failures`       | Past class failures       |
| `internet`       | Has internet at home      |
| `absences`       | Number of absences        |
| `G1`, `G2`, `G3` | Grades for each period    |

---

 ## Data Summary (coming soon)

I will include charts and summaries later as I finish the project.

---

## Data Sources

* [Student Performance – Math and Portuguese](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
* [Another Source with Student Data](https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics)
