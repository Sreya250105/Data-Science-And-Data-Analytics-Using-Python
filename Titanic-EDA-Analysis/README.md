# Titanic Mini Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project was completed as part of the **Data Science & Analysis with Python Internship** at **Maincrafts Technologies**.

The objective of this project is to perform a **Mini Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The project includes data cleaning, exploratory analysis, visualization, and interpretation of survival patterns among Titanic passengers.

---

## 🎯 Objectives

- Load and explore the Titanic dataset.
- Identify and handle missing values.
- Perform exploratory data analysis (EDA).
- Analyze survival patterns using different passenger features.
- Create meaningful visualizations.
- Draw insights from the dataset.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about **891 passengers**, including:

- Passenger ID
- Passenger Class (Pclass)
- Name
- Sex
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Ticket
- Fare
- Cabin
- Embarked
- Survival Status

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Filled missing values in the **Age** column using the mean age.
- Filled missing values in the **Embarked** column using the most frequent value (mode).
- Dropped the **Cabin** column because it contained a large number of missing values.
- Verified that no missing values remained in the cleaned dataset.

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

### Analysis 1
**Survival Rate by Age Group**

- Grouped passengers into different age categories.
- Compared survival rates across age groups.

### Analysis 2
**Survival Rate by Embarkation Port**

- Compared survival rates based on passengers' embarkation ports.

### Analysis 3
**Survival Rate by Family Size**

- Created a new **FamilySize** feature.
- Analyzed the relationship between family size and survival rate.

---

## 📈 Visualizations

The following visualizations were created:

- Age Distribution (Histogram)
- Correlation Heatmap
- Survival Rate by Family Size (Bar Chart)

---

## 🔍 Key Findings

- Children had the highest survival rate among all age groups.
- Senior passengers had the lowest survival rate.
- Passengers embarking from **Cherbourg (C)** showed the highest survival rate.
- Small families had better survival rates than passengers travelling alone or in very large families.
- Passenger Class and Fare showed meaningful relationships with survival.

---

## 📁 Project Structure

```
Titanic-EDA-Analysis/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── notebook/
│   └── Titanic_EDA_Task3.ipynb
│
├── images/
│   ├── age_distribution.png
│   ├── correlation_heatmap.png
│   └── survival_by_family_size.png
│
├── screenshots/
│   ├── notebook_preview.png
│   └── output_preview.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Titanic-EDA-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Titanic-EDA-Analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```
notebook/Titanic_EDA_Task3.ipynb
```

Run all cells sequentially.

---

## 📸 Sample Outputs

The generated visualizations are available in the **images/** folder.

---

## 👩‍💻 Author

**Sreya Nandi**

B.Tech Computer Science Engineering Student

Data Science & Analysis with Python Intern

---

## ⭐ Acknowledgement

This project was completed as part of the **Data Science & Analysis with Python Internship** offered by **Maincrafts Technologies**.

---

## 📜 License

This project is licensed under the **MIT License**.
