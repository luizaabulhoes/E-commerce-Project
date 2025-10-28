# README — E-commerce Analysis Project (Target)

**Objective**
This project aims to analyze Target’s e-commerce data to extract insights and provide actionable recommendations. The analysis covers customers, orders, payments, deliveries, and regional performance.

---

## Exploratory Analysis Steps

1. **Dataset Structure and Data Types**

   * Identify the data type of each column in the `customers` table.
   * Determine the time range during which orders were placed.
   * Count the cities and states of customers who placed orders in the given period.

2. **In-depth Exploration**

   * Analyze whether there is a growing trend in the number of orders over the years.
   * Identify monthly seasonality patterns (peaks and drops in order volume).
   * Determine the time of day Brazilian customers most frequently place orders:

     * 0–6 hrs → **Dawn**
     * 7–12 hrs → **Morning**
     * 13–18 hrs → **Afternoon**
     * 19–23 hrs → **Night**

3. **Evolution of E-commerce in Brazil**

   * Calculate month-on-month orders per state.
   * Analyze customer distribution across all states.

4. **Economic Impact (Financial Movement)**

   * Calculate the percentage increase in order values from 2017 to 2018 (January–August).
   * Compute total and average order values per state.
   * Compute total and average freight values per state.

5. **Sales, Freight, and Delivery Time Analysis**

   * Calculate delivery time for each order (`order_delivered_customer_date - order_purchase_timestamp`).
   * Calculate the difference between estimated and actual delivery dates (`order_delivered_customer_date - order_estimated_delivery_date`).
   * Identify the top 5 states with the **highest and lowest average freight values**.
   * Identify the top 5 states with the **highest and lowest average delivery times**.
   * Identify the top 5 states where deliveries are **faster than estimated**.

6. **Payment Analysis**

   * Determine month-on-month orders by payment type.
   * Determine the number of orders by payment installments.
   * Reconfirm the top 5 states where deliveries are significantly faster than estimated.

---

## What “Good” Looks Like

* Clean and consistent data (≥95% completeness on key fields).
* Positive year-over-year order growth.
* Clearly identified monthly seasonality trends.
* At least 80% of orders delivered on or before the estimated date.
* Clear identification of high-volume states with efficient logistics performance.

---

## Expected Deliverables

* **Summary tables:** order volume, total and average order/freight value, delivery performance by state.
* **Visualizations:** monthly trends, seasonality patterns, hourly order distribution, and state-level heatmaps.
* **Insights & Recommendations:** clear next steps for logistics, marketing, and pricing teams.

---

### Credits

Documentation and analytical structure developed by **Nishtha Nagar**.
