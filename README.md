# Olist E-Commerce SQL Analysis

A business intelligence case study on 100,000+ Brazilian e-commerce orders.
This project explores sales distribution, customer behaviour, product performance,
and revenue trends across a real-world dataset from Brazil's largest e-commerce
marketplace — combining SQL, Python, and Power BI into a full analytics workflow.

---


## Dataset

Source: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- 99,441 orders placed between September 2016 and August 2018
- 9 relational tables: orders, customers, sellers, products, payments, reviews

---

## Tools Used

- MySQL — data storage and querying
- Python (Pandas, SQLAlchemy, PyMySQL) — data loading and analysis
- Jupyter Notebook — SQL queries, analysis and visualisations
- Matplotlib — charts and graphs
- Power BI — interactive business dashboard

---
## Project Phases

### ✅ Phase 1 — Setup & Exploration
- Loaded all 9 tables into MySQL using Python + SQLAlchemy
- Fixed datetime inconsistencies
- Explored order status breakdown, top categories,
  customer distribution, and average order value

### ✅ Phase 2 — Revenue Analysis
- Monthly revenue trend (2016–2018)
- Top 10 product categories by orders
- Revenue distribution across Brazilian states
- Payment method breakdown by revenue
- Top sellers by revenue

### 🔄 Phase 3 — Seller Performance (up next)
- Delivery delay analysis (estimated vs actual)
- Best and worst performing sellers
- Seller ratings vs revenue correlation

### ⏳ Phase 4 — Customer Analysis
- Repeat vs one-time customers
- Cohort retention by signup month
- Time gap between 1st and 2nd order

### ⏳ Phase 5 — Power BI Dashboard
- Combined dataset exported from all 9 tables
- Interactive dashboard covering revenue, sellers,
  customers, and product performance

---

## Key Findings

**Order fulfillment is highly reliable**<br>
96.5% of 99,441 orders were successfully delivered, with a cancellation
rate of just 0.6% — indicating a strong and consistent fulfillment
pipeline across the 2016–2018 period.

**Strong and consistent revenue growth**<br>
Monthly revenue grew from R$40,325 in October 2016 to R$977,544 by
May 2018 — a 24x increase in under 2 years. A notable spike occurred
in November 2017 (R$987,765) driven by Black Friday, making it the
single highest revenue month in the dataset.

**Home and lifestyle dominate product demand**<br>
Bed, bath and table products (cama_mesa_banho) is the top ordered
category with 11,115 orders, followed by health & beauty (9,670) and
sports & leisure (8,641) — reflecting strong demand for everyday
home essentials.

**São Paulo drives the majority of revenue**<br>
SP state accounts for R$5,067,633 in revenue across 40,501 orders —
nearly 3x the second largest state (RJ at R$1,759,651). The top 3
states (SP, RJ, MG) together represent over 60% of total platform revenue.
SP also accounts for the highest number of cancellations, suggesting
volume and cancellation risk scale together.

**Average order value sits at R$160**<br>
At R$160.58 per order, the platform targets the mid-range consumer
segment, consistent with Brazil's e-commerce market positioning.

**Credit card is the dominant payment method**<br>
76,505 orders (77% of all transactions) were paid by credit card,
generating R$12.5M in total payment value. Boleto (a Brazilian bank
slip) is a distant second at 19,784 orders — reflecting typical
Brazilian payment preferences.

---

## Project Structure

olist-ecommerce-sql-analysis/
├── olist_analysis.ipynb
├── olist_combined.csv      ← for Power BI
├── charts/                 ← all saved charts
└── README.md

---

## Status

🔄 In progress — Phase 2 (Revenue Analysis) complete

