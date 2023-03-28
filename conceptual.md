### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  - Database management system within WSL
- What is the difference between SQL and PostgreSQL?
  - SQL is a language, PostgreSQL is the actual database
- In `psql`, how do you connect to a database?
  - \c <databasename>
- What is the difference between `HAVING` and `WHERE`?
  - Having filters data based on conditions that certain groups of rows would have.
  - Where is used to filter data based on conditions that individual rows would have.
- What is the difference between an `INNER` and `OUTER` join?
  - Inner is used to return only rows that have matching values in both tables that are joined
  - Outer returns only the non-matching rows
- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  - Left Outer returns all the rows from the left table and matching rows from the Right table
  - Right Outer returns all the rows from the right table and matching rows from the Left table
- What is an ORM? What do they do?
  - Object-Relational Mapping, makes it easier to work with databases.
- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?
  - AJAX requests are done on client side, faster for simple requests but less secure
  - Server side requests are done on a server may be more secure and slower
- What is CSRF? What is the purpose of the CSRF token?
  - CSRF token is a security measure used be web apps to prevent CSRF attacks
    - The CSRF token is unique with each request and is verified by the server.
- What is the purpose of `form.hidden_tag()`?
  - Used to generate a hidden form field that contains the CSRF token