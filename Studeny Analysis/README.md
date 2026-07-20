# 📊 Student Performance Analysis using Python

## 📌 Project Overview

This project is part of my **Data Science and Data Analysis using Python Internship** at **Maincrafts Technologies**.

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Student Performance dataset using Python. The project follows the complete data analysis workflow:

**Load → Clean → Analyze → Visualize → Conclude**

---

## 📂 Dataset

**Dataset Name:** Student Performance Dataset

The dataset contains information about students such as:

- School
- Gender
- Age
- Study Time
- Family Background
- Absences
- Grades (G1, G2, G3)
- And several other academic and social attributes.

Total Records: **395**

Total Features: **33**

---

## 🎯 Project Objectives

- Load the dataset using Pandas.
- Explore the dataset structure.
- Check for missing values.
- Remove duplicate records.
- Perform statistical analysis.
- Create visualizations.
- Draw meaningful insights from the data.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib

---

## 📈 Analysis Performed

The following analyses were carried out:

### 1. Average Final Grade (G3)

Calculated the average final grade of all students.

### 2. High Performing Students

Counted the number of students scoring above 15 in the final examination.

### 3. Study Time vs Final Grade

Calculated the Pearson correlation coefficient to determine whether study time affects academic performance.

**Correlation:** `0.098`

This indicates a **very weak positive relationship** between study time and final grades.

### 4. Gender-wise Performance

Compared the average final grades of male and female students.

| Gender | Average G3 |
|---------|------------|
| Female | 9.97 |
| Male | 10.91 |

Male students achieved a slightly higher average final grade in this dataset.

---

## 📊 Visualizations

The project includes the following visualizations:

- Histogram of Final Grades
- Scatter Plot (Study Time vs Final Grade)
- Bar Chart (Average Final Grade by Gender)

---

## 🔍 Key Findings

- The dataset contains **395 students** and **33 features**.
- No missing values were found.
- No duplicate records were found.
- The average final grade (G3) was calculated.
- Students scoring above 15 were identified.
- Study time showed only a **very weak positive correlation (0.098)** with final grades.
- Male students had a slightly higher average final grade than female students.

---

## 📁 Project Structure

```

Student-Performance-Analysis/
│
├── student_analysis.ipynb
├── student-mat.csv
├── README.md
└── requirements.txt

```

---

## ▶️ How to Run

1. Clone this repository.

```

git clone https://github.com/YOUR_USERNAME/Student-Performance-Analysis.git

```

2. Navigate to the project folder.

```

cd Student-Performance-Analysis

```

3. Install the required libraries.

```

pip install -r requirements.txt

```

4. Launch Jupyter Notebook.

```

jupyter notebook

```

5. Open

```

student_analysis.ipynb

```

and run all the cells.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Working with Pandas
- Creating professional Jupyter Notebooks

---

## 👩‍💻 Author

**Sreya Nandi**

Data Science and Data Analysis using Python Intern

Maincrafts Technologies

---

## ⭐ Acknowledgement

This project was completed as part of the **Data Science and Data Analysis using Python Internship** at **Maincrafts Technologies**.
