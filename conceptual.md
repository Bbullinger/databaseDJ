### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  A more user friendly version of SQL with additional features (i.e, foreign keys )

- What is the difference between SQL and PostgreSQL?
  SQL is the basic functioning language to query/amend/delete info from a database.
  postgreSQL is a language built on top of SQL to add additional functionality and ease of user use.
  Similar to python being used in a code editor

- In `psql`, how do you connect to a database?
  \c database;

- What is the difference between `HAVING` and `WHERE`?
  WHERE is a conditional the works of individual rows, HAVING is a conditional that works
  on a new group of rows created by the line. If count,average, etc is used.

- What is the difference between an `INNER` and `OUTER` join?
  Inner combines the similarities of two tables, outer the differences.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  LEFT OUTER includes the dissimilarities of the first table, RIGHT OUTER the second

- What is an ORM? What do they do?
  ORMs allow you to use a programming language to interact with a database (circumventing coding with postgreSQL etc)
  They have the benefit of allowing you to create database scripts

- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?
  AJAX can retreive/alter the webpage without needing to refresh/change endpoints.
  requests allow you to alter the database that the webpage is requesting info from.

- What is CSRF? What is the purpose of the CSRF token?
  Cross Site Request Forgery. It is meant to prevent malicious actors from sending info to
  under the guise of a form that exists on a webpage. The CSRF is like a passport, when the
  form is sent, the CSRF token verifies to the server that it is in fact who it says it is.

- What is the purpose of `form.hidden_tag()`?
  This method creates a CSRF token for a form, and hides it from the user.
