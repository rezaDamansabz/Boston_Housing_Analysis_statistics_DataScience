# Boston Housing Analysis

## Project Overview
This project explores the **Boston Housing dataset** to uncover key factors affecting the median value of owner-occupied homes. It combines **data science techniques** and **statistical analysis** to provide actionable insights for decision-making in real estate and urban planning.

The analysis addresses questions such as:
- Does proximity to the Charles River affect house prices?
- How does the age of houses influence their median value?
- Is there a relationship between nitric oxide concentration and proportion of non-retail business acres?
- How does distance to employment centers impact housing prices?

---

## Dataset
The dataset contains information on housing and environmental characteristics in Boston, including:

| Variable | Description |
|----------|-------------|
| CRIM     | Per capita crime rate by town |
| ZN       | Proportion of residential land zoned for lots over 25,000 sq.ft. |
| INDUS    | Proportion of non-retail business acres per town |
| CHAS     | Charles River dummy variable (1 if tract bounds river; 0 otherwise) |
| NOX      | Nitric oxide concentration (parts per 10 million) |
| RM       | Average number of rooms per dwelling |
| AGE      | Proportion of owner-occupied units built prior to 1940 |
| DIS      | Weighted distances to five Boston employment centres |
| RAD      | Index of accessibility to radial highways |
| TAX      | Full-value property-tax rate per $10,000 |
| PTRATIO  | Pupil-teacher ratio by town |
| LSTAT    | % lower status of the population |
| MEDV     | Median value of owner-occupied homes ($1000s) |

---

## Methods
The project is organized in three main tasks:

### **Task 1: Data Familiarization**
- Checked data types, missing values, and unique values.
- Explored variable distributions using histograms and boxplots.
- Calculated correlations to identify potential relationships.

### **Task 2: Descriptive Statistics & Visualizations**
- **Boxplots:** MEDV overall, MEDV by property age groups.
- **Bar plot:** Number of houses near the Charles River (CHAS).
- **Histogram:** Pupil-teacher ratio (PTRATIO).
- **Scatter plot:** NOX vs INDUS.
- Included explanations for all visualizations to highlight key insights.

### **Task 3: Statistical Analysis**
- **T-test:** Compare median house values for Charles River proximity.
- **ANOVA:** Compare MEDV across different age groups of houses.
- **Pearson correlation:** Examine relationship between NOX and INDUS.
- **Regression:** Evaluate impact of distance to employment centers on MEDV.
- All tests include hypotheses, α = 0.05, test statistics, and conclusions.

---

## Key Insights
- Houses near the Charles River tend to have different median values compared to others.
- The age of houses (pre-1940) significantly influences median home prices.
- Nitric oxide concentration is strongly correlated with the proportion of non-retail business acres.
- Distance to employment centers significantly affects median housing value, highlighting the importance of accessibility.

---

## Technologies & Libraries
- **Python**: Pandas, NumPy, SciPy, Seaborn, Matplotlib, Statsmodels
- **Statistical Methods**: T-test, ANOVA, Pearson Correlation, Linear Regression
- **Visualization**: Boxplots, Bar charts, Histograms, Scatter plots, Correlation Heatmaps

---

## Repository Structure
