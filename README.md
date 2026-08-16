# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 📖 Project Overview

This project involves:

1. **Data Architecture:** Designing a modern Data Warehouse using Medallion Architecture with Bronze, Silver, and Gold layers.
2. **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

* SQL Development
* Data Architecture
* Data Engineering
* ETL Pipeline Development
* Data Modeling
* Data Analytics

---

## 🛠️ Important Links & Tools

- 📂 **Datasets:** [Project Datasets](datasets/)
- 🗄️ **SQL Server:** [Microsoft SQL Server](https://www.microsoft.com/sql-server)
- 💻 **SSMS:** [SQL Server Management Studio](https://learn.microsoft.com/sql/ssms/)
- 🐙 **GitHub:** [Project Repository](https://github.com/poonammaurya20012-sudo/sql-data-warehouse-project)
- 🎨 **Draw.io:** [diagrams.net](https://app.diagrams.net/)
---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

* **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
* **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
* **Scope:** Focus on the latest datasets only; historization of data is not required.
* **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### 🏗️ Data Architecture

![Data Architecture](docs/data_architecture.png)

### 1. Bronze Layer

Stores raw data as-is from the source systems. Data is ingested from CSV files into the SQL Server database.

### 2. Silver Layer

This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

### 3. Gold Layer

Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 📁 Repository Structure

```text
data-warehouse-project/
│
├── datasets/
│   └──                         # Raw datasets used for the project
│
├── docs/
│   ├── data_architecture.drawio    # Data architecture diagram
│   ├── data_catalog.md             # Data catalog and field descriptions
│   ├── data_flow.drawio            # Data flow diagram
│   ├── data_model.drawio           # Data model / star schema
│   └── naming-conventions.md       # Naming conventions and guidelines
│
├── scripts/
│   ├── bronze/                     # Scripts for extracting and loading raw data
│   ├── silver/                     # Scripts for cleaning and transforming data
│   └── gold/                       # Scripts for creating analytical models
│
├── tests/                           # Data quality and validation tests
│
├── README.md                        # Project overview and instructions
├── LICENSE                          # License information
└── .gitignore                       # Files and directories ignored by Git
```

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share the project with proper attribution.

---

## 🌟 About Me

Hi there! I'm **Poonam Maurya**, a Computer Science student passionate about **Data Analytics, SQL, Data Warehousing, and Business Intelligence**.

I'm continuously learning and building projects to strengthen my practical knowledge in data and analytics.

Let's stay in touch! Feel free to connect with me on the following platforms:

- **GitHub:** [Poonam Maurya](https://github.com/poonammaurya20012-sudo)
- **LinkedIn:** [Poonam Maurya](https://www.linkedin.com/in/poonam-maurya-692122314)
---

🎯 **Career Goal:** To start my career as a **Data Analyst** and continuously grow my skills in data-driven problem solving.
