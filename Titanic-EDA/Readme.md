# Titanic Survival Analysis: Unraveling the Tragedy 🚢

This repository showcases my Exploratory Data Analysis (EDA) of the iconic Titanic dataset. The primary objective was to dissect and understand the multifaceted factors that influenced passenger survival during the tragic sinking.

## Project Overview 🧐

The Titanic dataset, a staple for data science learners, offers a compelling narrative for analysis. This project delves into the dataset to extract meaningful insights regarding passenger demographics, socioeconomic classes, and other relevant features that correlate with survival outcomes.

## Repository Structure 📂

* `Titanic.csv`         # The foundational Titanic dataset.
* `Titanic-sol.ipynb`   # Jupyter Notebook detailing the comprehensive EDA process.
* `Case_study.pdf`      # Documentation outlining the specific questions addressed during the EDA.
* `Age_group.ipynb`     # Supplementary notebook featuring in-depth visualizations related to age-based survival patterns.

## Dataset Description 📊

The dataset provides a rich array of information for each passenger, including:

* **PassengerId:** Unique identifier for each individual.
* **Survived:** Binary indicator of survival (0 = No, 1 = Yes).
* **Pclass:** Passenger ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
* **Name:** Passenger's full name.
* **Sex:** Passenger's gender.
* **Age:** Passenger's age in years.
* **SibSp:** Number of siblings/spouses aboard.
* **Parch:** Number of parents/children aboard.
* **Ticket:** Ticket number.
* **Fare:** Ticket fare.
* **Cabin:** Cabin number.
* **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Exploratory Data Analysis (EDA) Process 🔍

The EDA was conducted using a methodical approach, encompassing:

* **Data Wrangling:** Cleaning and preprocessing to handle missing values and inconsistencies.
* **Univariate & Bivariate Analysis:** Examining individual features and their relationships.
* **Visualizations:** Creating insightful plots to reveal patterns and correlations.
* **Pattern Identification:** Deriving meaningful insights from the data.

## Key Findings & Methodologies 💡

* **Gender Disparity in Survival:**
    * Females exhibited a significantly higher survival rate (74%) compared to males (19%), underscoring the "women and children first" evacuation policy.
    * `LabelEncoder` was utilized to encode the 'Sex' variable for analytical purposes.

* **Socioeconomic Influence (Pclass):**
    * First-class passengers enjoyed a 63% survival rate, while third-class passengers had a mere 24%, illustrating the impact of socioeconomic status on survival.
    * `Stacked bar plots` and `conditional probability` tables were employed for visualization and analysis.

* **Age-Related Survival Trends:**
    * Kernel Density Estimation (KDE) plots revealed distinct age distributions among survivors.
    * Children under 10 demonstrated higher survival rates, whereas older passengers in third class faced increased mortality.

## Conclusions 🎉

This analysis provided a comprehensive view of the Titanic dataset, revealing crucial insights into passenger characteristics and their survival outcomes. The EDA process involved thorough data cleaning, insightful visualizations, and statistical analysis, highlighting the significant impact of gender, socioeconomic status, and age on survival rates.

## Future Directions 🔮

* **Advanced Feature Engineering:** Creating new features to enhance predictive modeling.
* **Predictive Model Development:** Building a machine learning model to predict passenger survival.
* **Web Application Deployment:** Deploying the model as an interactive web app or API for broader accessibility.
