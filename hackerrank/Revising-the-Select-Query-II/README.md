# SQL Challenge — City (Revising the Select Query II)

SQL exercise solved on **HackerRank**.

## 🎯 Challenge Description

Query the `NAME` field for all American cities in the `CITY` table with populations larger than `120,000`.

The `CountryCode` for America is `USA`.

## 💡 Solution

```sql
SELECT NAME
FROM CITY
WHERE POPULATION >= 120000
  AND COUNTRYCODE = 'USA';
```

## 📚 Concepts Practiced

* `SELECT` statement
* Selecting specific columns
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

This challenge reinforces the use of `SELECT` to retrieve **only the required column** instead of returning all columns with `SELECT *`.

The query returns the `NAME` of cities that satisfy **both** conditions:

1. Population greater than or equal to `120,000`.
2. Country code equal to `USA`.

This is an important SQL pattern for filtering and returning only the data needed from a table.
