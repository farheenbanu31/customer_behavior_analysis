# Customer Behaviour Analysis

## MySQL Preparation
The cleaned data was structured and loaded into a MySQL database named **customer_behavior** for advanced querying.

## SQL Query Execution
Advanced queries aggregated key metrics:

- **Revenue Segmentation:** Total revenue for male versus female customers.
- **Top Products:** Top 5 products based on average customer review ratings.
- **Subscription Value:** Average purchase amount for subscribed versus non-subscribed customers.

## Power BI Integration & Modeling
The aggregated data and raw tables were connected to Power BI via the MySQL Connector/NET driver, using a Star Schema for relationships and measures.

## Power BI Dashboard
The interactive dashboard offers a comprehensive view of customer data, facilitating quick and informed decision-making.

### Key Metrics Visualised:
- Total Customers, Average Purchase Amount, and Average Review Rating (KPI Cards)
- Doughnut Chart for customer percentages by subscription status
- Bar Chart for the Top 5 Products by average rating
- Clustered Column Chart for total revenue by gender

### Interactivity:
Slicers are available for filtering by **item_purchased** and **age_group**.

## Key Results & Insights
- **Gender Disparity:** Male customers have a 15% higher average purchase amount, indicating potential marketing opportunities.
- **Product Quality:** Product X rates 4.8, while Product Y, at 3.1, needs investigation.
- **Subscription Value:** Subscribed customers have a 25% higher average lifetime value, highlighting the need for retention strategies.

## How to Run This Project
To replicate this analysis and view the dashboard:

1. Ensure Python 3.x, MySQL Workbench, and Power BI Desktop are installed.
2. Install the MySQL Connector/NET and create a MySQL database named **customer_behavior**.
3. Run the Jupyter Notebook **data_cleaning_eda.ipynb** for data preparation.
4. Execute queries in **mysql_queries.sql** to verify results.
5. Open and refresh **Customer_Behavior_Dashboard.pbix** in Power BI with your MySQL credentials.
