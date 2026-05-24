# F1 Pit Stop Strategy Analysis (2018–2024)

Quantitative analysis of Formula 1 pit stop strategies using regression modeling, exploratory data analysis, and trend visualization across teams, circuits, and tire compounds.

---

# Project Overview

Pit stop strategies are among the most critical tactical components in Formula 1 racing. Over time, changes in regulations, tire compounds, track conditions, and race strategies have significantly influenced pit stop performance and race outcomes.

This project analyzes Formula 1 pit stop data from 2018 to 2024 to identify trends in:

- Pit stop duration
- Tire compound strategies
- Team performance
- Seasonal evolution
- Circuit-level strategy variations

The project combines exploratory data analysis, regression modeling, feature engineering, and visualization techniques to better understand how modern Formula 1 teams optimize pit stop performance.

---

# Research Question

How have Formula 1 pit stop strategies evolved between 2018 and 2024 in terms of:

- Pit stop frequency
- Pit stop duration
- Tire compound usage

...across different teams and circuits?

---

# Objectives

The project aims to:

- Analyze historical pit stop performance trends
- Identify factors influencing pit stop duration
- Compare strategies across teams and seasons
- Study tire compound usage patterns
- Build regression models for pit stop time prediction
- Visualize strategic evolution in Formula 1 racing

---

# Tech Stack

## Programming & Analytics
- Python
- Pandas
- NumPy

## Visualization
- Matplotlib
- Seaborn

## Machine Learning
- Scikit-learn
- Linear Regression

## Development Environment
- Jupyter Notebook

---

# Repository Structure

```text
f1-pit-stop-strategy-analysis/
│
├── data/
│   └── f1_pitstops_2018_2024.csv
│
├── notebooks/
│   ├── f1_pitstop_case_study.ipynb
│   └── f1_regression_analysis.ipynb
│
├── presentation/
│   └── evolution_of_pit_stop_strategies.pdf
│
└── README.md
```

---

# Dataset

The dataset contains Formula 1 pit stop information between 2018 and 2024, including:

- Team / Constructor
- Circuit
- Tire Compound
- Lap Number
- Pit Stop Duration
- Weather-related variables
- Seasonal information
- Performance metrics

The data was cleaned and preprocessed for analytical modeling and visualization.

---

# Methodology

## 1. Data Preparation

Performed:

- Missing value handling
- Duplicate removal
- Data normalization
- Feature engineering
- Date and categorical processing

---

## 2. Exploratory Data Analysis (EDA)

Exploratory analysis focused on:

- Team-wise pit stop trends
- Tire compound usage
- Seasonal strategy evolution
- Correlation analysis
- Distribution analysis

Visualizations included:

- Correlation heatmaps
- Trend analysis graphs
- Team comparison charts
- Tire strategy visualizations

---

## 3. Regression Analysis

Linear Regression models were applied to predict pit stop duration using variables such as:

- Tire Compound
- Lap Number
- Team
- Track
- Weather metrics

### Regression Goals

- Identify key factors affecting pit stop performance
- Quantify strategic impact variables
- Evaluate predictive capability of race conditions

---

# Key Insights

- Tire compound selection significantly impacts pit stop duration.
- Top teams demonstrated consistent reductions in average pit stop times over time.
- Seasonal regulation changes influenced strategy evolution.
- Circuit characteristics affected tire strategy choices.
- Weather-related variables contributed to pit stop variability.

---

# Results

The analysis demonstrated:

- Clear strategic evolution in Formula 1 pit stop management
- Improved operational efficiency among leading teams
- Strong relationships between tire strategy and pit performance
- Distinct tactical variations across circuits and seasons

Regression analysis also identified several influential variables contributing to pit stop duration prediction.

---

# Visualizations Included

The project includes:

- Correlation heatmaps
- Team-wise pit stop trend analysis
- Tire compound strategy charts
- Regression prediction visualizations
- Feature importance analysis

---

# Future Improvements

Potential future enhancements include:

- XGBoost and ensemble models
- LSTM time-series forecasting
- Real-time race simulation
- Weather and traffic integration
- Interactive dashboards using Plotly or Power BI

---

# Files Included

## Dataset
- Formula 1 pit stop dataset (2018–2024)

## Notebooks
- Full exploratory data analysis notebook
- Regression analysis notebook

## Presentation
- Research presentation summarizing methodology and findings

---

# Disclaimer

This project was developed as part of an academic quantitative data analysis study focused on Formula 1 strategy evolution and predictive analytics.

---

# Author

Faiz Nizamuddin Karol

LinkedIn: https://linkedin.com/in/faiz-karol
