Customer Behavior Analysis

# Overview

This project analyzes a **Customer Shopping Behavior dataset** to understand purchasing patterns, customer demographics, and product trends.

The project follows a typical **data analytics workflow**, starting with data preprocessing, storing the cleaned dataset in a database, and finally building an interactive dashboard to visualize insights.

The analysis was performed using **Python for data processing, SQL for database management and querying, and Power BI for visualization**.

---

# Dataset

The project uses the **Customer Shopping Behavior dataset**, which contains **3900 records of customer transactions**.

The dataset includes information such as:

* Customer ID
* Age
* Gender
* Item Purchased
* Product Category
* Purchase Amount
* Review Rating
* Subscription Status
* Shipping Type
* Payment Method
* Frequency of Purchases

This dataset helps analyze **customer demographics, spending behavior, and shopping trends**.

---

# Tools & Technologies

* Python
* Pandas
* MySQL
* SQL
* SQLAlchemy
* Power BI

---

# Project Workflow

## Data Processing (Python – Pandas)

The dataset was explored and cleaned using Python. Missing values were handled, column names were standardized, and redundant columns were removed to improve the structure of the dataset.

Additional features were also created to support better analysis. Customers were grouped into **age categories**, and purchase frequency values were converted into numerical values to make them easier to analyze.

---

## Database Integration (SQL)

After preprocessing, the cleaned dataset was stored in a **MySQL database**. SQL was used to manage and query the dataset, allowing structured access to the data and making it easier to connect with visualization tools.

---

## Data Visualization (Power BI)

An interactive **Power BI dashboard** was created to visualize insights from the dataset. The dashboard provides a clear overview of customer behavior and purchasing trends.

Key metrics and visualizations included:

* Total number of customers
* Average purchase amount
* Average review rating
* Revenue distribution by age group
* Customer subscription status
* Product category performance

Interactive filters allow users to explore different aspects of the data.


# Project Structure

customer-behavior-analysis
│
├── customer_shopping_behavior.csv
├── data_processing.ipynb
├── sql_queries.sql
├── powerbi_dashboard.pbix
