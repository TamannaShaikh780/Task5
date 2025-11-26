Task 5 – Exploratory Data Analysis (EDA)
Data Analyst Internship – Task Submission
Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic Dataset using Python.
The goal is to explore the data, identify trends, find patterns, and draw meaningful insights using visual and statistical techniques.

Files Included
File	Description
Task5_EDA.ipynb	(Jupyter Notebook containing all analysis & visualizations)
Task5_EDA.pdf	(PDF export of the EDA notebook)
train.csv	(Titanic dataset used for analysis)
README.md	(Project documentation)

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

EDA Steps Performed
1.Data Loading & Inspection
Loaded the Titanic dataset using Pandas
Displayed first few rows (df.head())
Checked shape, data types, missing values using:
.shape
.info()
.describe()
.value_counts()
2.Univariate Analysis
Histogram of Age
Countplot of Gender
Countplot of Survival
Observations about distribution & class imbalance
3️.Bivariate Analysis
Survival by Gender
Survival by Passenger Class
Age vs Fare (scatterplot)
4️. Multivariate Analysis
Pairplot for Age, Fare, Pclass, Survived
Correlation Heatmap for numeric columns
5️. Additional Plots
Boxplot: Age vs Survival

Key Insights
Females had a much higher survival rate than males.
1st class passengers survived more, while 3rd class had the lowest survival.
Higher fare = higher survival chance, indicating wealth/socioeconomic status mattered.
Age has missing values; Cabin has many missing values.
Majority of passengers were in 3rd class, and most of them did not survive.
Younger passengers had slightly higher survival probability.

Conclusion
The analysis shows strong evidence that survival on the Titanic was influenced by gender, passenger class, fare, and age.
Women and first-class passengers had the highest chance of survival.
This EDA demonstrates the ability to understand data, explore patterns, and communicate findings clearly.
