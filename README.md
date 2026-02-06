# Enterprise Sales & Customer Analytics – Power BI

## Overview
This project delivers an **enterprise-grade analytical reporting solution** built in **Power BI**, designed using **financial-services-level data architecture and semantic modeling standards**.

The solution provides executives and analysts with a **single source of truth** for monitoring **revenue, profit, orders, returns, customer value, and geographic performance**, while enabling **advanced analytical exploration** through AI visuals and What-If analysis.

---

## Business Objectives
- Track **Revenue, Profit, Orders, and Return Rate** across time
- Identify **top products, categories, and regions**
- Analyze **customer value and behavior**
- Evaluate **pricing impact** using What-If simulations
- Support **self-service analytics** with governed metrics

---

## Architecture & Data Model
- **Star Schema** with clear fact/dimension separation
- **Fact Tables**: Sales, Returns  
- **Dimensions**: Calendar, Customer, Product, Category/Subcategory, Territory
- **Supporting Tables**:
  - Central **Measure Table** (semantic layer)
  - Metric selection tables
  - Price Adjustment (%) What-If parameter

**Design principles**
- One-directional relationships
- Calendar marked as Date table
- Measures isolated from visuals
- No duplicated business logic

---

## Semantic Layer (DAX Measures)
All KPIs are centralized in a governed **Measure Table**, ensuring consistency and scalability.

**Core KPIs**
- Total Orders
- Total Revenue
- Total Profit
- Total Returns

**Advanced Analytics**
- YTD and MoM metrics
- Rolling revenue and profit
- Target vs Actual and variance
- Return rates and contribution %
- Customer value and order behavior
- Adjusted Revenue/Profit via What-If pricing

This structure mirrors **enterprise BI semantic layers** used in large financial institutions.

---

## Reporting Capabilities
- **Executive Dashboard** – KPI snapshot, trends, targets
- **Geospatial Analysis** – Global performance by region
- **Product Analytics** – Category/product drilldowns and pricing simulation
- **Customer Analytics** – Segmentation and revenue concentration
- **AI Visuals** – Key Influencers, Decomposition Tree, Natural Language Q&A
- **UX Enhancements** – Bookmarks and dynamic navigation

---

## Governance & Performance
- Sample/anonymized data only
- No credentials stored in PBIX
- Optimized DAX using VAR patterns
- Star schema for performance and clarity
- Reusable, extensible model design

---

## Technology Stack
Power BI • DAX • Power Query (M) • Dimensional Modeling • AI Visuals • GitHub

---

## Portfolio Context
This project demonstrates **enterprise BI architecture**, **semantic modeling discipline**, and **executive-ready analytics**, reflecting the standards used in **banking, capital markets, and large-scale enterprise analytics teams**.

---

## Author
**Harika Murari**  
Data Engineer | BI Engineer  
Power BI • DAX • SQL • Analytics Engineering
