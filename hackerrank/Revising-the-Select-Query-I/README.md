# SQL Challenge — City (Revising the Select Query I)

SQL exercise solved on **HackerRank**.

## 🎯 Challenge Description
Query all columns for all American cities in the **CITY** table with populations larger than `100,000`. The **CountryCode** for America is `USA`.

## 💡 My Solution

```sql
SELECT *
FROM CITY
WHERE POPULATION >= 100000
  AND COUNTRYCODE = 'USA';