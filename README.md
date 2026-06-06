# Titanic Dataset - Exploratory Data Analysis (EDA)

## Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the data, identify missing values, detect outliers, and discover patterns that influence passenger survival.

## Dataset

* Dataset Name: Titanic Dataset
* File: `Titanic-Dataset.csv`

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Steps Performed

1. Loaded the Titanic dataset.
2. Inspected the dataset structure and data types.
3. Checked for missing values.
4. Handled missing values in Age, Fare, and Embarked columns.
5. Removed the Cabin column due to excessive missing values.
6. Generated summary statistics.
7. Visualized data using histograms and boxplots.
8. Analyzed survival rates based on gender and passenger class.
9. Created a correlation heatmap.
10. Generated pairplots for numerical features.

## Visualizations

* Histograms
* Boxplots
* Survival Count Plot
* Gender vs Survival Plot
* Passenger Class vs Survival Plot
* Correlation Heatmap
* Pairplot

## Key Insights

* Most passengers were between 20 and 40 years old.
* Female passengers had a higher survival rate than male passengers.
* First-class passengers had better survival chances.
* Fare contains several outliers.
* Passenger class and fare show a relationship with survival.

## Repository Contents

* `task2_eda.ipynb` – Jupyter Notebook containing the complete EDA process.
* `Titanic-Dataset.csv` – Dataset used for analysis.
* `README.md` – Project documentation.

## Conclusion

The Exploratory Data Analysis helped uncover important trends and relationships within the Titanic dataset. The findings indicate that factors such as gender, passenger class, and fare significantly influenced survival outcomes.
