# SQL Data Analytics Project 📊

A practical **SQL data analytics portfolio project** focused on transforming raw data into meaningful business insights.

This project demonstrates how SQL can be used to explore data, identify trends, measure business performance, segment customers and products, and create analytical reports that support data-driven decision-making.

The project is structured in two stages:

* **Part 1 — Exploratory Data Analysis (EDA)**
* **Part 2 — Advanced Analytics**

---

## 🎯 Project Objectives

The main goal of this project is to demonstrate practical SQL skills across the complete analytical process — from understanding the data to producing actionable insights.

Key objectives include:

* Explore and understand the underlying datasets
* Identify patterns, trends, and anomalies
* Calculate meaningful business metrics and KPIs
* Analyze changes in performance over time
* Compare current performance with historical results
* Segment customers and products based on business characteristics
* Understand how individual categories contribute to overall performance
* Build reusable SQL queries for analytical reporting
* Translate technical SQL analysis into business-oriented insights

---

## 🗂️ Project Structure

```text
sql-data-analytics-project/
│
├── datasets/
│   └── Source datasets used throughout the analysis
│
├── docs/
│   └── Project documentation and supporting materials
│
├── scripts/
│   ├── Part 1 - Exploratory Data Analysis
│   └── Part 2 - Advanced Analytics
│
├── LICENSE
└── README.md
```

---

# 🔎 Part 1 — Exploratory Data Analysis

The first stage focuses on understanding the data before performing advanced analysis.

### Areas Covered

* Database exploration
* Table and column inspection
* Data quality checks
* Missing-value investigation
* Duplicate detection
* Dimension exploration
* Date-range analysis
* Basic aggregations
* Customer and product exploration
* Initial business metrics

### Key Questions

Some of the questions addressed during EDA include:

* What data is available?
* What are the key dimensions and measures?
* What period does the data cover?
* Are there missing or inconsistent values?
* How many customers and products are represented?
* Which products and categories generate the most activity?
* What are the main characteristics of the dataset?

The purpose of this stage is to establish a reliable understanding of the data before moving into deeper analytics.

---

# 📈 Part 2 — Advanced Analytics

The second stage focuses on extracting deeper business insights using advanced SQL techniques.

### 1. Changes Over Time

Analyze how key metrics change across different time periods.

**Techniques include:**

* Date functions
* Aggregations
* Year/month analysis
* Trend analysis
* Period-over-period comparisons

**Business Questions:**

* How are sales changing over time?
* Which periods show the strongest performance?
* Are there noticeable growth or decline patterns?

---

### 2. Cumulative Analysis

Calculate running totals and cumulative metrics to understand long-term performance.

**Techniques include:**

* Window functions
* `SUM() OVER()`
* Running totals
* Moving averages

**Business Questions:**

* How does revenue accumulate over time?
* How quickly is the business reaching its annual performance?
* What does the overall growth trajectory look like?

---

### 3. Performance Analysis

Evaluate performance by comparing metrics against previous periods or benchmark values.

**Techniques include:**

* `LAG()`
* Window functions
* Average comparisons
* Conditional logic
* Performance categorisation

**Business Questions:**

* Which products or customers are performing above average?
* Which areas are underperforming?
* How has performance changed compared with previous periods?

---

### 4. Data Segmentation

Group customers, products, or other entities into meaningful business segments.

**Techniques include:**

* `CASE`
* `GROUP BY`
* Aggregations
* Conditional segmentation

**Business Questions:**

* Which customers generate the most value?
* How can customers be grouped based on their behaviour?
* Which products belong to high-, medium-, or low-performing segments?

---

### 5. Part-to-Whole Analysis

Understand how individual categories contribute to overall business performance.

**Techniques include:**

* Aggregations
* Window functions
* Percentage calculations
* `SUM() OVER()`

**Business Questions:**

* What percentage of total revenue comes from each category?
* Which categories contribute the most to overall performance?
* Is the business heavily dependent on a small number of categories?

---

# 🧠 SQL Skills Demonstrated

This project showcases practical SQL skills including:

* `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`
* Aggregate functions
* `CASE` expressions
* `JOIN`s
* Subqueries
* Common Table Expressions (CTEs)
* Window functions
* `LAG()` and `LEAD()`
* `SUM() OVER()`
* `AVG() OVER()`
* Date and time functions
* Conditional calculations
* KPI and metric development
* Analytical reporting

---

# 📊 Analytical Approach

The project follows a structured analytical workflow:

```text
Raw Data
   ↓
Data Exploration
   ↓
Data Quality Checks
   ↓
Metric & KPI Definition
   ↓
Exploratory Analysis
   ↓
Advanced SQL Analytics
   ↓
Customer / Product Segmentation
   ↓
Performance Analysis
   ↓
Business Insights
```

This approach helps ensure that analytical conclusions are based on an understanding of the underlying data rather than simply producing SQL queries.

---

# 💡 Business Value

The analysis is designed to demonstrate how SQL can move beyond simple data retrieval and support real business decisions.

The resulting analysis can help stakeholders:

* Identify important trends
* Monitor business performance
* Understand customer behaviour
* Identify high-performing products
* Detect underperforming areas
* Understand revenue contribution
* Prioritise business opportunities
* Make decisions based on measurable evidence

---

# 🛠️ Tools & Technologies

| Tool                   | Purpose                                   |
| ---------------------- | ----------------------------------------- |
| **SQL**                | Data exploration and analytics            |
| **SQL Server / T-SQL** | Query execution and analytical functions  |
| **GitHub**             | Version control and project documentation |

---

# 🚀 How to Use This Project

### 1. Clone the Repository

```bash
git clone https://github.com/annapauseiro/sql-data-analytics-project.git
```

### 2. Explore the Datasets

Review the files inside the `datasets/` directory to understand the available data and its structure.

### 3. Start with EDA

Run the scripts in the **Part 1 — Exploratory Data Analysis** section first.

This provides the necessary context before moving to advanced analytics.

### 4. Continue with Advanced Analytics

Run the scripts in **Part 2 — Advanced Analytics** to explore trends, performance, segmentation, cumulative metrics, and part-to-whole relationships.

### 5. Review the Documentation

Additional explanations and supporting materials can be found in the `docs/` directory.

---

# 📌 Project Roadmap

* Part 1 — Exploratory Data Analysis
* Part 2 — Advanced Analytics

<img width="1918" height="820" alt="My roadmap" src="https://github.com/user-attachments/assets/a96af71c-fcb4-40aa-a29f-a331566cd4f3" />

---

# 📚 Key Takeaways

This project demonstrates the ability to:

1. Understand and explore a relational dataset
2. Translate business questions into SQL queries
3. Apply intermediate and advanced SQL techniques
4. Analyse trends and performance over time
5. Segment customers and products
6. Build meaningful KPIs and analytical metrics
7. Interpret SQL results from a business perspective
8. Organise analytical work into a reproducible portfolio project

---

## 📄 License

This project is licensed under the [MIT License].(LICENSE). You are free to use, modify, and share this project with proper attribution.

---

## 👩‍💻 About Me

Hey there! I’m Anna Pauseiro, an IT professional passionate about data and the stories we can tell through it.

[![Website](https://img.shields.io/badge/Website-814256)](https://annapauseiro.my.canva.site/)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2)](https://www.linkedin.com/in/anna-paula-pauseiro-467a2a270/)
