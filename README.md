Titanic Dataset - Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover insights, identify patterns, and prepare the data for further modeling.

The dataset contains passenger details such as age, sex, ticket class, fare, and survival status. The goal is to explore relationships between these variables and survival outcomes.
📂 Dataset

The dataset used is the train.csv file from the Titanic Kaggle competition.

Columns:

    PassengerId → Unique ID for each passenger

    Survived → Survival status (0 = No, 1 = Yes)

    Pclass → Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

    Name → Passenger name

    Sex → Gender

    Age → Age in years

    SibSp → Number of siblings/spouses aboard

    Parch → Number of parents/children aboard

    Ticket → Ticket number

    Fare → Ticket price

    Cabin → Cabin number

    Embarked → Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

🔍 EDA Steps

    Data Cleaning

        Filled missing Age with mean value.

        Filled missing Embarked with mode.

        Filled missing Cabin with "Unknown".

    Univariate Analysis

        Age distribution

        Fare distribution

        Passenger class counts

    Bivariate & Multivariate Analysis

        Survival rate by gender

        Fare distribution by class

        Survival rate by port of embarkation

        Correlation heatmap

        Pairplot for numeric variables

    Visualization Tools

        Histogram

        Count plot

        Box plot

        Heatmap

        Pairplot

📊 Key Insights

    Females had a much higher survival rate than males.

    First-class passengers were more likely to survive than third-class passengers.

    Higher Fare correlated positively with survival.

    Most passengers were between 20 and 40 years old.

    Cabin data is missing for most passengers.

🛠 Tools & Libraries

    Python 3

    Pandas

    NumPy

    Matplotlib

    Seaborn

    ReportLab (for PDF reporting)
