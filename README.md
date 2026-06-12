# E-Commerce Sales Data Analytics Project

## 📌 Project Overview
This is an end-to-end Data Analytics project that demonstrates how to generate, clean, analyze, and visualize e-commerce sales data. The project bridges the gap between data engineering (using Python) and business intelligence (using Power BI) to deliver actionable insights for an online retail business.

## 🛠️ Tech Stack Used
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Random (for synthetic data generation)
* **BI Tool:** Power BI Desktop
* **Data Format:** Excel / CSV

---

## ⚙️ Project Workflow (Step-by-Step)

### 1. Data Generation & Ingestion
* Developed a Python script utilizing the `random` library to generate a synthetic dataset of **1,000+ sales transactions**.
* Attributes generated include: `OrderID`, `OrderDate`, `Category`, `Price`, `Quantity`, `PaymentMethod`, and `City`.

### 2. Data Cleaning & Wrangling (Pandas)
* Handled **duplicate rows** by identifying and removing them permanently using `.drop_duplicates()`.
* Managed **missing values** in the `City` column by replacing null values with `'Unknown'` via the modern Pandas `.fillna()` method.
* Ensured consistent data types across all columns before exporting the final dataset as `cleaned_ecommerce_data.csv`.

### 3. Business Intelligence & Dashboarding (Power BI)
* Imported the cleaned dataset into Power BI Desktop.
* Created key performance indicators (**KPI Cards**) for *Total Sales* and *Total Items Sold*.
* Designed a **Treemap** to display revenue contribution by product category.
* Developed a **Clustered Bar Chart** to track order volume across different cities.
* Formatted an advanced **Matrix Heatmap** utilizing conditional formatting to discover payment preferences across product categories.

---

## 📊 Key Business Insights Discovered
* **Top Performing Category:** Identified the product category driving the highest percentage of total revenue.
* **Geographic Hotspots:** Mapped the top cities contributing the maximum number of order placements.
* **Customer Behavior:** Uncovered the most preferred payment method used by customers for high-value purchases.
