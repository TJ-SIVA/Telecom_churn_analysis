# 📊 Customer Churn Analysis
## 📌 Project Overview
This project performs comprehensive churn analysis for a telecom dataset.
It includes data cleaning, EDA (Exploratory Data Analysis), statistical analysis, and visualizations to identify customer retention patterns and churn risk factors.

The analysis is done using Python (Pandas, Matplotlib, Seaborn), and also partially implemented in Tableau for interactive dashboards.

## 🗂 Dataset
Source: Telco Customer Churn Dataset
Key Columns:

customerid – Unique customer identifier

tenure – Number of months the customer has stayed

monthlycharges – Monthly subscription amount

totalcharges – Total amount charged to the customer

churn – Whether the customer left (Yes/No)

Multiple categorical variables like gender, contract type, internet service, payment method, etc.

## 🔍 Key Steps in the Project
- 1. Data Cleaning
Removed duplicates and handled missing values (e.g., totalcharges with tenure = 0).

Converted data types where necessary.

Ensured categorical/numerical separation for analysis.

- 2. Exploratory Data Analysis (EDA)
Numerical Variables:
Distribution plots (histograms) with mean and median lines.

Boxplots to detect outliers and compare churn vs retention.

Categorical Variables:
Frequency tables with percentages.

Mode (most frequent category) analysis.

- 3. Churn Analysis
Overall churn rate and retention rate.

Pie and bar charts for churn distribution.

Boxplots comparing numerical variables between churned vs retained customers.

Grouped churn rates by categorical features (e.g., contract type, payment method, internet service).

- 4. Advanced Analysis
Churn rate by tenure segments (0–12 months, 13–36 months, 37+ months).

Demographic analysis (gender, senior citizen status).

Churn rate by contract type and payment method.

Statistical significance testing using chi-square for categorical variables and t-tests for numerical variables.

- 5. Tableau Integration
Created interactive pie charts, bar charts, and heatmaps for churn rates.

Segmented customers by tenure and visualized churn distribution.

Built an interactive dashboard for quick exploration.

## 📈 Visualizations
### Some examples of charts produced in the project:

- Churn Distribution Pie Chart – Visualizing Yes/No churn percentages.

- Boxplots – Comparing monthly charges & tenure between churned and retained customers.

- Churn Rate Heatmaps – Comparing churn rates across contract types, internet services, etc.

- Tableau Dashboard – Interactive churn analysis and tenure segmentation.

## 🛠 Tools & Technologies
- Python – Pandas, NumPy, Matplotlib, Seaborn

- Tableau – Interactive data visualization

- Colab Notebook – For step-by-step EDA and analysis

- Git – Version control

## 🚀 How to Run
** Clone this repository: **

```
git clone https://github.com/TJ-SIVA/Telecom_churn-analysis.git
cd churn-analysis
```
Install dependencies:
```
pip install -r requirements.txt

```
Run the analysis:

jupyter notebook churn_analysis.ipynb
Open Tableau file (churn_dashboard.twbx) for interactive view.

## 📊 Project Structure

```
u[dated later
```
# 📌 Insights & Findings
- Customers with Month-to-Month contracts have significantly higher churn rates.

- Higher monthly charges are correlated with higher churn likelihood.

- Customers in the 0–12 month tenure segment churn more than those with longer tenure.

- Electronic check payment users show the highest churn rate.

## 📢 Next Steps
Apply Machine Learning models for churn prediction (Logistic Regression, Random Forest, XGBoost).

Build a real-time churn dashboard with Power BI or Streamlit.

Implement targeted retention strategies for high-risk customer groups.

## 👤 Author
Sivakumar Devaraj (Zuko)
Machine Learning Enthusiast | Aspiring AI Engineer
📧 Email: sivakumardevarajp@gmail.com
