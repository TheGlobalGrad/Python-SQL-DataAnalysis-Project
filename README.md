## 📊 Python + SQL Data Analysis Project

### 🔍 Project Overview

This project demonstrates the integration of **Python** and **SQL** for effective data analysis. Using Jupyter Notebook, it covers end-to-end steps — from data extraction using SQL to exploratory data analysis (EDA) and data visualization using Python libraries.

It is based on an e-commerce dataset, involving key entities like customers, orders, sellers, payments, and more.

### 🧰 Technologies Used

* **Python 3.x**
* **MySQL**
* **Jupyter Notebook**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **MySQL Connector**

### 📂 Dataset Summary

The dataset includes the following CSV files:

* `customers.csv`
* `orders.csv`
* `sellers.csv`
* `products.csv`
* `geolocation.csv`
* `payments.csv`
* `order_items.csv`

These are imported into MySQL and accessed using SQL queries in the notebook.


### ✅ Features / Tasks Performed

* 📥 **Loading CSVs into MySQL database**
* 🔎 **Running SQL queries** from Python
* 📊 **Data cleaning and manipulation** using Pandas
* 📈 **Visualization** using Seaborn and Matplotlib
* 🗂️ **Joins and aggregations** to explore relationships between:

  * Customers & Orders
  * Sellers & Revenue
  * States & Order Count
  * Payments & Order Value
* 📆 **Monthly trends**, top-performing sellers, spendthrift customers, and more


### 📸 Sample Visuals

* Bar plots of revenue by sellers
* Heatmaps for state-wise order distributions
* Time-series plots for monthly trends

### 🚀 How to Run This Project

1. Clone this repo:

   ```bash
   git clone https://github.com/TheGlobalGrad/Python-SQL-DataAnalysis-Project.git
   cd project-name
   ```

2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn mysql-connector-python jupyter
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook
   ```

4. Set up your MySQL server and import the CSVs to create the necessary tables.

5. Execute cells sequentially to see analysis and visuals.


### 📌 Notes

* Make sure your MySQL server is running and credentials in the notebook are correctly set.
* Data visualizations are created using Seaborn and Matplotlib for better insights.
