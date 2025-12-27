# 📘 PySpark SQL — Querying Big Data Using SQL

This folder contains the notebook for **Blog PySpark SQL** of my PySpark Beginner → Expert series.  
The focus of this notebook is to explain **Spark SQL from the ground up**, with clear explanations of every method, parameter, and SQL clause used.

https://medium.com/@Bhuvaneshwaran_16/pyspark-sql-explained-clearly-writing-sql-on-distributed-data-without-confusion-d34668c7dc6b

---

## 📚 What This Notebook Covers

### 🔹 Introduction to Spark SQL
- What Spark SQL is
- Why Spark SQL exists
- Spark SQL vs DataFrame API
- When to use SQL vs PySpark code

---

### 🔹 Temporary Views
- `createOrReplaceTempView()`
- Why views are required for SQL
- Scope and lifetime of temp views
- Difference between `createTempView` and `createOrReplaceTempView`

---

### 🔹 Writing SQL Queries in PySpark
- Using `spark.sql()`
- SELECT, WHERE, GROUP BY, ORDER BY, LIMIT
- Aliases and column naming
- Filtering and sorting data

---

### 🔹 Aggregations and Business Logic
- COUNT, SUM, AVG
- GROUP BY usage
- CASE WHEN expressions
- Writing readable business rules in SQL

---

### 🔹 Joins in Spark SQL
- INNER, LEFT, RIGHT, FULL joins
- Join conditions
- Table aliases
- SQL joins vs DataFrame joins

---

### 🔹 Query Execution & Optimization
- Using `.explain()` to understand execution plans
- How Spark optimizes SQL internally
- Why understanding execution plans matters

---

## 📁 Notebook Included

- **PySpark_SQL_Basics.ipynb**  
  A step-by-step notebook with:
  - Code examples
  - Detailed explanations
  - Beginner-friendly notes
  - Real-world SQL patterns in Spark

---

## 🎯 Who Is This For?
- Beginners learning PySpark
- SQL users moving into big data
- Data engineers & analysts
- Anyone who wants to understand Spark SQL clearly

---

## 🔗 Related Blogs
- Part - 1: [SparkSession + RDDs  ](https://medium.com/@Bhuvaneshwaran_16/title-starting-with-pyspark-understanding-sparksession-rdds-a-beginners-deep-dive-a4a80fc4f4b6)
- Part - 2:  [PySpark DataFrames  ](https://medium.com/@Bhuvaneshwaran_16/pyspark-dataframes-explained-simply-your-complete-beginners-guide-93a007d9b98a)
- Part - 3: [Advanced DataFrame Operations ](https://medium.com/@Bhuvaneshwaran_16/advanced-dataframe-operations-in-pyspark-from-intermediate-to-expert-part-3-70950d75ad90) 


