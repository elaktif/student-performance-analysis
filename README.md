# student-performance-analysis
## 📌 Project Overview

This project investigates how academic performance is influenced by socio-demographic and lifestyle factors among high school students. It is part of the Data Analysis Capstone Project for Code:You.

Using two real-world datasets from Kaggle, we compare student outcomes in Math and Portuguese language courses.  
The project explores relationships between variables such as parental education, internet access, study time, and alcohol consumption, and their impact on students' final grades.

---


## 📊 Datasets Used
### 1. Student Performance in Math
- **Source**:  [Kaggle Link](https://www.kaggle.com/datasets/syria/2016-school-demographics-statistics)
- **File**: `student-mat.csv`  
- **Rows**: 395  
- **Columns**: 33  
- **Qualitative Variables**: gender, school, parent's jobs, address, internet access, etc.  
- **Quantitative Variables**: age, absences, G1-G3 grades, study time, etc.

### 2. Student Performance in Portuguese
- **Source**:  [Kaggle Link](https://www.kaggle.com/datasets/syria/2016-school-demographics-statistics) 
- **File**: `student-por.csv`  
- **Rows**: 649  
- **Columns**: 33  
- **Qualitative Variables**: similar to Math dataset  
- **Quantitative Variables**: same structure – includes grades, absences, age, etc.

Both datasets share many columns and can be merged for deeper analysis.

---

## 📁 Project Structure

- `data/`: CSV/Excel files from Kaggle
- `notebooks/`: Jupyter Notebook for data analysis
- `images/`: Visualizations
- `requirements.txt`: Python libraries
- `README.md`: Project documentation

---





## 🎯 Objective

To analyze how factors such as parental background, study time, alcohol use, and internet access influence students' academic success in Math and Portuguese subjects. The project will also compare overall performance across both subjects and highlight any trends or disparities.

---

## 📋 Data Dictionary

| Column        | Description |
|---------------|-------------|
| `school`      | Student's school (`GP` = Gabriel Pereira, `MS` = Mousinho da Silveira) |
| `sex`         | Student's gender (`F` = female, `M` = male) |
| `age`         | Student's age (numeric: from 15 to 22) |
| `address`     | Home address type (`U` = urban, `R` = rural) |
| `famsize`     | Family size (`LE3` = ≤ 3, `GT3` = > 3) |
| `Pstatus`     | Parent's cohabitation status (`T` = together, `A` = apart) |
| `Medu`        | Mother's education (0 = none, 1 = primary, 2 = 5th–9th grade, 3 = secondary, 4 = higher) |
| `Fedu`        | Father's education (same scale as `Medu`) |
| `Mjob`        | Mother's job (`teacher`, `health`, `services`, `at_home`, `other`) |
| `Fjob`        | Father's job (same options as `Mjob`) |
| `reason`      | Reason for choosing this school (`home`, `reputation`, `course`, `other`) |
| `guardian`    | Student's guardian (`mother`, `father`, `other`) |
| `traveltime`  | Home to school travel time (1 = <15 min, 2 = 15–30 min, 3 = 30–60 min, 4 = >60 min) |
| `studytime`   | Weekly study time (1 = <2 hrs, 2 = 2–5 hrs, 3 = 5–10 hrs, 4 = >10 hrs) |
| `failures`    | Number of past class failures (numeric: n if 1 ≤ n < 4, else 4) |
| `schoolsup`   | Extra educational support (`yes` or `no`) |
| `famsup`      | Family educational support (`yes` or `no`) |
| `paid`        | Extra paid classes within the course subject (`yes` or `no`) |
| `activities`  | Extra-curricular activities (`yes` or `no`) |
| `nursery`     | Attended nursery school (`yes` or `no`) |
| `higher`      | Intends to take higher education (`yes` or `no`) |
| `internet`    | Internet access at home (`yes` or `no`) |
| `romantic`    | In a romantic relationship (`yes` or `no`) |
| `famrel`      | Quality of family relationships (from 1 = very bad to 5 = excellent) |
| `freetime`    | Free time after school (1 = very low to 5 = very high) |
| `goout`       | Going out with friends (1 = very low to 5 = very high) |
| `Dalc`        | Workday alcohol consumption (1 = very low to 5 = very high) |
| `Walc`        | Weekend alcohol consumption (same scale as `Dalc`) |
| `health`      | Current health status (1 = very bad to 5 = very good) |
| `absences`    | Number of school absences (numeric) |
| `G1`          | First period grade (numeric: 0–20) |
| `G2`          | Second period grade (numeric: 0–20) |
| `G3`          | Final grade (numeric: 0–20) |

---

## 📈 Data Summary (coming soon)

Key statistics and insights derived from the datasets.

---



## 🔗 Data Sources

- [High School Performance & Demographics](https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics)
- [Student Performance – Math](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- [Student Performance – Portuguese](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
