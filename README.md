# Life Expectancy Analysis Using R

**Exploratory Data Analysis | Statistical Modeling | Machine Learning | R**

## Project Overview

This project examines life expectancy indicators using R, combining exploratory data analysis, statistical visualization, multivariate analysis, and predictive modeling.

The analysis uses the World Health Organization (WHO) Life Expectancy dataset, covering 193 countries during the period 2000–2015.

The project was developed in the context of the HarvardX Data Science: Capstone course and is presented as part of a Data Science portfolio.

## Dataset

- **Source:** [Life Expectancy (WHO) — Kaggle](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
- **Observations:** 2,938
- **Variables:** 22
- **Period:** 2000–2015
- **Format:** CSV

The dataset includes demographic, economic, health, and development indicators associated with life expectancy.

## Project Objectives

- Explore patterns and relationships in life expectancy indicators.
- Identify relevant variables through statistical analysis.
- Apply data cleaning and transformation techniques.
- Use Principal Component Analysis (PCA) to explore dimensionality reduction.
- Apply regression models to investigate relationships and classification problems.
- Document the analytical process using reproducible R Markdown reports.

## Analytical Methodology

### 1. Exploratory Data Analysis (EDA)

Data exploration, cleaning, transformation, descriptive statistics, and visualization.

### 2. Correlation Analysis

Investigation of relationships among numerical variables using correlation techniques and visualizations.

### 3. Principal Component Analysis (PCA)

Application of dimensionality reduction techniques to explore patterns among correlated variables, with a focus on OECD countries in the second part of the analysis.

### 4. Multiple Linear Regression

Application of regression modeling to examine relationships between life expectancy and explanatory variables.

### 5. Logistic Regression

Application of a classification model to investigate categorical outcomes within the analytical workflow.

## Results and Findings

The project includes exploratory visualizations, statistical summaries, PCA results, and regression analyses.

Detailed outputs and interpretations are available in the project reports.

Quantitative model performance and statistical findings should be interpreted in the context of the original analysis. Independent validation of all statistical results has not been performed.

## Technologies and Libraries

- R 4.5.1
- R Markdown
- ggplot2
- dplyr
- caret
- FactoMineR
- factoextra
- car
- psych
- corrplot
- janitor
- lmtest
- tseries

## Project Structure

```text
life-expectancy-r-analysis/
├── data/
│   └── Life Expectancy Data.csv
├── reports/
│   ├── Capstone Data Science Jorge Castro Martínez.Rmd
│   ├── Capstone-Data-Science-Jorge-Castro-Martínez.html
│   └── Capstone-Data-Science-Jorge-Castro-Martínez.pdf
├── scripts/
│   ├── Capstone Data Science Jorge Castro Martínez.R
│   └── Proyecto Mejorado Capstone Data Science Jorge Castro Martínez.R
├── Capstone-Data-Science-Jorge-Castro-Martínez.html
├── .gitignore
└── README.md
```

## Project Reports

- [View HTML Report](reports/Capstone-Data-Science-Jorge-Castro-Martínez.html)
- [View PDF Report](reports/Capstone-Data-Science-Jorge-Castro-Martínez.pdf)
- [View R Markdown Source](reports/Capstone%20Data%20Science%20Jorge%20Castro%20Mart%C3%ADnez.Rmd)

The HTML file can be downloaded and opened in a web browser.

## Reproducibility

The project was developed using R 4.5.1.

The dataset is located at:

`data/Life Expectancy Data.csv`

To regenerate the HTML report, run the following R command from the repository's root directory:

```r
rmarkdown::render(
  "reports/Capstone Data Science Jorge Castro Martínez.Rmd",
  output_format = "html_document",
  knit_root_dir = getwd()
)
```

The HTML report has been generated successfully in the configured development environment. This verifies report rendering, but does not constitute independent validation of the statistical models or findings.

## Academic Context

This project was developed as part of the HarvardX Data Science: Capstone course offered through edX.

It demonstrates the application of data analysis, statistical modeling, visualization, and machine learning techniques using R.

## Author

**Jorge Castro Martínez**

Data Science | Artificial Intelligence | Statistical Analysis

[GitHub Portfolio](https://github.com/JorgeDSIA)