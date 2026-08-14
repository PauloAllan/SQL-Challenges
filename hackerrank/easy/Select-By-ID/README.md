# SQL Challenge — Select By ID

SQL exercise solved on **HackerRank**.

## 🎯 Challenge Description

Query **all columns** for the city in the `CITY` table with the `ID` equal to `1661`.

The objective is to use the `WHERE` clause to locate a specific record based on its unique identifier.

## 💡 Solution

```sql
SELECT *
FROM CITY
WHERE ID = 1661;
```

## 📚 Concepts Practiced

* `SELECT` statement
* `SELECT *`
* `FROM` clause
* `WHERE` clause
* Filtering by a specific value
* Equality operator (`=`)
* Searching records by `ID`

## 🛠️ Challenge Information

| Information    | Details        |
| -------------- | -------------- |
| Platform       | HackerRank     |
| Difficulty     | Easy           |
| Technology     | SQL            |
| Topic          | SELECT & WHERE |
| Database Table | `CITY`         |

## 🧠 What I Learned

This challenge demonstrates how to retrieve a **specific record** from a database using the `WHERE` clause.

The condition:

```sql
WHERE ID = 1661
```

filters the `CITY` table and returns only the city whose `ID` matches `1661`.

The `*` after `SELECT` means that **all columns** from the matching record will be returned.
