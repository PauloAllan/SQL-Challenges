# SQL Challenge — City (Revising the Select Query I)

SQL exercise solved on **HackerRank**.

## 🎯 Challenge Description

Query all columns for all American cities in the `CITY` table with populations larger than `100,000`.

The `CountryCode` for America is `USA`.

## 💡 My Solution

```sql
SELECT *
FROM CITY
WHERE POPULATION >= 100000
  AND COUNTRYCODE = 'USA';
```

## 📚 Concepts Practiced

* `SELECT` statement
* `FROM` clause
* `WHERE` clause
* Comparison operator (`>=`)
* Logical operator (`AND`)
* Multi-condition filtering
* Filtering by country and population

## 🛠️ Challenge Information

| Information    | Details        |
| -------------- | -------------- |
| Platform       | HackerRank     |
| Difficulty     | Easy           |
| Technology     | SQL            |
| Topic          | SELECT & WHERE |
| Database Table | `CITY`         |

## 🧠 What I Learned

This challenge reinforces how to filter database records using multiple conditions in the `WHERE` clause.

The query returns only cities that satisfy **both** conditions:

1. Population greater than or equal to `100,000`.
2. Country code equal to `USA`.

This is a fundamental SQL pattern for extracting specific records from a larger dataset.
