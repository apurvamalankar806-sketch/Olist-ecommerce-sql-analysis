# Olist E-Commerce SQL Analysis

A business intelligence case study on 100,000+ Brazilian e-commerce orders 
using MySQL. This project explores sales distribution, customer behaviour, 
product performance, and revenue trends across a real-world dataset from 
Brazil's largest e-commerce marketplace.

---

## Dataset

Source: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- 99,441 orders placed between 2016–2018
- 9 relational tables: orders, customers, sellers, products, payments, reviews

---
## Tools Used

- MySQL — all analysis and querying
- Python (Pandas, SQLAlchemy) — data loading and visualisations
- Jupyter Notebook — charts and presentation

---

## Questions Explored

- How are orders distributed across different statuses?
- Which product categories drive the most orders?
- How is revenue distributed across Brazilian states?
- What is the average order value on the platform?
- Which payment methods do customers prefer?
- Which sellers generate the highest revenue?

---
## Key Findings

**Order fulfillment is highly reliable**
96.5% of 99,441 orders were successfully delivered, with a cancellation 
rate of just 0.6% — indicating a strong and consistent fulfillment 
pipeline across 2016–2018.

**Home and lifestyle dominate product demand**
Bed, bath and table products (cama_mesa_banho) is the top ordered category 
with 11,115 orders, followed by health & beauty (9,670) and sports & leisure 
(8,641) — reflecting strong demand for everyday home essentials.

**São Paulo drives the majority of revenue**
SP state accounts for R$5,067,633 in revenue across 40,501 orders — nearly 
3x the second largest state (RJ at R$1,759,651). The top 3 states (SP, RJ, MG) 
together represent over 60% of total platform revenue.

**Average order value sits at R$160**
At R$160.58 per order, the platform targets the mid-range consumer segment, 
consistent with Brazil's e-commerce market positioning.

**Credit card is the dominant payment method**
76,505 orders (77% of all transactions) were paid by credit card, generating 
R$12.5M in total payment value. Boleto (a Brazilian bank slip) is a distant 
second at 19,784 orders — reflecting typical Brazilian payment preferences.

---
## Project Structure

- `data/` — schema and table definitions
- `01_exploration/` — initial data exploration and sanity checks
- `02_revenue_analysis/` — top categories, revenue by state, payment methods
- `03_seller_performance/` — delivery delays, ratings, volume
- `04_cohort_analysis/` — customer retention by signup month
- `05_repeat_purchase/` — repeat purchase funnel and order gap analysis
- `visualisations/` — Python charts generated from SQL outputs

---

## Status

🔄 In progress — Phase 2 (Revenue Analysis) complete
