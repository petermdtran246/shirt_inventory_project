# 👕 SQL Project: Shirt Inventory Management

This is a beginner-level SQL project that simulates managing a basic shirt inventory using a relational database. It demonstrates the full cycle of **CRUD operations** — creating a table, inserting data, updating records, deleting specific entries, and eventually dropping the entire table.

---

## 📦 Project Overview

This project is useful for learning:

- How to design a simple table structure
- How to manage data with real-world logic (e.g., tracking how long since a shirt was last worn)
- How to apply conditional logic in SQL
- How to confidently use `INSERT`, `SELECT`, `UPDATE`, `DELETE`, and `DROP`

---

## 🧱 1. Table Creation

```sql
CREATE TABLE shirts (
  shirt_id INT NOT NULL AUTO_INCREMENT,
  article VARCHAR(100),
  color VARCHAR(100),
  shirt_size VARCHAR(100),
  last_worn INT,
  PRIMARY KEY (shirt_id)
);
