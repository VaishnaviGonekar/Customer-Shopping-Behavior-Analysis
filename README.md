# Customer Shopping Behavior Analysis

A complete end-to-end data analytics project analysing retail customer transaction data to uncover purchasing patterns, identify high-value customer segments, and generate actionable business recommendations.

**Tools:** Python (Pandas) · PostgreSQL 16 · Power BI

---

## Overview

A retail company wants to better understand its customers' shopping behaviour in order to improve sales, customer satisfaction, and long-term loyalty. This project analyses 3,900 customer transaction records to answer the question:

> *"How can the company leverage consumer shopping data to identify purchasing trends, understand customer value, and optimise its marketing and product strategies?"*

The analysis is structured across three stages — Exploratory Data Analysis in Python, structured querying in PostgreSQL, and interactive visualisation in Power BI — producing a set of clear, evidence-based findings and recommendations.

---

## Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv           # Raw dataset (3,900 records)
├── Customer_Shopping_Behaviour.ipynb        # EDA notebook (Python / Pandas)
├── Customer_Behaviour_Analysis.sql          # SQL queries (PostgreSQL)
├── Customer_Behaviour_Dashboard.pbix        # Power BI dashboard
├── Customer_Shopping_Behaviour_Report.pdf  # Full written report
└── README.md
```

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, SQLAlchemy) | Data cleaning, feature engineering, export to PostgreSQL |
| PostgreSQL 16 / pgAdmin 4 | SQL-based business analysis (10 queries) |
| Power BI | Interactive dashboard and data visualisation |

---

## Dataset

- **Size:** 3,900 records · 18 columns
- **Content:** Retail customer transactions including purchase amount, product category, shipping type, review ratings, subscription status, and purchase history.

---

## Key Findings

- **Subscribers punch above their weight.** Subscribers are only 27% of customers but generate a disproportionately high share of total revenue, with a higher average spend per transaction than non-subscribers.
- **2,518 repeat buyers are not subscribed.** Among customers with more than 5 previous purchases, non-subscribers outnumber subscribers 2.6 to 1 — the highest-probability conversion pool in the dataset.
- **Clothing leads across all categories.** Clothing dominates both revenue and transaction volume, with Blouse, Pants, and Shirt as the top-purchased items.
- **Young Adults are the top revenue segment.** Young Adults generate €62,143 in total revenue, followed closely by Middle Age (€59,197).
- **Heavy discount dependency on key products.** Hat (50%), Sneakers (49.7%), and Coat (49.1%) have the highest discount rates — roughly every other sale is promotion-assisted, raising margin risk.
- **Customer base is mature but acquisition is thin.** 60% of customers are in the Loyal segment (21+ purchases); only 2% are New, signalling a gap in new customer acquisition.

---

## Report

The full written analysis — including methodology, SQL findings with insights, Power BI dashboard summary, and strategic recommendations — is available in `Customer_Shopping_Behaviour_Report.docx`.

---
