Customer Shopping Behavior Analysis

Overview


This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI to uncover valuable business insights. The workflow includes data cleaning, exploratory data analysis (EDA), SQL-based business analysis, interactive dashboard creation, and reporting.


The main objective of this project is to understand customer purchasing patterns, spending behavior, product preferences, and subscription trends to support data-driven business decisions.


Dataset


The dataset contains customer transaction and shopping behavior data.


Key Information
Total Records: 3,900+
Features Included:
Customer demographics
Purchase details
Product categories
Subscription status
Discounts and promo usage
Shipping preferences
Ratings and reviews
Sample Columns
Age
Gender
Location
Category
Item Purchased
Purchase Amount
Review Rating
Subscription Status
Discount Applied
Shipping Type
Tools & Technologies
Programming & Analysis
Python
Pandas
NumPy
Matplotlib
Seaborn
Database & SQL
PostgreSQL
MySQL
SQL Server
Visualization & Reporting
Power BI
Gamma (Presentation/PPT)
Jupyter Notebook
Project Workflow

1. Data Loading
Imported dataset using Pandas
Explored dataset structure using:
.info()
.describe()
.head()

3. Data Cleaning
Handled missing values
Renamed columns for consistency
Removed redundant columns
Checked data types and duplicates

5. Exploratory Data Analysis (EDA)

Performed analysis to identify:

Customer spending behavior
Product category trends
Gender-based purchasing patterns
Subscription impact
Seasonal purchase trends
Rating distributions

4. SQL Analysis

Executed SQL queries on PostgreSQL/MySQL/SQL Server to answer business questions such as:

Revenue by gender
Top-rated products
Subscriber vs non-subscriber spending
High-spending discount users
Customer segmentation
Revenue by age group
Top products per category
5. Power BI Dashboard


Created an interactive dashboard to visualize:

Sales trends
Customer segmentation
Revenue analysis
Product performance
Subscription insights
Purchase behavior
6. Reporting & Presentation
Generated a detailed project report
Created a professional presentation using Gamma
Dashboard Highlights

The Power BI dashboard includes:

KPI Cards
Revenue Trends
Customer Segmentation Charts
Product Performance Analysis
Subscription Insights
Interactive Filters & Slicers
Key Results & Insights
Identified top-performing product categories
Found high-value customer segments
Analyzed impact of discounts on purchases
Compared subscriber and non-subscriber behavior
Discovered revenue contribution by different age groups
Improved understanding of customer buying patterns
Project Structure

├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
├── sql/
│   └── customer_behavior_sql_queries.sql
├── dashboard/
│   └── customer_behavior_dashboard.pbix
├── reports/
│   └── Customer Shopping Behavior Analysis.pdf
├── presentation/
│   └── Gamma Presentation
└── README.md

How to Run the Project
1. Clone the Repository
git clone <repository-link>
cd customer-shopping-behavior-analysis
2. Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
3. Run Jupyter Notebook
jupyter notebook


Open:

Customer_Shopping_Behavior_Analysis.ipynb

4. Run SQL Queries
Import cleaned dataset into:
PostgreSQL
MySQL
SQL Server
Execute:
customer_behavior_sql_queries.sql

6. Open Power BI Dashboard

Open:

customer_behavior_dashboard.pbix
Future Improvements
Build machine learning models for customer prediction
Deploy dashboard online
Automate ETL workflows
Add real-time analytics
Conclusion


This project demonstrates end-to-end data analytics skills including:

Data cleaning
Exploratory Data Analysis
SQL querying
Data visualization
Dashboard development
Business reporting

It highlights practical business problem-solving using modern analytics tools and technologies.
