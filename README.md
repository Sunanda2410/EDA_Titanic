# Mini Exploratory Data Analysis (EDA) on Titanic Dataset

## Objective

The objective of this project is to perform a Mini Exploratory Data Analysis (EDA) on the Titanic dataset by cleaning the data, handling missing values, creating new features, and visualizing important patterns. The analysis helps identify factors that influenced passenger survival.

## Dataset

- **Dataset:** Titanic Dataset
- **Format:** CSV
- **Records:** 891 passengers
- **Features:** Passenger details such as Age, Sex, Passenger Class, Fare, Embarked Port, Family Information, and Survival Status.

## Tools & Libraries Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Data Cleaning

- Filled missing values in the **Age** column using the mean value.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column due to a large number of missing values.
- Verified that the cleaned dataset contained no missing values in the remaining columns.

## Exploratory Data Analysis

### 1. Survival Rate by Age Group
- Created age groups using the Age column.
- Calculated the survival rate for each age group.
- Visualized the results using a bar chart.

### 2. Survival Rate by Embarkation Port
- Grouped passengers based on their embarkation port.
- Calculated the survival percentage for each port.
- Displayed the results using a bar chart.

### 3. Survival Rate by Family Size
- Created a new **FamilySize** feature using:
  - SibSp (Number of siblings/spouses)
  - Parch (Number of parents/children)
- Analyzed the relationship between family size and survival.
- Visualized the results using a bar chart.

## Visualizations

- **Age Distribution (Histogram)** – Shows the distribution of passenger ages.
-  **Correlation Heatmap** – Displays the relationships between numerical features.
-  **Survival Rate by Family Size (Bar Plot)** – Illustrates how family size influenced passenger survival.

## Key Findings

- Children had the highest survival rate among all age groups.
- Senior passengers had the lowest survival rate.
- Survival rates varied across different embarkation ports.
- Passengers travelling with small families had better survival chances than those travelling alone or in very large families.
- Data cleaning and feature engineering significantly improved the quality of the analysis.

## Conclusion

This project demonstrates the complete workflow of a Mini Exploratory Data Analysis (EDA), including data cleaning, feature engineering, visualization, and interpretation of results. The analysis provides meaningful insights into how age, embarkation port, and family size influenced passenger survival on the Titanic.
