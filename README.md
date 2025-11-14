# 📘 SAITM Department Data – MySQL Database Dump

This repository contains a MySQL database dump file (`saitm_dep1.sql`) created for practicing basic SQL operations such as table creation, data insertion, and query execution. It includes a sample dataset representing students with their name, roll number, grade, and marks.

---

## 📂 File Included
- `saitm_dep1.sql` — MySQL dump of the `dep1` table with 10 sample student records.

---

## 🧱 Table Structure (`dep1`)

| Column | Type        | Description       |
|--------|-------------|-------------------|
| name   | VARCHAR(30) | Student Name      |
| rollno | INT         | Roll Number       |
| grade  | VARCHAR(10) | Grade Awarded     |
| mark   | INT         | Marks Obtained    |

---

## 🧪 Sample Data Included

The file contains pre-inserted dummy student records such as:

- `('asd', 1, 'A', 30)`
- `('sam', 2, 'C', 31)`
- `('aws', 3, 'B', 53)`
- ...and others (total 10 rows)

---

## ▶️ How to Import the Database

### **Using MySQL CLI**
```bash
mysql -u your_username -p saitm < saitm_dep1.sql
