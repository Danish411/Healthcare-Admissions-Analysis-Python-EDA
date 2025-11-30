# Healthcare Admissions and Length-of-Stay Analysis (Python/EDA) 🐍

## 1. Overview
Conducted an in-depth Exploratory Data Analysis (EDA) using Python to understand patient admission patterns and analyze factors influencing **Length of Stay (LOS)** in a healthcare setting. The analysis provides operational insights for resource planning and efficiency improvements.

### 🎯 Goal
To identify key temporal trends (e.g., peak admission days/months) and statistically characterize the distribution of patient Length of Stay (LOS), informing hospital capacity planning and staffing needs.

## 2. Tools & Technologies (The Python Stack)
- **Primary Language:** **Python 3**
- **Data Manipulation:** **Pandas** (for cleaning and feature engineering)
- **Numerical Analysis:** **NumPy**
- **Data Visualization:** **Matplotlib** and **Seaborn** (for statistical plots)
- **Environment:** Jupyter Notebook / Google Colab (`.ipynb`)

## 3. Key Actions / Process (EDA & Statistical Analysis)
- **Data Cleaning & Manipulation:** Used Pandas to handle missing data, convert dates, and calculate the `CALCULATED_LENGTH_OF_STAY` feature.
- **Temporal Analysis:** Analyzed admission data across multiple dimensions:
    - **Year/Month Trends:** Identified seasonal fluctuations in patient volume.
    - **Day-of-Week Analysis:** Determined if certain days (e.g., Mondays or Weekends) experience statistically significant differences in admission rates.
- **Statistical Profiling:** Performed descriptive statistics on `CALCULATED_LENGTH_OF_STAY` (mean, median, standard deviation) and visualized its distribution using **histograms and box plots** .
- **Hypothesis Generation:** Explored correlations between categorical variables (e.g., admission type) and the LOS to generate hypotheses for future predictive modeling.

## 4. Key Achievements & Results
- **Operational Efficiency:** Provided clear, visualized evidence of **peak admission periods**, enabling hospital management to optimize staffing levels and resource allocation to prevent bottlenecks.
- **Statistical Rigor:** Demonstrated proficiency in using the fundamental Python data science stack (Pandas, NumPy, Matplotlib) to derive statistical insights from real-world healthcare data.
- **Foundational Modeling:** Created a cleaned, analysis-ready dataset and identified key variables that would serve as the foundation for a future **Length of Stay predictive model**.

## 5. View Project
- **Full Code:** `HealthPython.ipynb` (Available in this repository)
- **Data Source:** [Sanitized Data File Name].csv
