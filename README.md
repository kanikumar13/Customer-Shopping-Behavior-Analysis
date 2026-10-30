## Customer-Shopping-Behavior-Analysis-Portfolio Project
This dataset contains information about 3,900 customers and their purchase behavior in an e-commerce setting. The data spans various customer demographics, purchase preferences, and transactional details. It is designed to help analyze customer behavior, shopping patterns, and marketing effectiveness.

## 1. Project Overview
This project focuses on analyzing customer shopping behaviour to identify purchasing patterns, customer preferences, and business insights.

The project follows an end-to-end data analytics workflow, starting with raw data collection and cleaning in Python, followed by exploratory data analysis (EDA), SQL analysis using MySQL, and interactive dashboard development in Power BI.

The final insights are presented through a project report and a PowerPoint presentation created using Gamma.

## Objective: 
To transform raw customer data into meaningful business insights that can help improve marketing strategies, customer engagement, and business decisions.


## 2. Dataset

- Dataset: Customer Shopping Behaviour
- Records: 3,900 customer records
- Data Type: Customer demographics, shopping preferences, and transaction details.
- Key Information:
     - Customer ID
     - Age and Gender
     - Item Purchased
     - Category and Purchase Amount
     - Season and Location
     - Review Rating
     - Discount and Subscription Status
     - Previous Purchases
 
## 3. Tools & Technologies

### Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data loading, cleaning, and EDA |
| Pandas | Data manipulation and transformation |
| Jupyter Notebook | Python development and analysis |
| MySQL | Database management and SQL analysis |
| Power BI | Interactive dashboard and visualization |
| Gamma AI | PowerPoint presentation |
| GitHub | Project documentation and version control |

## 4. Project Workflow

### Step 1: Data Loading

- Imported the dataset into Python using Pandas.
- Inspected the dataset structure, columns, and data types.
- Checked the number of rows and columns.

### Step 2: Exploratory Data Analysis (EDA)

- Analyzed customer demographics and purchasing patterns.
- Examined product categories and purchase amounts.
- Identified trends in customer preferences.
- Checked missing values and duplicate records.

### Step 3: Data Cleaning & Transformation

- Checked for missing values; no missing values were found.
- Checked and handled duplicate records, if any.
- Created age groups to segment customers.
- Converted purchase frequency into numerical days.
- Standardized column names using snake_case.
- Checked data consistency and removed redundant columns.
- Prepared the cleaned dataset for MySQL analysis.Payment and Shipping Preferences.

### Step 4: SQL Analysis Using MySQL

- Loaded the cleaned dataset into MySQL.
- Performed SQL queries to analyze customer purchasing behaviour.
- Used GROUP BY, ORDER BY, WHERE, HAVING, CASE, and aggregate functions.
- Analyzed customer segments, product performance, discounts, and subscription patterns.
- Identified key business trends from the query results.

### Step 5: Power BI Dashboard

- Connected Power BI to the MySQL database.
- Prepared data for visualization.
- Created KPI cards, charts, and interactive visuals.
- Developed dashboards to highlight customer behaviour and purchasing trends.

### Step 6: Project Report & Presentation

- Documented the project methodology, analysis, and findings in a report.
- Created a PowerPoint presentation using Gamma AI.
- Presented key insights and business recommendations in a clear and visual format.

  ## 5. Power BI Dashboard

  The interactive dashboard highlights:

    - Customer demographics and distribution.
    - Revenue and purchase behaviour.
    - Product category performance.
    - Customer subscription patterns.
    - Discount usage and purchasing trends.
    - Customer segmentation.


### Dashboard Screenshot:

Add your Power BI dashboard screenshot here.

![Power BI Dashboard](screenshots/dashboard.png)

## 6. Key Results & Business Insights

The analysis focuses on identifying:

- Customer purchasing patterns across different age groups.
- Revenue contribution by gender and customer segments.
- Purchasing differences between subscribers and non-subscribers.
- Products and categories with higher purchase activity.
- Impact of discounts on purchasing behaviour.
- Customer loyalty based on previous purchase history.

### Business Value:
The findings help businesses understand customer preferences, identify valuable customer segments, evaluate promotional strategies, and make data-driven marketing decisions.


## 7. Project Folder Structure


```text
Customer-Shopping-Behaviour-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── customer_shopping_analysis.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── customer_shopping_dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── Presentation/
│   └── project_presentation.pdf
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

## 8. How to Run the Project

Prerequisites:

- Python
- Jupyter Notebook
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Steps:
1. Clone or download this GitHub repository.
2. Download and place the dataset in the Dataset folder.
3. Open the Jupyter Notebook.
4. Install the required Python libraries:

pip install pandas numpy matplotlib seaborn sqlalchemy pymysql

5. Run the Python notebook to perform data cleaning and EDA.
6. Import the cleaned dataset into MySQL.
7. Execute the SQL queries in MySQL Workbench.
8. Open the Power BI file and connect it to your MySQL database.
9. Refresh the dashboard to view the analysis.
10. Review the final project report and Gamma presentation.

## 9. Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI.

It showcases practical skills in data cleaning, exploratory data analysis, database querying, data visualization, business reporting, and storytelling.

The project highlights how raw customer data can be transformed into actionable insights to support better business decisions.


### Skills Demonstrated: Python | Pandas | EDA | Data Cleaning | MySQL | SQL | Power BI | Data Visualization | Business Analysis | Reporting | Data Storytelling


## Power BI Dashboard

![Dashboard](screenshots/dashboard.png)
