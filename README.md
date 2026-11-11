# Titanic Dataset – Exploratory Data Analysis (EDA)

## 1. Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic passenger dataset. The main objective is to understand the dataset, identify missing values, explore passenger information, and discover patterns related to passenger survival.

The analysis was performed using Python in Google Colab with the help of data analysis and visualisation libraries.

## 2. Objectives

- Understand the structure and dimensions of the dataset.
- Identify missing values and duplicate records.
- Calculate summary statistics.
- Analyse passenger survival patterns.
- Explore the relationship between survival, gender, passenger class, age, and fare.
- Create visualisations to present the findings.

## 3. Dataset Information

**Dataset:** Titanic Training Dataset (`train.csv`)

- Total records: 891
- Total columns: 12

The dataset contains passenger details such as Passenger ID, Name, Sex, Age, Passenger Class, Ticket, Fare, Cabin, and Embarked.

## 4. Tools and Technologies Used

- **Python** – Programming language used for analysis.
- **Google Colab** – Environment used to write and execute Python code.
- **Pandas** – Data loading and manipulation.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualisation.
- **Seaborn** – Statistical charts and visualisations.

## 5. Data Analysis Performed

The following activities were performed:

1. Imported the dataset and explored its structure.
2. Checked column names, data types, and dataset dimensions.
3. Identified missing values and duplicate records.
4. Generated descriptive statistics.
5. Analysed survival counts.
6. Compared survival patterns by gender and passenger class.
7. Examined age and fare distributions.
8. Created a correlation heatmap and pairplot.

## 6. Visualisations Created

The project includes eight visualisations:

1. Survival Count
2. Survival Count by Gender
3. Survival Count by Passenger Class
4. Age Distribution
5. Age vs Fare Scatterplot
6. Correlation Heatmap
7. Age by Survival Boxplot
8. Pairplot of Selected Numerical Variables

## 7. Key Findings

- Out of 891 passengers, 342 survived and 549 did not survive.
- The overall survival rate was approximately 38.38%.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had the highest survival rate.
- Third-class passengers had the lowest survival rate.
- The average passenger age was approximately 29.70 years.
- The Age column contained 177 missing values, Cabin contained 687, and Embarked contained 2.
- No duplicate records were found.

## 8. Project Folder Structure

```text
Titanic_EDA_Submission/
│
├── README.md
│
├── code/
│   ├── Titanic_EDA.ipynb
│   └── Titanic_EDA.py
│
├── dataset/
│   └── train.csv
└── report/
    └── Titanic_EDA_Report.pdf
```

## 9. How to Run the Project

1. Download or extract the project folder.
2. Open `Titanic_EDA.ipynb` using Google Colab.
3. Upload `train.csv` when required.
4. Run the notebook cells in sequence.
5. View the generated charts and analysis results.

Alternatively, the Python script can be run in a Python environment with the required libraries installed.

## 10. Conclusion

The Titanic EDA project helped identify important patterns and relationships in passenger survival data. The analysis showed differences in survival rates based on gender and passenger class. Data visualisations and summary statistics helped present these findings clearly.

This project provided practical experience in data cleaning, exploratory data analysis, statistical summaries, and data visualisation using Python.

**Project Type:** Data Analytics – Exploratory Data Analysis  
**Dataset:** Titanic Training Dataset  
**Platform:** Google Colab
