 Execution Log
## Step 1: Database Design
* **Concept:** Designed a simple, relatable Library System to demonstrate joins.
* **Tables Created:** `Authors`, `Books`, and `Publishers`.
* **Relationships:** Established a one-to-many relationship between `Authors` and `Books` using the `AuthorID` foreign key.

## Step 2: Data Population
* **Data Strategy:** Inserted sample data to specifically test all join types:
    * An Author with **no books** ('Unpublished Author') to test `LEFT JOIN`.
    * A Book with an **unknown AuthorID** (NULL) to test `RIGHT JOIN`.
    * Standard matching data for the `INNER JOIN` examples.

## Step 3: Core Joins Implementation
* **INNER JOIN:** Created a query to correctly list books with their known authors, confirming only matching rows are returned.
* **LEFT JOIN:** Created a query to list all authors, including the 'Unpublished Author' with a NULL book title.
* **RIGHT JOIN:** Created a query to list all books, including the one with the unknown author (NULL author name).
* **FULL OUTER JOIN:** Combined both LEFT and RIGHT join results, listing all authors and all books, regardless of a match.

## Step 4: Advanced Concepts & Interview Preparation
* **CROSS JOIN:** Executed a query between `Authors` and `Publishers` to demonstrate the Cartesian Product ($N \times M$ rows).
* **Self-Join:** Provided a conceptual example and a test query on the `Authors` table to find authors with the same first name.
* **Non-Key Join:** Provided an example of joining tables based on a logical condition rather than a formal foreign key.

## Step 5: Documentation
* Drafted `README.md` to summarize the task, database design, and key concepts.
* Created `interview_answers.md` with detailed responses for the 10 provided SQL interview questions.
* Compiled this `task_log.md` to document the steps taken.
