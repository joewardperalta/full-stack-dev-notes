# Introduction to Database


## What is a Database

A **database** is an organized collection of data that can be
stored, managed, and retrieved efficiently. It's like a digital
filing system for information used by websites, apps, and 
systems to handle everything from user data to product listings.


## Core Building Blocks of a Database

### 1. Tables (in relational databases)
- Think of tables like spreadsheets: rows and columns
- Each table stores data about one type of item (users,
products, orders)

### 2. Rows (records)
- Each row represents a single entry or item

### 3. Columns
- Each column defines a type of data stored for all entries
- Example: `name`, `email`, `id` are fields (columns)

### 4. Primary Key
- A unique identifier for each row in a table
- Usually named `id`
- Helps keep data organized and searchable

### 5. Relationships
In **relational databases**, tables can be connected using keys:

- **Foreign Key**: a reference to another table's primary key
- Example: An `Orders` table might include `user_id` that links
to the `Users` table

### 6. Queries
- Special instructions (often in **SQL**) to get, insert, update,
or delete data
- Example: ```sql SELECT name FROM users WHERE id = 1; ```