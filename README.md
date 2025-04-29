# Titanic-Survival-Prediction

📌 Objective:
To build a predictive model that determines whether a passenger survived or not based on features like age, sex, class, fare, family size, etc.

📊 Dataset Features:
PassengerId: Unique ID for each passenger
Pclass: Passenger class (1st, 2nd, 3rd)
Name: Passenger's name
Sex: Gender
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Ticket fare
Cabin: Cabin number
Embarked: Port of Embarkation (C, Q, S)
Survived: Target variable (0 = No, 1 = Yes)

🔍 Steps Involved:

  1)Data Preprocessing:
    Handle missing values (e.g., Age, Cabin, Embarked)
    Encode categorical variables (Sex, Embarked)
    Feature engineering (e.g., Title extraction from Name)

  2)Exploratory Data Analysis (EDA):
    Visualize survival rates based on various features
    Analyze correlations and patterns

  3)Model Building:
    Train using Logistic Regression, Random Forest, or other classifiers
    Evaluate with metrics like accuracy, precision, recall, F1-score
