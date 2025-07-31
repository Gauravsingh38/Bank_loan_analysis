
# Bank Loan Analysis Project

## Overview
This project involves analyzing bank loan data to provide insights into lending practices. By utilizing Power BI for visualization and SQL for data management, we aim to assess borrowing trends, risk factors, and repayment behaviors.

### Key Objectives:
- Understand the factors influencing loan approval and performance.
- Visualize loan data to identify trends and insights.
- Provide a detailed analysis of borrower profiles and financial behaviors.

## Terminologies Used in Data
### Key Data Fields:
- **Loan ID**: A unique identifier for each loan application serving as a tracking mechanism for banks.
- **Address State**: Indicates the borrower’s location; important for assessing regional risk.
- **Employee Length**: Reflects employment stability, a factor in repayment likelihood.
- **Employee Title**: Specifies the borrower's occupation, crucial for income verification.
- **Grade/Sub Grade**: Risk classifications that help determine loan pricing based on creditworthiness.
- **Home Ownership**: Indicates the borrower’s housing status, aiding in risk assessment.
- **Issue Date**: The origination date of loans, important for tracking timelines.
- **Last Credit Pull Date**: Captures the last time the borrower’s credit was checked.
- **Loan Status**: Indicates the current state of the loan (e.g., fully paid, default).
- **Purpose**: Specifies the reason for borrowing, aiding in product customization.
- **Term**: Duration of the loan which influences repayment structure.
- **Verification Status**: Indicates if financial details have been verified, affecting credibility assessments.
- **Annual Income**: Yearly earnings of the borrower, critical for assessing repayment capacity.
- **DTI (Debt-to-Income Ratio)**: Metric that gauges the borrower’s capacity to take on additional debt.
- **Instalment**: Monthly repayment amount covering principal and interest.
- **Interest Rate**: The cost of borrowing expressed as a percentage, determining profitability for banks.
- **Loan Amount**: Total sum borrowed, defining the principal.

## Project Structure
### 1. Loading the Data
- Use Power BI to load `bank_loan_data.csv`.

### 2. Data Cleaning & Preparation
- Verify data integrity and handle missing values.
- Create calculated fields where necessary (e.g., Debt-to-Income Ratio).

### 3. Visualizing the Data
#### Suggested Visualizations:
- **Total Loans by Approval Status**: Pie Chart showing distribution of loan statuses.
- **Loans by Purpose**: Bar Chart depicting the reasons for borrowing.
- **Loan Amount Distribution**: Histogram showing the spread of loan amounts.
- **DTI Analysis**: Scatter Plot assessing Debt-to-Income Ratios.
- **Monthly Loan Approvals**: Line Chart tracking approval trends over time.

### 4. Dashboard Creation
- Arrange visualizations for intuitive user interface.
- Add slicers for filtering data dynamically by loan status, purpose, and DTI.

### 5. Saving and Sharing the Insights
- Save your Power BI file and publish it to the Power BI Service for broader access.
- Optionally, provide a link in this repository for direct access to the dashboard.

## Importance of Data Analysis in Banking
- **Risk Assessment**: Evaluating borrower creditworthiness to minimize defaults.
- **Decision-Making**: Data-informed choices on loan applications.
- **Portfolio Management**: Monitoring loan health and identifying underperformers.
- **Fraud Detection**: Identifying unusual patterns in applications.
- **Regulatory Compliance**: Meeting reporting requirements for financial institutions.

## Conclusion
This project highlights the importance of thorough data analysis in banking, utilizing visual tools for deeper insights into loan management. 

"# Bank_loan_analysis" 
