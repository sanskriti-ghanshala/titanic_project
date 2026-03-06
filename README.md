Titanic Dataset Analysis 🚢

Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python.
The main goal of this analysis is to understand the factors that affected passenger survival during the Titanic disaster.

Using data analysis and visualization techniques, we explore how different features such as gender, passenger class, and age influenced survival chances.

Dataset

The dataset used in this project is the Titanic dataset, which contains information about passengers such as:

Passenger class (Pclass)

Name

Age

Gender

Fare

Embarked port

Survival status

Technologies Used

The following Python libraries were used in this project:

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib – data visualization

Seaborn – statistical visualizations

Steps Performed
1. Data Loading

The dataset was loaded using Pandas and basic information about the dataset was explored.

2. Data Cleaning

Missing values in the dataset were handled:

Missing values in Age were replaced with the mean.

Missing values in Embarked were filled with the mode.

Cabin column was removed due to too many missing values.

3. Exploratory Data Analysis (EDA)

Different visualizations were created to analyze the data, including:

Survival count plot

Gender vs survival analysis

Passenger class vs survival

Age distribution

Correlation heatmap

4. Data Visualization

Graphs and plots were generated using Seaborn and Matplotlib to better understand relationships between features.

Key Insights

Some important observations from the analysis:

Female passengers had a higher survival rate compared to males.

Passengers traveling in 1st class had better survival chances than those in lower classes.

Most passengers were between 20 and 40 years old.

Conclusion

This analysis helps in understanding how different factors influenced survival during the Titanic disaster. It also demonstrates basic data cleaning, analysis, and visualization techniques in Python.
