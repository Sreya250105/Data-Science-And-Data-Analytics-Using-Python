# 🚢 Titanic Data Analysis using Python

## 📌 Project Overview

This project analyzes the famous **Titanic Dataset** using Python. The objective is to explore the factors that influenced passenger survival by performing data cleaning, exploratory data analysis (EDA), and data visualization.

The project was completed as part of the **Data Science with Python Internship – Task 2**.

---

## 🎯 Objectives

- Load and explore the Titanic dataset.
- Handle missing values using appropriate techniques.
- Analyze survival patterns based on:
  - Gender
  - Passenger Class
  - Age Group
- Visualize the findings using Matplotlib.
- Draw meaningful conclusions from the analysis.

---

## 📂 Project Structure

```
Titanic-Data-Analysis/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── notebook/
│   └── Titanic_Data_Analysis.ipynb
│
├── images/
│   ├── survival_by_gender.png
│   ├── survival_by_passenger_class.png
│   └── passenger_age_distribution.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 🛠 Technologies Used

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📊 Data Cleaning

The following preprocessing steps were performed:

- Replaced missing values in the **Age** column with the median.
- Replaced missing values in the **Embarked** column with the mode.
- Replaced missing values in the **Cabin** column with **"Unknown"**.
- Verified that the dataset contains no missing values after cleaning.

---

## 📈 Analysis Performed

### 1. Survival Count by Gender
Compared the number of male and female passengers who survived.

**Finding:** Female passengers had a significantly higher number of survivors than male passengers.

---

### 2. Survival Count by Passenger Class
Compared survivor counts across First, Second, and Third Class.

**Finding:** First Class had the highest number of survivors, followed by Third Class and Second Class.

---

### 3. Survival Count by Age Group
Grouped passengers into different age categories and analyzed survivor counts.

**Finding:** Young Adults had the highest number of survivors, while Seniors had the fewest.

---

## 📉 Visualizations

The project includes the following visualizations:

- Bar Chart: Survival Count by Gender
- Bar Chart: Survival Count by Passenger Class
- Histogram: Distribution of Passenger Ages

---

## 📋 Results

- Female passengers had better survival outcomes than male passengers.
- Passenger class influenced survival, with First Class showing the highest number of survivors.
- Most survivors belonged to the Young Adult age group.
- The majority of passengers were between 20 and 40 years old.

---

## ▶️ How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/your-username/Titanic-Data-Analysis.git
```

2. Navigate to the project folder.

```bash
cd Titanic-Data-Analysis
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the notebook.

```bash
jupyter notebook
```

5. Run **Titanic_Data_Analysis.ipynb**.

---

## 📁 Dataset

- **Dataset:** Titanic Dataset
- **Source:** Kaggle

https://www.kaggle.com/c/titanic/data

---

## 📄 License

This project is intended for educational and internship purposes.

---

## 👩‍💻 Author

**Sreya Nandi**

B.Tech Computer Science Engineering (CSE)

GitHub: https://github.com/Sreya250105

LinkedIn: https://linkedin.com/in/sreya-nandi-696341363
