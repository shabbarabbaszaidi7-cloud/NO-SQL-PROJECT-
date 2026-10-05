Name: SHABBAR ABBAS ZAIDI
Course: BCA (DS & AI)
Section: BCADS-26 
University: Babu Banarasi Das University,Lucknow
Roll No.: 15
UNIVERSITY Roll No:-1250258407

# Student Management System Using MongoDB

## 📌 Project Overview

This project is a **Student Management System** developed using **MongoDB**, a NoSQL database management system.

The project demonstrates how MongoDB can be used to store, retrieve, update, delete, search, filter, sort, and manage student information using different MongoDB queries and operators.

## 🎯 Objectives

- Understand the basic concepts of NoSQL databases.
- Learn the basic features of MongoDB.
- Create a database and collection.
- Insert and manage student records.
- Perform CRUD operations.
- Use comparison operators.
- Perform sorting and filtering.
- Use logical AND and OR operations.

## 🛠️ Technology Used

- **Database:** MongoDB
- **Interface:** MongoDB Compass / MongoDB Shell
- **Database Type:** NoSQL
- **Collection:** `students`

## 📂 Database Structure

The project uses a database named:

`Project`

The collection created inside the database is:

`students`

Each student record contains:

- Roll Number
- Name
- Age
- Marks
- City

The project initially contains **50 student records**.

## 🔧 Operations Performed

The following MongoDB operations are demonstrated in this project:

1. Create Database
2. Create Collection
3. Insert 50 Students
4. Display All Students
5. Greater Than (`$gt`)
6. Less Than (`$lt`)
7. Equal To (`$eq`)
8. Greater Than or Equal To (`$gte`)
9. Less Than or Equal To (`$lte`)
10. Not Equal To (`$ne`)
11. AND Operation (`$and`)
12. OR Operation (`$or`)
13. Update Operation
14. Delete One Operation
15. Delete Many Operation
16. Sort Operation
17. Limit Operation
18. Search by Data
19. Count Documents

## 🔍 MongoDB Operators Used

| Operator | Meaning |
|----------|---------|
| `$eq` | Equal to |
| `$gt` | Greater than |
| `$lt` | Less than |
| `$gte` | Greater than or equal to |
| `$lte` | Less than or equal to |
| `$and` | All conditions must be true |
| `$or` | At least one condition must be true |

## 💻 Example Queries

### Display all students

```javascript
db.students.find()
