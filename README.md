# SQL 🛢
This repo will store my SQL practices 🛢🔗

## SQL Cheatsheet

- [Manipulation](#manipulation)
- [Queries](#queries)
- [Aggregate Functions](#aggregate-functions)
- [Multiple Tables](#multiple-tables)

### Manipulation

#### Column Constraints
Column constraints are the rules applied to the values of individual columns:

- **PRIMARY KEY** constraint can be used to uniquely identify the row.
- **UNIQUE** columns have a different value for every row.
- **NOT NULL** columns must have a value.
- **DEFAULT** assigns a default value for the column when no value is specified.

There can be only one PRIMARY KEY column per table and multiple UNIQUE columns.

> CREATE TABLE student (
> id INTEGER PRIMARY KEY,
> name TEXT UNIQUE,
> grade INTEGER NOT NULL,
> age INTEGER DEFAULT 10
> );


### Queries

### Aggregate Functions

### Multiple Tables
