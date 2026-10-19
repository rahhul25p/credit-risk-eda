# Credit Risk Analysis using Excel and Python

## Project Overview
This project analyzes a credit risk dataset to identify patterns associated with loan defaults. The analysis covers data cleaning, exploratory data analysis, scenario-based financial forecasting, and credit risk assessment using Microsoft Excel and Python.

## Dataset
- **Dataset:** `credit_risk_dataset.csv`
- **Records analyzed:** 9,983
- **Columns:** 12
- **Domain:** Banking and Financial Services

The dataset contains borrower information, loan details, credit history, and loan default status.

## Tools Used
- Microsoft Excel
- Python
- Pandas
- Jupyter Notebook

## Week 1: Understanding Financial Data

### Work Performed
- Inspected the dataset and reviewed its structure.
- Identified missing values and duplicate records.
- Removed 17 duplicate records and documented data quality decisions.
- Analyzed default rates by loan grade, loan purpose, home ownership, and age group.
- Compared average loan amounts and annual income across categories.
- Created charts and summary tables to present findings.

### Key Findings
- Overall historical default rate: **22.14%**.
- Grade G had the highest observed default rate at 100%.
- Grade A had the lowest observed default rate at approximately 9.68%.
- Debt consolidation had a default rate of approximately 29.91%.
- Venture loans had a default rate of approximately 14.74%.

These results describe patterns in the dataset and do not establish cause-and-effect relationships.

## Week 2: Creating Financial Forecasts

### Objective
Develop a scenario-based model to estimate how the loan default rate would change under different hypothetical assumptions.

### Work Performed
- Calculated the historical loan default rate in Excel.
- Created a forecast using a hypothetical 5% relative increase.
- Compared scenarios using 2%, 5%, and 10% relative increases.
- Created formulas, comparison tables, and charts.

### Key Results
- Historical default rate: **22.14%**
- Forecast rate under the 2% scenario: **22.58%**
- Forecast rate under the 5% scenario: **23.24%**
- Forecast rate under the 10% scenario: **24.35%**

### Limitation
The model is a hypothetical scenario analysis, not a prediction based on historical time-series trends.

## Week 3: Risk Analysis

### Objective
Identify potential credit risks, assess their likelihood and impact, and recommend mitigation strategies.

### Risks Identified
- **Loan Default Risk:** The dataset had a historical default rate of 22.14%.
- **High-Risk Loan Grades:** Grades D, E, F, and G showed substantially higher default rates than grades A and B.
- **Borrower Affordability Risk:** Borrowers may struggle to repay loans if their financial capacity is insufficient.
- **Loan Purpose Risk:** Default rates varied across loan purposes.
- **Missing or Unreliable Data:** Missing employment-length and interest-rate values may affect risk assessments.

### Mitigation Strategies
- Strengthen borrower credit checks and repayment-capacity assessments.
- Apply additional scrutiny to higher-risk loan applications.
- Verify income and assess debt-to-income levels.
- Review loan purpose and assess each application individually.
- Validate data and investigate missing values before making lending decisions.

### Limitation
The assessment is based on the available dataset. The identified patterns do not prove causation or guarantee future lending outcomes.

### Week 4: Hypothesis Testing
- Formulated null and alternative hypotheses to compare average loan amounts between defaulters and non-defaulters.
- Conducted an independent two-sample t-test assuming unequal variances (Welch’s t-test) using Microsoft Excel.
- Compared group averages and interpreted the p-value at a 5% significance level.
- Documented the methodology, results, limitations, and AI assistance in the project report.

## Week 5: Data Visualization

**Objective:** Visualize patterns in the credit risk dataset using Microsoft Excel.

**Visualizations Created:**
- Default Rate by Loan Grade
- Average Loan Amount by Default Status
- Default Rate by Loan Purpose

**Key Findings:**
- Default rates varied considerably across loan grades.
- Defaulters had a higher average loan amount than non-defaulters.
- Debt consolidation had the highest default rate among the loan purposes analyzed.

  ## Week 6: Reporting and Presentation

**Objective:** Combine the findings from Weeks 1–5 into a final credit risk analysis report.

**Work Completed:**
- Summarized the project objectives and scope.
- Consolidated the work completed across all five weeks.
- Presented key findings from exploratory data analysis, forecasting, risk assessment, hypothesis testing, and data visualization.
- Added recommendations for future analysis and a final conclusion.

**Tools Used:** Microsoft Excel

## Project Files
- `Credit_Risk_Analysis.xlsx` — Excel workbook containing data cleaning, analysis, summary tables, charts, forecasting, and risk analysis.
- `Credit_Risk_EDA.ipynb` — Python notebook containing exploratory data analysis.
- `Week_1_Understanding_Financial_Data.docx` — Week 1 report.
- `Week_2_Creating_Financial_Forecasts.docx` — Week 2 report.
- `Week_3_Risk_Analysis.docx` — Week 3 report.

## Conclusion
This project provided practical experience in financial data cleaning, exploratory data analysis, scenario-based forecasting, and credit risk assessment. The findings demonstrate how Excel and Python can be used to examine loan default patterns and support more informed lending decisions.
