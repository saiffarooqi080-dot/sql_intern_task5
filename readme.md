## Objective
[cite_start]The primary goal of this task was to demonstrate mastery of combining data from multiple tables using various SQL Join types: **INNER, LEFT (OUTER), RIGHT (OUTER), and FULL (OUTER)**[cite: 3].

## Database Design: The Library System
To execute the task, a simple relational database consisting of three tables was created:
1.  **Authors**: Stores author information.
2.  **Books**: Stores book details and links to the `Authors` table via `AuthorID`.
3.  **Publishers**: Stores publisher details.

## Deliverables
[cite_start]All SQL queries were developed in a local environment (e.g., DB Browser for SQLite / MySQL Workbench [cite: 5]) to ensure correctness and were categorized by join type.

### Files in this Repository
* `task_5_sql_queries.sql`: Contains all `CREATE TABLE`, `INSERT`, and `SELECT` (join) statements.
* `interview_answers.md`: Detailed answers to the key SQL Join interview questions.
* `task_log.md`: A summary of the steps taken to complete the task.

## Key Concepts Demonstrated
* Fundamental Joins (INNER, LEFT, RIGHT, FULL).
* Handling of non-matching records (NULL values in Outer Joins).
* Advanced Join concepts: CROSS JOIN and joining more than two tables.
* [cite_start]The difference between `INNER` and `LEFT JOIN`.
