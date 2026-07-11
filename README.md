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

---

## Questions Explored

- How are orders distributed across different statuses?
- Which product categories drive the most orders and revenue?
- How did revenue trend month over month across 2016–2018?
- How is revenue distributed across Brazilian states?
- What is the average order value on the platform?
- Which payment methods do customers prefer?
- Which sellers generate the highest revenue?

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

- `data/` — schema and table definitions
- `olist_analysis.ipynb` — all SQL queries, analysis and visualisations

---

## Status

🔄 In progress — Phase 2 (Revenue Analysis) complete
