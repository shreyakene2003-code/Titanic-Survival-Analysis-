# Titanic-Survival-Analysis-
This project performs a complete Exploratory Data Analysis (EDA) on the famous Titanic passenger dataset. The goal is to uncover survival patterns based on gender, passenger class, and age — practicing real-world data cleaning and visualization skills.
 Objectives

Load and explore the Titanic dataset
Clean messy/missing data (missing Age values, duplicates)
Answer key analytical questions:

Who survived more — males or females?
Did passenger class affect survival?
What was the survival rate by age group?


Visualize findings using Seaborn and Matplotlib


 Data Cleaning Steps

Missing Age values → filled with median age (robust to outliers)
Missing Embarked → filled with mode
Duplicate rows → identified and removed
Age Group feature → created bins: Child, Teen, Young Adult, Adult, Senior

Dataset

Source: Titanic Dataset – Kaggle
Rows: 891 passengers
Columns: PassengerId, Survived, Pclass, Sex, Age, Fare, Embarked
Target: Survived (0 = No, 1 = Yes)



 Insights & Conclusions

Gender was the strongest predictor — the "women and children first" maritime protocol saved significantly more female lives.
Passenger class directly correlated with survival — likely due to cabin location (lower decks = 3rd class) and lifeboat access.
Children had priority evacuation, consistent with maritime safety protocols.
Socioeconomic status mattered — 1st class passengers had better access to lifeboats and were closer to the deck.
