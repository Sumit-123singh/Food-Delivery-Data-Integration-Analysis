# Food Delivery Data Integration and Analysis

This project demonstrates how to integrate and analyze food delivery data from multiple real-world sources such as CSV, JSON, and SQL using Python and Pandas. The goal is to create a unified dataset and extract meaningful business insights related to orders, users, revenue, and restaurant performance.

---

## 📌 Project Overview

In real-world systems, data often exists in different formats. This project simulates such a scenario by combining:
- Transactional order data (CSV)
- User master data (JSON)
- Restaurant master data (SQL)

The integrated dataset is then used to perform analytical queries and answer business-driven questions.

---

## 📂 Data Sources

- **orders.csv** – Order-level transactional data  
- **users.json** – User details including membership information  
- **restaurants.sql** – Restaurant details including cuisine and ratings  

---

## 🔧 Technologies Used

- Python
- Pandas
- SQLite
- Jupyter Notebook
- Git & GitHub

---

## 🔄 Data Integration Steps

1. Load CSV, JSON, and SQL datasets
2. Perform LEFT JOIN operations using Pandas
3. Merge datasets using appropriate keys:
   - `user_id`
   - `restaurant_id`
4. Create a final consolidated dataset for analysis

---

## 📊 Analysis Performed

- Order trends and revenue analysis
- User behavior analysis (Gold vs Regular members)
- City-wise and cuisine-wise performance
- Restaurant rating impact on revenue
- Seasonal and quarterly revenue trends

---

## 📁 Project Structure

```Food-Delivery-Data-Integration-Analysis/
├── data/
│   ├── orders.csv                # Transactional order data
│   ├── users.json                # User master data
│   └── restaurants.sql           # Restaurant master data
│
├── notebook/
│   └── food_delivery_analysis.ipynb   # Jupyter notebook with integration & analysis
│
├── output/
│   └── final_food_delivery_dataset.csv   # Final merged dataset
│
├── README.md                     # Project documentation




