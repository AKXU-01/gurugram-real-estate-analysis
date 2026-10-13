# Gurugram Real Estate Data Analysis

Exploratory data analysis (EDA) of Gurugram property listings to understand what drives housing prices in the city, built with Python.

## Overview
This project cleans a raw real estate dataset and answers key questions about prices, localities, property status, RERA approval and BHK configurations using Pandas and Seaborn.

## Dataset
Gurugram property listings (`data.csv`) with columns such as price, area, rate per sq ft, locality, society, builder/company, BHK count, flat type, status and RERA approval.

## Data Cleaning
- Standardized column names (lowercase, underscores)
- Removed duplicate records
- Converted `price`, `area` and `rate_per_sqft` from text to numeric
- Cleaned `status`, `flat_type` and `rera_approval` (mapped to True/False)

## Questions Answered
1. Which is the most expensive flat in the dataset?
2. Which locality has the highest average price?
3. Which locality has the highest rate per sq ft?
4. Do ready-to-move properties cost more than under-construction ones?
5. Do RERA-approved properties command a price premium?
6. How does area impact price?
7. Which BHK configuration is the most expensive?
8. Which builders/companies have the highest rate per sq ft?
9. Are larger homes more expensive per sq ft?

## Key Findings
> Add your results here after running the notebook, for example:
> - Highest average price locality: **[locality]**
> - Highest rate per sq ft locality: **[locality]**
> - Ready-to-move vs under-construction: **[your finding]**
> - RERA premium: **[your finding]**

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## How to Run
```bash
git clone https://github.com/<your-username>/gurugram-real-estate-analysis.git
cd gurugram-real-estate-analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook gurugram_real_state.ipynb
```

## Author
**Akshay Kumar**
Connect with me on [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)
