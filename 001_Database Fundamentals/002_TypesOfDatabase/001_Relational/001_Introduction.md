# Relational Database

**A relational database (RDB) is a way of structuring information in tables, rows, and columns.**

- An RDB has the ability to establish links—or relationships–between information by joining tables, which makes it easy to understand and gain insights about the relationship between various data points.

They store data in **tables**, where each table represents an **`entity`**, and each **row** in the table represents a **_specific instance of that entity_**.

- The tables are related to each other through key relationships.

# The relational database model

Developed by **`E.F. Codd`** from IBM in the 1970s.

- The relational database model allows any table to be related to another table using a common attribute.

**Think of the relational database as a collection of spreadsheet files that help businesses organize, manage, and relate data.**

- In the relational database model, each `spreadsheet` is a **table** that stores `information`, represented as **columns** (`attributes`) and **rows** (`records or tuples`).

**_Attributes_ (`columns`) specify a data type, and each _record_ (or `row`) contains the value of that specific data type.**

- All tables in a relational database have an attribute known as the `primary key`, which is a unique identifier of a row, and each row can be used to create a relationship between different tables using a foreign key—a reference to a `primary key` of another existing table.

![relationaldb](/003_Database%20Fundamentals/000_images/relationaldb01.jpg)

# Benefits Of Relational Database

## Flexibility

It’s easy to `add`, `update`, or `delete` tables, `relationships`, and make other changes to data whenever you need **_without changing the overall database structure or impacting existing applications_**.

## ACID compliance

Relational databases support ACID (**Atomicity**, **Consistency**, **Isolation**, **Durability**) performance to ensure data validity regardless of `errors`, `failures`, or `other potential mishaps`.

## Ease of use

It’s easy to run complex queries using SQL, which enables even non-technical users to learn how to interact with the database.

## Collaboration

Multiple people can operate and access data simultaneously.

- Built-in locking prevents simultaneous access to data when it’s being updated.

## Built-in security

Role-based security ensures data access is limited to specific users.

## Database normalization

Relational databases employ a design technique known as normalization that reduces data redundancy and improves data integrity.
