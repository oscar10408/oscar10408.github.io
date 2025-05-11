---
title: "Database Management Projects"
layout: single
permalink: /database-management/
author_profile: true
---

## 🗄️ Facebook-Style Relational Database Design  
🔗 [GitHub Repo](https://github.com/oscar10408/FaceBook-Database-Construction)

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">
<a href="https://github.com/oscar10408/FaceBook-Database-Construction" target="_blank">
    <img src="../assets/images/facebook_db_schema.jpg" alt="Facebook Database Schema" style="max-width: 600px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
</a>
</div>

**Description**  
This project involves designing and implementing a relational database schema for a social media platform inspired by Facebook. It encompasses the creation of tables, enforcement of data integrity through constraints, and development of SQL scripts for schema creation and data management.

- Designed an ER diagram to model entities such as users, friendships, messages, photos, and events
- Implemented SQL scripts to create and manage database objects, ensuring referential integrity
- Developed views and queries to facilitate data retrieval and analysis
- Included scripts for loading sample data and dropping database objects for maintenance

---

## 🖧 Facebook-Style JDBC Database Interaction  
🔗 [GitHub Repo](https://github.com/oscar10408/facebook-JDBC)

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">
<a href="https://github.com/oscar10408/facebook-JDBC" target="_blank">
    <img src="../assets/images/facebook_jdbc_schema.jpg" alt="Facebook JDBC Schema" style="max-width: 600px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
</a>
</div>

**Description**  
This project demonstrates how to integrate Java applications with relational databases using **JDBC**. It focuses on executing SQL queries to retrieve and process data related to users, friendships, and events in a social network context.

- Implemented SQL queries to extract meaningful insights from the database
- Utilized **JDBC** for database connectivity and data manipulation
- Ensured proper resource management by closing connections and statements appropriately
- Organized code to separate concerns between data access and business logic

---

## 🗃️ MongoDB User Data Analysis & Query  
🔗 [GitHub Repo](https://github.com/oscar10408/MongoDB-User-Data-Analysis-and-Query)

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">
<a href="https://github.com/oscar10408/MongoDB-User-Data-Analysis-and-Query" target="_blank">
    <img src="../assets/images/mongodb_user_analysis.jpg" alt="MongoDB User Analysis" style="max-width: 600px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
</a>
</div>

**Description**  
This project demonstrates how to migrate relational data to a NoSQL system and perform analytical queries using **MongoDB**.  
It showcases data extraction from Oracle, transformation into JSON, and aggregation queries to reveal user and friendship patterns.

- Extracted user data from Oracle and transformed it into MongoDB-compatible JSON documents  
- Imported data into **MongoDB** and structured collections based on users, friendships, and cities  
- Performed queries to analyze friend counts, restore broken friendships, and extract birth month distributions  
- Applied MongoDB’s **aggregation framework** for efficient data grouping and statistical analysis  
- Demonstrates practical skills in **data migration**, **NoSQL modeling**, and **query design**  

---

## 📀 Grace Hash Join Implementation  
🔗 [GitHub Repo](https://github.com/oscar10408/Grace-Hash-Join-GHJ)

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">
<a href="https://github.com/oscar10408/Grace-Hash-Join-GHJ" target="_blank">
    <img src="../assets/images/GHJ.jpg" alt="Grace Hash Join Diagram" style="max-width: 600px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">  
</a>
</div>

**Description**  
This project implements the **Grace Hash Join** algorithm to perform efficient joins on large datasets under memory constraints.  
It simulates disk I/O behavior, applies multi-pass partitioning, and builds memory-efficient hash tables to probe and merge matching records.

- Designed partition phase using a hash function to divide large relations into disk-based buckets  
- Developed probing phase with in-memory hash tables to join partitioned data efficiently  
- Handled recursive repartitioning when intermediate partitions exceed available buffers  
- Simulated buffer pool management and disk I/O to mimic realistic system limitations  
- Demonstrates practical understanding of **external join algorithms**, **buffer optimization**, and **query execution planning**

---
