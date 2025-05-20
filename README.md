# Exploratory data analysis with Python 

Overview :
Exploratory Data Analysis (EDA) with Python is a crucial step in any data science or analytics project. It helps you understand the data’s structure, detect patterns, spot anomalies, and formulate hypotheses. Here's a structured guide with code examples for doing EDA using Python:
import pandas as pd        # Data manipulation
import numpy as np         # Numerical operations
import matplotlib.pyplot as plt  # Plotting
import seaborn as sns      # Advanced visualization

# Basic Info & Summary
- df.info()        # Overview of dataset (non-null counts, types)
- df.describe()    # Summary stats for numeric columns
- df.shape         # Rows and columns
- df.columns       # Column names
- df.isnull().sum()  # Missing values per column

# Data set:
You can download and read about the data set by going through this link https://www.kaggle.com/c/titanic/data
This data set consists Information about the passengers of RMS Titanic ship And also have info about is that particular passenger is survived in that disaster or not. For every individual person we have information about —

1.	Passenger Id- Id number of passenger in data set
2.	Name- Name of the passenger
3.	Survival- Person survived or not ( 0 for No & 1 for Yes)
4.	Pclass- With what class of ticket that passenger was travelling.
5.	sex- Male Or Female
6.	Age- Age of the person in Years
7.	Sibsp- Number of siblings / spouses on the Titanic
8.	parch- Number of parents / children on the Titanic
9.	Ticket- Ticket number
10.	Fare- Amount of money that person paid to travel
11.	Cabin- Cabin Number of Passenger
12.	Embarked- Port of Embarkation ( C = Cherbourg, Q = Queenstown, S = Southampton)


# Content of EDA :
 1. Loading the data
   2. Describe the data
   3. Feature Extraction (Countplot, Histograms , PDF & CDF)
   4.Graphical Bi-variate Analysis  
   5. Mean,Median,  Percentile, Quantile, IQR, MAD and Std-dev(Only three features
   6. Correlation Matrix
