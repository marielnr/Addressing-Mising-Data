<img width="1229" height="524" alt="image" src="https://github.com/user-attachments/assets/8479308a-0e62-44b7-89f4-88bd997f6858" />

# Address Missing Data in Unicorn Companies Dataset

This Jupyter Notebook explores handling missing data in a dataset of unicorn companies (startups valued over $1B). It covers:

## Contents
- **Exploratory Data Analysis (EDA)**: Dataset shape, data types, descriptive statistics.
- **Data Cleaning**: Type conversion, handling null values (e.g., in 'City' and 'Select Investors').
- **Specific Analysis**:
  - Hardware industry companies in Beijing, San Francisco, and London.
  - AI industry companies in London.
  - Top 20 countries by sum of valuations (excluding US, China, India, UK).
  - Global valuation map.
- **Visualizations**: Charts with Matplotlib, Seaborn, and Plotly (including a geo map).

## Requirements
- Python 3.7+
- Libraries: `pandas`, `numpy`, `matplotlib`, `plotly`, `seaborn`
- Dataset: [Unicorn_Companies.csv](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies) (included or download here).

## Key Findings
- The dataset includes 1074 companies, with missing data in 'City' (16) and 'Select Investors' (1).
- Top countries (excluding big-4): Germany ($72B), Sweden ($63B), etc.
- Europe stands out for high unicorn activity.

