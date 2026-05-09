# Survival Analysis Project

Marketing Analytics | DS223
American University of Armenia (AUA)

## Overview

This project analyzes customer churn behavior using survival analysis techniques and Customer Lifetime Value (CLV) estimation. The analysis is performed using Python in a Jupyter Notebook environment with parametric survival models from the `lifelines` library.

The goal of the project is to identify the factors affecting customer churn risk, compare different Accelerated Failure Time (AFT) models, estimate customer lifetime value, and provide insights for customer retention strategies.

## Project Tasks

The project includes:

- Building Accelerated Failure Time (AFT) survival models using multiple probability distributions
- Comparing model performance
- Visualizing survival curves
- Selecting significant variables and identifying the final model
- Estimating Customer Lifetime Value (CLV)
- Exploring high-value customer segments
- Interpreting factors affecting churn risk
- Providing retention strategy recommendations

## Dataset Features

The dataset contains subscriber-level information, including:

- Demographics (age, gender, marital status, education)
- Financial indicators (income)
- Service usage features (voice, internet, call forwarding)
- Customer category information
- Churn indicator
- Customer tenure (lifetime)

## Repository Structure

```text
Survival_Analysis/
│
├── Data/
│   └── teclo.csv
│
├── notebook.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Lifelines

## Running the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebook.ipynb
```
