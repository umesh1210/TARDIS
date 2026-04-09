# 🏥 TARDIS — Medical Insurance Data Warehouse & BI Project

A UK-based medical insurance analytics solution built for Torus, analyzing 
policy sales, renewals, claims, and revenue performance through a scalable 
Data Warehouse and optimized BI reports.

---

## 🎯 Project Objectives

- Build a scalable Data Warehouse using Star Schema modeling
- Develop ETL pipelines to load data from multiple source systems
- Enable strategic decision-making through Power BI & SSRS reporting
- Optimize aggregation and query performance using SSAS Tabular Model

---

## 🏗️ Architecture

- Source Systems (SQL Server / Excel / Flat Files)
- Staging Layer (SSIS ETL Processing)
- Enterprise Data Warehouse (Star Schema)
- SSAS Tabular Model (Aggregation Layer)
- Power BI & SSRS Reports

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| SQL Server (T-SQL) | Data extraction, stored procedures & views |
| SSIS | ETL development & incremental loads |
| SSAS Tabular Model | Aggregation & performance optimization |
| SSRS | Operational reporting (40+ reports) |
| Power BI | Interactive dashboards & KPI tracking |
| TFS | Version control & deployment |

---

## 🗂️ Data Model

**Fact Tables**
- Premium
- Limit
- Deduction

**Dimension Tables**
- Policy, Policy Section, Policy Coverage
- Transaction Type, Revenue Type, Currency

> Star Schema implemented for optimized analytical querying.

---

## ⚙️ Key Responsibilities

- Developed 30+ SSIS packages for full and incremental loads
- Implemented ETL transformations using Lookup, SCD, and Merge logic
- Designed custom logging framework for ETL monitoring
- Built SSAS Tabular Model for aggregated reporting
- Developed 100+ SSRS reports
- Designed Power BI dashboards with business KPIs
- Deployed SSIS packages using ISPAC & SSIS Catalog

---

## 📊 Key Business KPIs

- Branch-wise Revenue & Bottom Performing Branches
- Year-wise Revenue Growth
- Policy Renewal Ratio & New vs Renewal Customer Ratio
- Top 5 Brokers by Revenue
- Top 5 Policies by Revenue
- Claim Settlement Trends

---

## 🚀 Business Value

- Enabled trend analysis for policy renewals and revenue growth
- Improved reporting performance using SSAS aggregation layer
- Provided strategic insights for branch and broker performance
- Processed 30–40 million monthly records across multiple source systems
