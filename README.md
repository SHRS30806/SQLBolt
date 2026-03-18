# 🗄️ SQL Exercises — SQLBolt Solutions

A structured collection of SQL exercise solutions based on the interactive lessons from [SQLBolt](https://sqlbolt.com/). Each lesson covers a core SQL concept, with the original question, reference table, queries, and expected output all documented in one place.

---

## 📚 Table of Contents

| # | Lesson | Topic |
|---|--------|-------|
| 01 | [SELECT queries 101](lessons/lesson-01-select-queries.md) | Selecting columns from a table |
| 02 | *(coming soon)* | Queries with constraints (Pt. 1) |
| 03 | *(coming soon)* | Queries with constraints (Pt. 2) |
| 04 | *(coming soon)* | Filtering and Sorting Query Results |
| 05 | *(coming soon)* | Simple SELECT Queries |
| 06 | *(coming soon)* | Multi-table queries with JOINs |
| 07 | *(coming soon)* | OUTER JOINs |
| 08 | *(coming soon)* | A short note on NULLs |
| 09 | *(coming soon)* | Queries with Expressions |
| 10 | *(coming soon)* | Queries with Aggregates (Pt. 1) |
| 11 | *(coming soon)* | Queries with Aggregates (Pt. 2) |
| 12 | *(coming soon)* | Order of execution of a Query |
| 13 | *(coming soon)* | Inserting rows |
| 14 | *(coming soon)* | Updating rows |
| 15 | *(coming soon)* | Deleting rows |
| 16 | *(coming soon)* | Creating tables |
| 17 | *(coming soon)* | Altering tables |
| 18 | *(coming soon)* | Dropping tables |

---

## 📁 Repository Structure

```
sql-exercises/
├── README.md
└── lessons/
    ├── lesson-01-select-queries.md
    ├── lesson-02-constraints-pt1.md
    └── ...
```

---

## 🧠 How Each Lesson File Is Organized

Every lesson markdown file follows the same consistent format:

1. **Concept overview** — a brief explanation of the SQL topic covered
2. **Reference table** — the dataset used in the exercise
3. **Tasks & Solutions** — each task listed with its query and output

---

## 🛠️ Database Used

Most exercises use a **Pixar movies** database. The main tables include:

- `movies` — title, director, year, length_minutes
- `boxoffice` — movie_id, rating, domestic_sales, international_sales

Some later lessons introduce additional tables for JOIN exercises.

---

## 📖 Source

All exercises are sourced from [SQLBolt](https://sqlbolt.com/) — a free, interactive SQL learning site. This repository exists purely for learning and reference purposes.
