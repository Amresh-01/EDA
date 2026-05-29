# Bengaluru House Price EDA

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Bengaluru House Price dataset.
The goal is to understand housing price trends, clean the data, identify outliers, and analyze relationships between important features such as price, total square feet, bathrooms, balconies, and locations.

---

## Dataset

Dataset: Bengaluru House Price Dataset

The dataset contains information about:

* Location
* Total square feet
* Number of bedrooms
* Bathrooms
* Balconies
* Price
* Area type
* Availability

---

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
```

---

## Data Cleaning Steps

The following preprocessing steps were performed:

* Removed duplicate rows
* Handled missing values
* Cleaned `total_sqft` column
* Converted square feet values to numeric format
* Removed extreme outliers
* Filled missing balcony values
* Clipped unrealistic bathroom values

---

## Exploratory Data Analysis (EDA)

### Univariate Analysis

Performed analysis on:

* Price
* Total square feet
* Bathrooms
* Balconies

Visualizations used:

* Histogram
* Boxplot
* KDE Plot
* Violin Plot

### Bivariate Analysis

Analyzed relationships between:

* Total square feet vs Price
* Bathrooms vs Price

Visualizations used:

* Scatter plots
* Regression plots

---

## Key Insights

* House prices are right-skewed
* Larger houses generally have higher prices
* Most properties lie between moderate price ranges
* Several extreme outliers were detected and handled
* Total square feet has a positive correlation with price

---

## Conclusion

This project demonstrates the complete EDA workflow:

* Data cleaning
* Missing value treatment
* Outlier handling
* Visualization
* Relationship analysis

The cleaned dataset can further be used for machine learning models such as Linear Regression, Random Forest, or XGBoost for house price prediction.

---

## Author

Amresh Chaurasiya
