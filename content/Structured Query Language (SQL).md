---
title: "Structured Query Language (SQL)"
alias: SQL
---
> [!SUMMARY]+
> SQL is a language used to store, manipulate, and retrieve [[data]] in a [[Database]]

```sql
SELECT
	field1
FROM
	table.value
WHERE
	field1 = 'condition';
```


## WHERE
The `WHERE` clause narrows down the query to match the conditions set. 

## SELECT
The `SELECT` clause chooses which columns in the table will be queried. `SELECT *` chooses *all* columns and should be sued sparingly.

## Comments
There are 2 syntaxes for comments:
```sql
SELECT
	field1 /* comment (less conventional) */
FROM 
	table.value -- also a comment
```

---
- Index:: [[_Computer Science]] 
- Related:: [[Data analysis]]
---