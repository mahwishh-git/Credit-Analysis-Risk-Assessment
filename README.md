# Credit-Analysis-Risk-Assessment
Credit Analysis &amp; Risk Assessment using Excel, SQL, and Power BI to analyze credit profiles, loan performance, risk, and financial trends through data analysis and interactive dashboards.
# 💳 Credit Analysis & Risk Assessment

## 📊 End-to-End Data Analytics Project using Excel, SQL & Power BI

This project focuses on analyzing **customer credit profiles, loan applications, financial behavior, and credit risk** using three complementary tools:

* 📗 **Microsoft Excel** — Data analysis and exploration
* 🗄️ **SQL** — Data querying and business analysis
* 📊 **Power BI** — Interactive dashboard and visualization

The project demonstrates an end-to-end analytics workflow, starting from structured credit data and progressing toward actionable insights through SQL analysis and an interactive Power BI dashboard.

---

## 🎯 Project Objective

The main objective of this project is to analyze customer and loan-related data to understand:

* Customer credit profiles
* Loan application patterns
* Credit score distribution
* Loan amounts and income levels
* Loan approval and rejection trends
* Customer risk categories
* Default probability
* Debt-to-income ratio
* Late payment behavior
* Loan-type performance
* State-wise loan activity
* Application trends over time

The analysis can help financial institutions better understand **credit risk, customer behavior, lending patterns, and potential high-risk segments**.

---

# 🛠️ Tools & Technologies

| Tool                               | Purpose                                    |
| ---------------------------------- | ------------------------------------------ |
| 📗 Microsoft Excel                 | Data exploration and analysis              |
| 🗄️ SQL                            | Data querying and business analysis        |
| 📊 Power BI                        | Interactive visualization and dashboarding |
| 📁 CSV/Excel-style structured data | Source dataset                             |

---

# 📂 Project Files

### 1. 📗 `Credit Analysis FINAL.xlsx`

The Excel workbook contains the credit-analysis dataset used as the analytical foundation of the project.

The dataset contains customer and financial attributes such as:

* Customer ID
* Customer Name
* Date of Birth
* Age
* Marital Status
* Education
* Employment Type
* City & State
* Annual Income
* Credit Score
* Loan Amount
* Loan Type
* Loan Tenure
* Interest Rate
* Debt-to-Income Ratio
* Monthly Debt
* Loan Status
* Risk Category
* Application Channel
* Application Date
* Default Probability
* Utilization Ratio
* Existing Loans
* Late Payments

This provides the base data required for both SQL analysis and Power BI reporting.

---

# 🗄️ 2. `credit_analysis in SQL(corrected)(1).sql`

The SQL file creates and works with a `credit_analysis` database and a `credit_data` table containing customer, financial, loan, and risk-related fields.

The SQL analysis goes beyond simple data retrieval and includes multiple business-focused queries.

### 🔍 Key SQL Analysis

#### 📌 Overall Credit Metrics

* Total number of customers
* Average credit score
* Average annual income
* Total loan amount

#### 📌 Loan Status Analysis

Analysis of:

* Approved applications
* Rejected applications
* Pending applications
* Other loan statuses

#### 📌 Risk Analysis

Customers are analyzed according to their:

* Low risk
* Medium risk
* High risk
* Very High risk

The analysis also compares credit scores and default probabilities across risk categories.

#### 📌 Loan Type Analysis

The project evaluates different loan types based on:

* Number of applications
* Total loan amount
* Average interest rate
* Average credit score

#### 📌 Geographic Analysis

State-wise analysis is performed to understand:

* Number of customers
* Total loan value
* Average credit score

#### 📌 High-Risk Customer Identification

The SQL queries identify customers with:

* High or Very High risk
* High default probability
* Poor credit scores
* High debt-to-income ratios

#### 📌 Financial Risk Indicators

The analysis specifically examines:

* Debt-to-income ratio
* Monthly debt
* Default probability
* Existing loans
* Late payments
* Credit score

#### 📌 Approval & Rejection Rates

SQL queries calculate the overall:

* Loan approval rate
* Loan rejection rate

#### 📌 Advanced Analysis

The project also includes:

* Customer ranking by loan amount using `RANK()`
* High-risk + high-DTI customer identification
* Late-payment analysis
* Monthly application trends

These queries provide a strong foundation for understanding both **customer-level risk and overall lending performance**.

---

# 📊 3. `PowerBI_Report_GITHUB(2).pbix`

