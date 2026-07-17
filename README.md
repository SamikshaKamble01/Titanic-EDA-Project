# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview 

This project performs Exploratory Data Analysis (EDA) on the Titanic Dataset using Python. The goal is to understand passenger data, identify patterns, handle missing values, detect outliers, analyze relationships between variables, and derive meaningful insights related to survival rates.

## 🎯 Objectives

* Understand the dataset structure
* Perform data cleaning and preprocessing
* Analyze missing values
* Generate descriptive statistics
* Create visualizations for better insights
* Detect outliers using statistical methods
* Analyze correlations between features
* Test hypotheses related to passenger survival

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

## 📊 Dataset Features

| Feature     | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique Passenger ID               |
| Survived    | Survival Status (0 = No, 1 = Yes) |
| Pclass      | Passenger Class                   |
| Name        | Passenger Name                    |
| Sex         | Gender                            |
| Age         | Passenger Age                     |
| SibSp       | Number of Siblings/Spouses Aboard |
| Parch       | Number of Parents/Children Aboard |
| Ticket      | Ticket Number                     |
| Fare        | Ticket Fare                       |
| Cabin       | Cabin Number                      |
| Embarked    | Port of Embarkation               |

## 🔍 Exploratory Data Analysis

### Data Inspection

* Dataset Shape
* Data Types
* Missing Values Analysis

### Statistical Analysis

* Mean
* Median
* Standard Deviation
* Skewness
* Kurtosis

### Data Visualization

* Histogram
* Count Plot
* Box Plot
* Heatmap
* Pair Plot

### Outlier Detection

* Z-Score Method
* Interquartile Range (IQR) Method

### Correlation Analysis

* Pearson Correlation
* Spearman Correlation

## 📈 Key Findings

* Female passengers had a higher survival rate than male passengers.
* First-class passengers were more likely to survive.
* Age influenced survival probability.
* Fare showed a positive relationship with survival.
* Several outliers were detected in the Fare column.

## ✅ Hypotheses Tested

### H1: Higher-class passengers had better survival rates.

**Result:** Confirmed ✅

### H2: Age impacted passenger survival.

**Result:** Confirmed ✅


## 💡 Recommendations

* Create a Family Size feature using `SibSp` and `Parch`.
* Perform advanced feature engineering.
* Apply machine learning models for survival prediction.
* Conduct deeper analysis on passenger demographics.


## 📂 Repository Structure

```text
Titanic-EDA-Project/
│
├── Titanic_EDA.ipynb
├── titanic.csv
├── README.md
└── requirements.txt
```

## OUTPUT
<img width="1456" height="695" alt="Screenshot 2026-06-17 152420" src="https://github.com/user-attachments/assets/0b4fbb59-771b-4280-b1cd-beed273938a0" />
<img width="1368" height="713" alt="Screenshot 2026-06-17 152354" src="https://github.com/user-attachments/assets/c10e67a7-b1ff-4feb-8b25-97829f6cb945" />
<img width="1270" height="743" alt="Screenshot 2026-06-17 152324" src="https://github.com/user-attachments/assets/aa45c5b3-0774-48ac-b20c-91676465e9df" />

## 👩‍💻 Author

**Samiksha Kamble**


