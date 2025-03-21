# Survey of Labour and Income Dynamics (SLID)

## Overview
This project analyzes the **Survey of Labour and Income Dynamics (SLID)** dataset, which provides insights into labor market trends, income distribution, and demographic statistics. The analysis includes graphical and statistical representations, regression modeling, probability distributions, and interactive components using **Shiny**.

## Repository Structure
```
SLID-Analysis/
│-- image.jpeg         # Sample visualization from the dataset
│-- SLID.csv           # Dataset containing labor and income survey data
│-- script.Rmd         # R Markdown script performing the analysis
│-- README.md          # Documentation of the project
```

## Features & Analysis
1. **Graphical and Tabular Data Representation**
   - Frequency distribution tables for **Age, Wages, and Education**.
   - Histograms for visualizing distribution.
   - Pie charts and bar charts for **gender distribution**.
   - Summary statistics for all variables.
   - Boxplots for understanding dispersion and outliers.

2. **Descriptive Statistical Measures**
   - Computation of **mean, variance, standard deviation, median, and IQR**.
   - Analysis of **Age, Wages, and Education**.
   - Gender mode identification.

3. **Probability Distributions**
   - Normal distribution applied to **Age**.
   - Calculation of **mean, variance, standard deviation, and expected value**.
   - Probability estimation for an individual of **Age = 35** using standardization.

4. **Regression Modeling & Predictions**
   - Scatter plots showcasing the relationships between **Wages & Education** and **Wages & Age**.
   - Multiple linear regression model: **Wages = a + b(Age) + c(Education) + e**.
   - Shiny app integration for real-time wage prediction based on user input.

5. **Confidence Intervals**
   - **95% confidence intervals** for descriptive measures.
   - Confidence intervals for **regression estimates**.

## How to Run the Project

### Prerequisites
Ensure you have the following installed:
- **R**
- **RStudio**
- **R Markdown**
- Required dependencies:
  ```r
  install.packages(c("fdth", "shiny", "knitr"))
  ```

### Steps to Run
1. **Clone the repository**
   ```sh
   git clone https://github.com/Ehsan-Tanvir/SLID-Analysis.git
   cd SLID-Analysis
   ```
2. **Open the project in RStudio**
3. **Run the script**
   - Open `script.Rmd` in RStudio.
   - Click the **"Run Document"** button to execute the analysis.
4. **Run the Shiny App**
   - The script includes a Shiny app for wage prediction.
   - Enter **Age** and **Education** in the input fields.
   - Click **"Output"** to get the predicted wage per hour.

## Dataset
The dataset used in this analysis is publicly available on Kaggle:
[Survey of Labour and Income Dynamics (SLID)](https://www.kaggle.com/datasets/utkarshx27/survey-of-labour-and-income-dynamics)



