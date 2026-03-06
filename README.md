Titanic Survival Analysis 🚢

Introduction

The Titanic disaster is one of the most well-known tragedies in history. The ship sank on April 15, 1912 after hitting an iceberg, leading to the loss of many lives. However, not all passengers had the same chances of survival. Factors such as gender, age, and passenger class played an important role in determining who survived.
This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to understand patterns and relationships in the data. The objective of this analysis is to explore the dataset, clean missing values, and visualize important features that may have influenced passenger survival.

Objective
The main objectives of this project are:
•	To explore the Titanic dataset and understand its structure
•	To clean and preprocess the dataset by handling missing values
•	To perform exploratory data analysis using Python
•	To visualize important patterns using graphs and charts
•	To identify factors that may have influenced survival chances

Dataset Description

The dataset contains information about passengers who were on board the Titanic. Some important columns in the dataset include:
•	Survived – Survival status (0 = No, 1 = Yes)
•	Pclass – Passenger class (1st, 2nd, 3rd)
•	Sex – Gender of passenger
•	Age – Age of passenger
•	SibSp – Number of siblings/spouses aboard
•	Parch – Number of parents/children aboard
•	Fare – Ticket fare
•	Embarked – Port of embarkation

Tools and Libraries Used

This project was implemented using Python and the following libraries:
•	Pandas – for data loading and manipulation
•	NumPy – for numerical operations
•	Matplotlib – for basic data visualization
•	Seaborn – for advanced visualizations

Data Cleaning
Before performing analysis, the dataset required preprocessing. The following steps were taken:
•	Missing values in the Age column were filled using the mean value.
•	Missing values in the Embarked column were filled using the most frequent value (mode).
•	The Cabin column contained too many missing values and was removed from the dataset.
These steps helped in making the dataset more suitable for analysis.

Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand patterns in the data. Several visualizations were created to examine relationships between different features.
The following analyses were performed:
•	Distribution of survival among passengers
•	Survival comparison based on gender
•	Survival comparison based on passenger class
•	Age distribution of passengers
•	Correlation heatmap to understand relationships between numerical features
These visualizations helped in identifying trends and patterns in the dataset.

Key Observations

From the analysis, some important observations were found:
•	Female passengers had a significantly higher survival rate compared to male passengers.
•	Passengers traveling in 1st class had better survival chances than those in 2nd and 3rd class.
•	Younger passengers had slightly better chances of survival compared to older passengers.
These findings suggest that social and economic factors played a role in survival during the disaster.

Conclusion

This project demonstrates how data analysis and visualization techniques can be used to explore historical datasets. By analyzing the Titanic dataset, we were able to identify patterns related to passenger survival and understand the influence of different features.
The project also highlights the importance of data cleaning, exploratory data analysis, and visualization in the field of Data Science.


