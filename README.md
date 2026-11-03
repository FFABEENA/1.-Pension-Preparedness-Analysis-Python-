# Pension Preparedness Analysis – Indian Pension Subscriber Data (Python)

Exploratory analysis of Indian pension subscriber records to understand which demographic, contribution, investment and scheme-related factors are linked to stronger or weaker retirement preparedness.

## Dataset
- **Source:** India Pension Scheme Dataset (Kaggle) – synthetic data, not real individuals
- **Size:** 5,553 records × 38 variables (demographic, employment, contribution, investment, pension and retirement fields)

## What I did
**1. Data cleaning and validation**
- Checked duplicates, missing values and data types; standardised 14 categorical variables
- Converted text-stored numbers and dates, fixed mixed date formats, and corrected invalid ages by validating them against date of birth
- Ran consistency checks on contributions, fund value, NAV, units held and asset-allocation percentages
- Flagged outliers with IQR boxplots and kept genuine high-value accounts

**2. Exploratory data analysis**
- Descriptive, univariate, bivariate and multivariate analysis with Matplotlib and Seaborn
- Spearman correlation network of key pension variables

## Key findings
- Median subscriber age is 46 years, with a median of 7.3 years of contribution
- Fund values are right-skewed: mean ₹10.69 lakh vs median ₹4.29 lakh
- Total contribution and current fund value show the strongest relationship (Spearman 0.97), followed by monthly contribution and fund value (0.81)
- NPS – Government and UPS show higher median fund values and expected monthly pensions in this dataset
- Early, regular contributions and informed investment choices are linked to stronger preparedness

## Files
| File | Description |
|------|-------------|
| `Pension_Analysis_Notebook.ipynb` | Full Python notebook (cleaning, EDA, visualisations) |
| `Pension_Analysis_Report.pdf` | Complete analysis report with outputs and interpretation |
| `Data_Cleaning_Report.pdf` | Data cleaning and preprocessing summary |
| `Dataset_Raw.xlsx` / `Dataset_Cleaned.xlsx` | Dataset before and after cleaning |

## Tools
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

---
*Fabeena Fasal* · [LinkedIn](https://www.linkedin.com/in/fabeena-fasal)
