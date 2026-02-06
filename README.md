# AdventureWorks-Harika
# Enterprise Sales & Customer Analytics – Power BI

## Executive Summary
This project delivers a **production-grade, enterprise analytics solution** built using **Power BI**, following **financial-services-level data architecture and BI governance practices**.

The solution enables executive leadership and analysts to monitor **revenue, profit, orders, returns, customer value, and geographic performance**, while supporting **advanced analytics capabilities** such as:
- AI-driven insights (Key Influencers, Decomposition Tree, Q&A)
- What-If price simulation
- Target vs Actual performance tracking
- Centralized semantic layer with governed DAX measures

This project is intentionally designed to reflect how **large financial institutions and global enterprises** implement analytical reporting platforms.

---

## Business Objectives
The solution answers the following strategic questions:

- How are **Revenue, Profit, Orders, and Returns** trending over time?
- Which **products, categories, and regions** drive the most value?
- Who are the **highest-value customers**, and how does behavior differ by segment?
- How do **returns and margins** vary across products?
- What factors **influence pricing and customer behavior**?
- How would **price changes impact revenue and profitability**?

---

## Architecture Overview

### Architectural Pattern
- **Star Schema (Dimensional Modeling)**
- Centralized **semantic layer**
- Measure-driven analytics
- Clear separation of:
  - Data
  - Business logic
  - Presentation

This architecture ensures **scalability, correctness, and performance**.

---

## Data Model

### Fact Tables
- **Sales Data**
  - Grain: One row per order line
  - Metrics: Quantity, Revenue, Profit
- **Returns Data**
  - Grain: One row per returned product
  - Metrics: Returned Quantity

### Dimension Tables
