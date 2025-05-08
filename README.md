# 📊 Tumor Response Analysis

## 🧪 Project Overview

Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications, conducted a 45-day study on 249 mice diagnosed with squamous cell carcinoma (SCC). The mice were treated with various drug regimens, including Capomulin, Ramicane, Infubinol, and Ceftamin. The primary objective was to evaluate the effectiveness of these treatments in reducing tumor volume.

## 🧰 Methodology

The analysis followed these key steps:

1. **Data Preparation**
   - Merged `mouse_metadata` and `study_results` datasets.
   - Identified and removed duplicate entries based on Mouse ID and Timepoint.

2. **Summary Statistics**
   - Calculated mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volumes by drug regimen.

3. **Data Visualization**
   - **Bar Charts**: Total number of timepoints for each drug regimen using Pandas and Matplotlib.
   - **Pie Charts**: Gender distribution of mice using Pandas and Matplotlib.

4. **Outlier Detection and Box Plots**
   - Determined final tumor volumes for mice on Capomulin, Ramicane, Infubinol, and Ceftamin.
   - Calculated interquartile range (IQR) and identified potential outliers.
   - Created box plots showing tumor volume distributions.

5. **Line and Scatter Plots**
   - **Line Plot**: Tumor volume over time for a single mouse treated with Capomulin.
   - **Scatter Plot**: Relationship between mouse weight and average tumor volume for Capomulin.

6. **Correlation and Regression Analysis**
   - Calculated Pearson correlation coefficient between weight and average tumor volume.
   - Performed linear regression and plotted the trendline on a scatter plot.

## 🔍 Key Findings

- **Capomulin and Ramicane** showed lower final tumor volumes compared to Infubinol and Ceftamin.
- **Outliers** were noted in the Infubinol and Ceftamin groups, indicating variability in drug response.
- **Positive correlation** was found between mouse weight and tumor volume for Capomulin-treated mice.

## 📁 Repository Structure

- `pymaceuticals.ipynb`: Main Jupyter Notebook with the analysis.
- `Resources/`: Folder containing source datasets.

---

This project exemplifies exploratory data analysis in a preclinical context, using statistical methods and visualization to assess treatment efficacy.