The Power BI file transforms the credit dataset and analysis into an interactive reporting experience.

The report is organized into four major analytical sections:

### 🏠 Executive – Loan Overview

Provides a high-level view of the overall loan portfolio and key credit metrics.

### 📈 Loan Performance Analysis

Focuses on loan performance and application patterns, helping understand how different loan segments are performing.

### 🛡️ Credit & Risk Analysis

Provides deeper insights into:

* Credit scores
* Risk categories
* Default probability
* Customer risk
* Debt-related indicators

### 👥 Customer & Financial Analysis

Provides a customer-focused view of:

* Customer characteristics
* Income
* Credit behavior
* Loan information
* Financial indicators

---

# 🔄 Project Workflow

The overall workflow of the project can be represented as:

```text
Credit Dataset
      ↓
   Excel
      ↓
Data Exploration & Preparation
      ↓
     SQL
      ↓
Business Queries & Risk Analysis
      ↓
   Power BI
      ↓
Interactive Dashboard
      ↓
Business Insights & Decision Support
```

---

# 💡 Key Business Questions

This project can help answer questions such as:

1. What is the overall credit profile of customers?
2. What is the average credit score?
3. What is the total loan exposure?
4. Which loan types have the highest loan amounts?
5. Which states have the highest lending activity?
6. What proportion of applications are approved or rejected?
7. Which customers fall into high-risk categories?
8. Which customers have high debt-to-income ratios?
9. How does default probability vary across risk categories?
10. Which loan types have higher average interest rates?
11. How do late payments vary across risk categories?
12. How does loan application activity change over time?

---

# 📌 Important Risk Indicators

The project uses several important indicators to understand credit risk:

### 💳 Credit Score

A customer's credit score provides an important indication of their credit profile.

### 💰 Annual Income

Income helps provide context for a customer's borrowing capacity.

### 🏦 Loan Amount

Loan amount is analyzed in relation to income and other financial indicators.

### 📉 Debt-to-Income Ratio

DTI helps identify customers carrying relatively high debt compared with their income.

### ⚠️ Default Probability

Default probability provides an additional indicator for identifying potentially risky customers.

### 🕒 Late Payments

Late-payment behavior can help identify patterns associated with credit risk.

### 📊 Risk Category

Customers are grouped into different risk levels to support easier segmentation and analysis.

---

# 📊 Dashboard Highlights

The Power BI report brings the analysis together into an interactive dashboard experience, allowing users to explore the credit portfolio from different perspectives.

The report covers four major perspectives:

**Executive Overview → Loan Performance → Credit & Risk → Customer & Financial Analysis**

This makes it possible to move from a high-level portfolio view into more detailed customer and risk analysis.

---

# 🚀 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis
* Data Cleaning & Preparation
* Excel Analysis
* SQL
* SQL Aggregations
* `GROUP BY`
* Filtering & Conditional Analysis
* Window Functions
* Risk Segmentation
* Financial Data Analysis
* Credit Risk Analysis
* Business Intelligence
* Power BI Dashboard Development
* Data Visualization
* Business Insight Generation

---

# 📁 Repository Structure

```text
Credit-Analysis/
│
├── 📗 Credit Analysis FINAL.xlsx
│
├── 🗄️ credit_analysis in SQL(corrected)(1).sql
│
├── 📊 PowerBI_Report_GITHUB(2).pbix
│
└── 📄 README.md
```

---

# 🎓 Project Outcome

This project demonstrates how raw credit and loan data can be transformed into meaningful business intelligence using multiple analytical tools.

**Excel** provides the foundation for working with the dataset, **SQL** enables structured and detailed business analysis, and **Power BI** converts the findings into an interactive visual reporting solution.

Together, the three files demonstrate a complete **data analytics workflow from raw data to business insights**.

---

## ⭐ Conclusion

Credit analysis is not only about looking at individual credit scores. It requires combining customer demographics, income, loan characteristics, repayment behavior, debt levels, and risk indicators.

This project brings these dimensions together to provide a structured view of **loan performance, customer financial behavior, and credit risk**.

---

### 🔗 Project Files

📗 **Excel:** Credit Analysis FINAL.xlsx
🗄️ **SQL:** credit_analysis in SQL(corrected)(1).sql
📊 **Power BI:** PowerBI_Report_GITHUB(2).pbix

---

## 💬 Feedback

I’m always open to feedback, suggestions, and ideas for improving the analysis or dashboard.

If you find this project useful, feel free to ⭐ **star the repository** and explore the files.
