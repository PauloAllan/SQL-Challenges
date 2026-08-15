# SQL Challenge — Japanese Cities' Attributes

SQL exercise solved on **HackerRank**.

## 🎯 Challenge Description

Query **all columns (attributes)** for every Japanese city in the `CITY` table.

The `CountryCode` for Japan is `JPN`.

## 💡 Solution

```sql
SELECT *
FROM CITY
WHERE COUNTRYCODE = 'JPN';
```

## 📚 Concepts Practiced

* `SELECT` statement
* `SELECT *`
* `FROM` clause
* `WHERE` clause
* Filtering records by country
* Equality operator (`=`)
* String comparison

## 🛠️ Challenge Information

| Information    | Details        |
| -------------- | -------------- |
| Platform       | HackerRank     |
| Difficulty     | Easy           |
| Technology     | SQL            |
| Topic          | SELECT & WHERE |
| Database Table | `CITY`         |

## 🧠 What I Learned

This challenge reinforces how to filter records using a **text-based condition**.

The condition:

```sql
WHERE COUNTRYCODE = 'JPN'
```

returns only the cities where the `COUNTRYCODE` column contains the value `JPN`.

Using `SELECT *` ensures that **all columns** of the matching cities are returned.
