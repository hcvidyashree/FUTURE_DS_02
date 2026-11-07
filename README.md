# Customer Retention & Churn Analysis

## Project Overview
This project analyses customer churn using the IBM Telco Customer Churn dataset. The objective is to identify customer segments with higher churn rates, understand factors associated with customer attrition, and develop data-driven recommendations to improve customer retention.

## Dataset
- **Source:** [IBM Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Total Records:** 7,043 customers
- **Original Features:** 21 columns
- **Target Variable:** Churn

The dataset contains customer demographics, subscribed services, contract details, payment methods, tenure, monthly charges, total charges, and churn status.

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Power BI

## Project Workflow

1. **Data Collection:** Imported the IBM Telco Customer Churn dataset.
2. **Data Cleaning:** Handled blank values in `TotalCharges`, converted the column to numeric format, and checked for missing values and duplicate records.
3. **Exploratory Data Analysis:** Examined churn patterns across contracts, tenure, payment methods, internet services, and customer characteristics.
4. **Customer Segmentation:** Analysed customer groups to identify segments with higher churn rates.
5. **Dashboard Development:** Created an interactive Power BI dashboard to present key churn metrics and customer patterns.
6. **Business Recommendations:** Developed recommendations based on the analysis findings.

## Key Findings

- Overall customer churn rate: **26.54%**
- Customer retention rate: **73.46%**
- Month-to-month contract customers have a churn rate of **42.71%**.
- Electronic check users have a churn rate of **45.29%**.
- Fiber optic customers have a churn rate of **41.89%**.
- Customers who churned had a lower average tenure than retained customers.
- Customers without online security and technical support services showed higher churn rates.

## Business Recommendations

- Encourage month-to-month customers to consider longer-term contracts.
- Promote automatic payment methods.
- Improve customer support and engagement for fiber optic customers.
- Encourage adoption of online security and technical support services.
- Focus retention efforts on customers during their early tenure period.

## Project Structure

```text
FUTURE_DS_02/
│
├── data/
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
├── outputs/
│   ├── cleaned_customer_churn.csv
│   ├── overall_churn_summary.csv
│   ├── churn_factor_summary.csv
│   ├── tenure_retention_summary.csv
│   └── business_recommendations.csv
├── dashboard/
│   └── Customer_Churn_Dashboard.pbix
├── screenshots/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open `notebooks/Customer_Churn_Analysis.ipynb` in Jupyter Notebook.
4. Run the notebook cells in sequence.
5. Open the Power BI dashboard file from the `dashboard` folder using Power BI Desktop.

## Limitations

- The dataset is a historical snapshot and does not contain monthly customer activity records.
- Explicit customer churn reasons are not provided. The analysis identifies patterns and associations rather than confirmed reasons.
- The findings indicate associations and should not be interpreted as proof of causation.

## Project Context
**Internship:** Future Interns – Data Science & Analytics  
**Task:** Task 2 – Customer Retention & Churn Analysis