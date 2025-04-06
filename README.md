# Matplotlib-Challenge

# Pymaceuticals SCC Tumor Study Analysis

---

## Overview
This project analyzes data from Pymaceuticals' recent animal study, which aimed to evaluate the efficacy of various treatment regimens, including **Capomulin**, in reducing squamous cell carcinoma (SCC) tumor sizes. A total of 249 mice were monitored over 45 days, with their tumor volumes observed and recorded. The analysis focuses on comparing Capomulin to other treatment regimens and drawing insights from the study.

----

## Objectives
1. Clean and prepare the dataset to ensure integrity.
2. Generate key statistical summaries and visualizations to evaluate treatment performance.
3. Identify potential outliers and analyze trends in tumor volume reduction.
4. Assess relationships between variables, such as mouse weight and tumor volume.
5. Summarize findings to guide decision-making for future research.

---

## Files
- **`pymaceuticals.ipynb`**: Jupyter Notebook containing the Python code for the analysis, including data cleaning, statistics, and visualizations.
- **`README.md`**: This documentation file providing an overview of the analysis project.

---

## Key Steps in Analysis
1. **Data Cleaning**:
   - Removed duplicate entries and ensured data integrity.
   - Filtered data for the most relevant drug regimens (e.g., Capomulin, Ramicane).

2. **Statistical Summary**:
   - Calculated mean, median, variance, standard deviation, and SEM of tumor volumes across all regimens.

3. **Visualizations**:
   - **Bar Plot**: Number of observations for each drug regimen.
   - **Pie Chart**: Gender distribution of the mice.
   - **Box Plot**: Tumor volume distribution across treatment groups, with outliers marked.
   - **Line Plot**: Tumor volume trends over time for a single mouse treated with Capomulin.
   - **Scatter Plot**: Relationship between mouse weight and tumor volume for the Capomulin regimen, with a linear regression model.

4. **Outlier Analysis**:
   - Used IQR to detect potential outliers in tumor volume for each regimen.

5. **Correlation and Regression**:
   - Calculated the correlation coefficient between mouse weight and average tumor volume for Capomulin.
   - Generated a regression model to predict tumor volume based on weight.

---

## Key Findings
- **Capomulin and Ramicane** were the most effective regimens in reducing tumor volumes, showing the lowest mean and median values with high consistency (low variance and SEM).
- A strong positive correlation (**r = 0.84**) exists between mouse weight and tumor volume for Capomulin. This suggests potential for weight-based adjustments in treatment dosages
- Tumor volume trends over time indicate reliable tumor reduction for mice treated with Capomulin.
- Only **Infubinol** exhibited a notable outlier in tumor volume measurements.

---

## Technologies
- **Python**: Core programming language for analysis.
- **Pandas**: Data cleaning, manipulation, and statistical calculations.
- **Matplotlib**: Visualization of data using bar plots, pie charts, box plots, etc.
- **NumPy**: Correlation analysis and numerical computations.
- **SciPy**: Linear regression and statistical modeling.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/geraldine1456/matplotlib-challenge.git

2. Install required Python libraries:
   ```bash
   pip install pandas matplotlib numpy scipy

3. Download and place the dataset in the working directory.  (pymaceuticals\data : **`Mouse_metadata.csv`** and **`Study_results.csv`**)
4. Run the analysis code (**`pymaceuticals.ipynb`**) in Jupyter Notebook
5. Review the generated tables and figures for insights

---

## References
1.  [Python Official Documentation](https://docs.python.org/)
2.  [Pandas Documentation](https://pandas.pydata.org/docs/)
3.  [Matplotlib Documentation](https://matplotlib.org/)
4.  [Numpy Documentation](https://numpy.org/)
5.  [Scipy Documentation](https://scipy.org/)
6.  [Jupyter Notebook Guide](https://jupyter.org/)
7.  [W3Schools](https://www.w3schools.com/)
8.  [Microsoft Copilot](https://copilot.microsoft.com/)  
8.  Special thanks to Tutor CJ for assistance with debugging coding errors

---

##  Conclusion
Capomulin demonstrates exceptional potential as an SCC treatment, given its consistency and efficacy in reducing tumor volumes. These findings form the basis for further studies and clinical trials.

---

## Author
Bootcamp/GCValencia