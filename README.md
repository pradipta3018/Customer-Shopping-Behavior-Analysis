# Customer Shopping Behavior Analysis

**End-to-End Data Analytics Project | Python • PostgreSQL • Power BI**

## Overview

This project analyses customer shopping behaviour to identify purchasing trends, customer preferences, spending patterns, and subscription behaviour.

The project demonstrates a complete data analytics workflow, from data preparation and exploratory analysis using **Python** to business analysis using **PostgreSQL**, interactive dashboard development using **Power BI**, and communicating insights through a project report and **Gamma presentation**.

**Project Objective:** Transform raw customer transaction data into meaningful insights that support data-driven business decisions.

## Dataset

The dataset contains customer shopping transactions across different product categories.

| Dataset Information | Details |
|---|---|
| Total Records | 3,900 |
| Total Columns | 18 |
| Data Type | Customer shopping transactions |
| Missing Values | 37 values in Review Rating |

**Key Features:**
- Customer demographics: Age, Gender, Location, Subscription Status
- Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Colour
- Shopping behaviour: Discounts, Previous Purchases, Purchase Frequency, Review Ratings and Shipping Type

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data loading, EDA and cleaning |
| Pandas | Data manipulation and feature engineering |
| PostgreSQL | SQL queries and business analysis |
| SQLAlchemy | Python–PostgreSQL database connection |
| Power BI | Interactive dashboard and visualisation |
| Gamma | Project presentation |
| PDF / Word | Project documentation and reporting |

## Project Steps

### 1. Data Loading and Exploratory Data Analysis (EDA)

- Loaded the dataset into Python using Pandas.
- Examined the dataset structure using `df.info()`.
- Generated descriptive statistics using `df.describe()`.
- Identified missing values and checked data consistency.
- Explored customer demographics, spending behaviour and product preferences.

### 2. Data Cleaning and Feature Engineering

- Handled 37 missing values in `review_rating` using category-wise median values.
- Standardised column names to snake_case.
- Created an `age_group` column for customer segmentation.
- Created a `purchase_frequency_days` feature.
- Removed the redundant `promo_code_used` column after checking its relationship with `discount_applied`.
- Prepared the cleaned dataset for database analysis.

### 3. PostgreSQL Database Integration

- Connected Python to PostgreSQL.
- Loaded the cleaned DataFrame into the database.
- Used SQL queries to answer business-related questions.

**SQL Analysis Included:**
1. Revenue comparison by gender
2. High-spending customers using discounts
3. Top-rated products
4. Average spending by shipping type
5. Subscribers vs. non-subscribers
6. Products most dependent on discounts
7. Customer segmentation
8. Top-selling products by category
9. Repeat buyers and subscription behaviour
10. Revenue by age group

### 4. Power BI Dashboard Development

Developed an interactive **Customer Behavior Dashboard** to communicate the analytical findings.

**Dashboard Features:**
- Total customer count
- Average purchase amount
- Average review rating
- Subscription distribution
- Revenue and sales by product category
- Revenue and sales by age group
- Interactive slicers for customer and purchase attributes

## Dashboard

<img width="1322" height="733" alt="image" src="https://github.com/user-attachments/assets/e6723c27-d6e8-47b1-ab5b-74c71dcbc2c3" />

*Add the dashboard screenshot to the `images` folder.*

The dashboard enables users to explore shopping patterns, compare customer segments, and identify opportunities to improve business performance.

## Results & Key Insights

The analysis produced several insights into customer behaviour:

- **Total Customers:** 3,900
- **Average Purchase Amount:** $59.76
- **Average Review Rating:** 3.75
- **Subscription Behaviour:** Approximately 27% of customers were subscribers, while 73% were non-subscribers.
- **Customer Segmentation:** The largest segment was classified as Loyal.
- **Product Ratings:** Gloves, Sandals and Boots were among the highest-rated products.
- **Shipping Preferences:** Express shipping customers had a slightly higher average purchase amount than Standard shipping customers.

### Business Recommendations

- Introduce targeted campaigns to increase subscriptions.
- Strengthen loyalty programmes for repeat customers.
- Review discount strategies to balance sales and profitability.
- Promote highly rated and popular products.
- Focus marketing efforts on valuable customer segments.

## Project Report & Presentation

A detailed project report was prepared to document the data cleaning process, SQL analysis, dashboard development and business recommendations.

A professional presentation was also created using **Gamma** to communicate the project workflow, findings and conclusions.

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy sqlalchemy psycopg2-binary
   ```

3. Open the Python notebook or script.
4. Update the dataset file path and load the data.
5. Run the EDA and data-cleaning steps.
6. Configure the PostgreSQL connection using your own database credentials.
7. Execute the SQL queries to reproduce the business analysis.
8. Open the `.pbix` file in Power BI Desktop and update the data source if required.
9. Explore the dashboard and review the project report and Gamma presentation.

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── shopping_behavior.csv
│   └── cleaned_shopping_data.csv
│
├── notebooks/
│   └── customer_analysis.ipynb
│
├── sql/
│   └── business_analysis.sql
│
├── dashboard/
│   └── customer_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── reports/
│   └── customer_analysis_report.pdf
│
├── presentation/
│   └── gamma_presentation.pdf
│
└── README.md
```

*The structure above is suggested. Adjust the filenames and folders to match your repository.*

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Feature Engineering
- Python and Pandas
- PostgreSQL and SQL Querying
- Database Integration
- Power BI Dashboard Development
- Data Visualisation and Storytelling
- Business Insights and Reporting

## Conclusion

This project demonstrates my ability to complete an **end-to-end data analytics project**, from working with raw datasets to delivering actionable business insights.

It strengthened my practical skills in **Python, SQL, PostgreSQL, Power BI and analytical reporting**, while developing my ability to communicate findings clearly to business stakeholders.

---

**Author:** Pradipta Nilav Saha 
**LinkedIn:** https://www.linkedin.com/in/pradipta-nilav-saha/ 
**GitHub:** https://github.com/pradipta3018
