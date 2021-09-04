### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  PostgreSQL, also known as Postgres, is a free and open-source relational database management system emphasizing extensibility and SQL compliance.


- What is the difference between SQL and PostgreSQL?
  SQL server is a database management system which is mainly used for e-commerce and providing different data warehousing solutions. PostgreSQL is an advanced version of SQL which provides support to different functions of SQL like foreign keys, subqueries, triggers, and different user-defined types and functions.
  

- In `psql`, how do you connect to a database?
  \c db_name


- What is the difference between `HAVING` and `WHERE`?
  The main difference between them is that the WHERE clause is used to specify a condition for filtering records before any groupings are made, while the HAVING clause is used to specify a condition for filtering values from a group.


- What is the difference between an `INNER` and `OUTER` join?
  The major difference between inner and outer joins is that inner joins result in the intersection of two tables, whereas outer joins result in the union of two tables.
  

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  The main difference between the Left Join and Right Join lies in the inclusion of non-matched rows. Left outer join includes the unmatched rows from the table which is on the left of the join clause whereas a Right outer join includes the unmatched rows from the table which is on the right of the join clause

- What is an ORM? What do they do?
  Object-Relational Mapping (ORM) is a technique that lets you query and manipulate data from a database using an object-oriented paradigm.
  

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  An AJAX request is identical to a "normal" browser request as far as the server is concerned other than potentially slightly different HTTP headers. e.g. chrome sends:



- What is CSRF? What is the purpose of the CSRF token?
  A CSRF token is a secure random token (e.g., synchronizer token or challenge token) that is used to prevent CSRF attacks. The token needs to be unique per user session and should be of large random value to make it difficult to guess. A CSRF secure application assigns a unique CSRF token for every user session.


- What is the purpose of `form.hidden_tag()`?
  The form. hidden_tag() template argument generates a hidden field that includes a token that is used to protect the form against CSRF attacks. All you need to do to have the form protected is include this hidden field and have the SECRET_KEY variable defined in the Flask configuration.
