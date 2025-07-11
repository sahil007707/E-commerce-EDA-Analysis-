# 🛍️ E-Commerce Data Analysis & Insights


## 📊 Project Overview

This repository contains a detailed **Exploratory Data Analysis (EDA)** on a large-scale E-commerce dataset. The goal was to uncover insights from customer behavior, product trends, and transaction patterns to guide business decisions.

Through visualizations, aggregations, and data wrangling, this project dives deep into the e-commerce ecosystem, revealing what drives sales, returns, customer satisfaction, and more.

---

## 🧾 Dataset Description

The dataset used in this project includes information related to:
- Customer demographics
- Product categories
- Order dates and statuses
- Payment types
- Shipping timelines
- Review scores

> ⚠️ Note: Due to dataset size and privacy, it is not included here. You can refer to the competition or dataset source where applicable.

---

## 📌 Key Objectives

- Understand the flow from order placement to delivery.
- Explore patterns in customer behavior.
- Investigate relationships between product category, payment methods, and review scores.
- Identify bottlenecks in logistics and delivery delays.
- Support data-driven decision-making for business improvement.

---

## 📍 EDA Workflow

### 📦 1. Data Cleaning
- Checked for missing values and inconsistencies.
- Standardized datetime formats.
- Merged datasets based on `order_id` for enriched context.

### 📈 2. Exploratory Data Analysis
- Distribution analysis of key metrics (e.g. delivery time, purchase price).
- Trend analysis over time (sales volume, payment method usage).
- Product category performance and revenue contribution.
- Geographic customer segmentation by state and city.

### ⭐ 3. Review & Rating Analysis
- Correlation between delivery time and review score.
- Comparison of review trends across payment methods and product types.

### 🚚 4. Delivery Performance
- Analyzed shipping and delivery delays.
- Calculated average wait time, shipping time by seller, product, and location.

---

## 📌 Top Insights

- **Late Deliveries** significantly impact low review scores (1 and 2-star).
- **Credit card** is the most used payment method, but **boleto** is common among older demographics.
- **Apparel and electronics** had high return and cancellation rates.
- **Southeast regions** showed higher purchase volume, hinting at regional marketing opportunities.

---

## 📊 Visualizations

Used `matplotlib`, `seaborn`, and `plotly` to create:
- Heatmaps for correlation analysis.
- Bar plots for product and payment distribution.
- Histograms for delivery timelines.
- Time-series line plots for monthly trends.

---

## 🛠️ Tools & Technologies

| Category        | Libraries/Tools                        |
|----------------|----------------------------------------|
| Language        | Python                                 |
| Data Analysis   | pandas, numpy                          |
| Visualization   | matplotlib, seaborn, plotly            |
| Notebook        | Jupyter Notebook                       |

---
