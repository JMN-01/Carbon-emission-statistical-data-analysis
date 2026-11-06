# Carbon CO2 Emissions Data Analysis
This Machine learning project conducts statistical analysis **(Descriptive and inferential)** of Carbon Emission data sourced from 190 countries over a period of 29 years, it uncovers the reliability of the data measuring and collection techniques from developing countries.

## 📌 Project Overview
* This project was completed as part of the assessment requirements for **IDS201 - Introduction to Data Science**. 
* Analyze global carbon emissions data using *Descriptive* and *Inferential* statistical analysis techniques also utilizing Python, pandas, and Seaborn to uncover regional trends, distribution and emission outliers across different economic tiers for the purpose of identifying its reliability (for CO2 data collected from developing countries).

## Dataset source
- **Original Dataset:** The dataset was produced by Ravender Singh Rana and retrieved from https://www.kaggle.com/datasets/ravindrasinghrana/carbon-co2-emissions/data 

## Key Technical Steps & Pipeline

1. **Data Preprocessing & Cleaning:**
- Inspected and structured the global carbon emissions dataset comprising countries across a 29-year historical period (1990–2019).
- Standardized and verified numerical features (Kilotons of Co2, Metric Tons Per Capita) and categorical features (Country, Region).
- Handled missing and non-standard values across regional records to maintain data integrity and consistency for downstream statistical analysis.

2. **Descriptive Statistical Analysis::**
- Evaluated measures of central tendency (Mean, Median, Mode) and distribution skewness globally and across five distinct geographic regions using Python
- Analyzed measures of variability (Standard Deviation, Variance, Interquartile Range) to quantify emission spread and disparities.
- Applied the 1.5x Interquartile Range (IQR) rule and generated box-and-whisker plots and frequency histograms (matplotlib, seaborn) to detect and visualize regional outliers and skewed distributions

3. **Inferential Statistics & Trend Modeling:**
- Implemented Linear Regression in Python to characterize the relationships between time (Date) and emission metrics (Kilotons of Co2, Metric Tons Per Capita).
- Calculated regional annual rates of change and established trend lines to evaluate emission trajectories across the 5 regions, Asia, the Americas, Africa, Europe, and Oceania.
- Integrated 95% Confidence Intervals around regression models to establish margins of error, supporting the final evaluation of dataset reliability and reporting inconsistencies between developed and developing nations.

## 📊 Results
The statistical analysis uncovered that less than 10 percent of the countries were responsible for majority of the CO2 emission.
- The regional Frequency Distribution of CO2 Emissions (Metric Tons Per Capita)

</div>
<div align="center">

<img width="1429" height="789" alt="Regional Frequency Distribution of CO2 Emissions (Metric Tons Per Capita)" src="https://github.com/user-attachments/assets/d89a10e1-2594-4af5-a0e4-cd53346266e7" />
</div>


## How to Run Locally

To explore or execute the notebooks on your local machine/operating system, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/JMN-01/CLR204-Covid-19-Patient-Health-Statistical-Analytics.git
```
### 2. Install dependencies

Ensure you have Python installed, then install the required data science libraries:
```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```
### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

















