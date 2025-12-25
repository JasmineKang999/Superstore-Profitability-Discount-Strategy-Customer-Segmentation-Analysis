# Superstore Profitability Discount Strategy & Customer Segmentation Analysis


## Project Overview
This project performs a deep dive into the Superstore dataset to uncover business trends and optimize customer management. By analyzing transactional data, the project aims to identify profitable product categories, regional performance, and, most importantly, segment customers based on their purchasing behavior.

## Objectives:
* **Business Insight**: Analyze sales and profit trends across time, geography, and product categories.
* **Customer Profiling**: Build an RFM (Recency, Frequency, Monetary) model to quantify customer value.
* **Precision Marketing**: Apply the K-Means Clustering algorithm to group customers into distinct segments for targeted operations.

---

## Dataset Description
The dataset contains historical retail transactions with the following key attributes:
* **Order Details**: Order ID, Order Date, Ship Date, Ship Mode.
* **Customer Information**: Customer ID, Customer Name, Segment.
* **Geographic Data**: Country, City, State, Postal Code, Region.
* **Product Metrics**: Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit.

---

## Tech Stack
* **Language**: Python
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-learn (K-Means)
* **Analysis Methodology**: RFM Analysis, Elbow Method

---

## Analysis Pipeline
1.  **Data Preprocessing**:
    * Cleaning missing values and handling outliers.
    * Feature engineering (extracting Year, Month, and Quarter from Order Date).
2.  **Exploratory Data Analysis (EDA)**:
    * Visualizing monthly sales growth and seasonal trends.
    * Identifying top-performing categories (e.g., Technology vs. Furniture).
    * Analyzing profit margins by region and state.
3.  **Customer Segmentation (RFM & ML)**:
    * **RFM Calculation**: Calculating Recency (days since last purchase), Frequency (total orders), and Monetary (total spend) for each customer.
    * **Scaling**: Standardizing data using `StandardScaler`.
    * **Clustering**: Using the Elbow Method to determine the optimal number of clusters and training the K-Means model.

---

## Key Insights & Results
* **Optimal Segments**: The project identified distinct customer groups (e.g., "Champions," "Loyal Customers," and "At-Risk Customers").
* **Actionable Strategies**:
    * **High-Value Group**: Focus on loyalty programs and exclusive previews.
    * **Churn-Risk Group**: Implement re-engagement campaigns with personalized discounts.
    * **Profitability**: Technology and Office Supplies drive the highest margins compared to Furniture.

---
