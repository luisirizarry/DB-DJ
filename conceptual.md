### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

  PostgreSQL is a database that lets you store and manage data using SQL.

- What is the difference between SQL and PostgreSQL?

  SQL is a language used to interact with the databases, while PostgreSQL is a type of database 
  that uses SQL with added features and other stuff.

- In `psql`, how do you connect to a database?

  \c "name of database";

- What is the difference between `HAVING` and `WHERE`?

  WHERE is used to filter rows before grouping, while HAVING is used to 
  filter groups after you’ve grouped the data with GROUP BY.

- What is the difference between an `INNER` and `OUTER` join?

  Inner join only includes rows where data from two tables are present, so there shouldnt 
  be any rows with empty cells. Whereas an outerjoin will add all data, even if there is no data present. 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

  A Left outer join keeps all rows from the left table, even if there’s no match on the right.
  A RIGHT outer join keeps all rows from the right table, even if there’s no match on the left.

- What is an ORM? What do they do?

  An ORM is an Object Relational Mapper. It lets you work with database data as objects 
  in code, so you don’t have to write the SQL directly. 

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

  AJAX makes requests from the browser, and the page can update without reloading.
  Server-side requests happen on the server and usually return a response back to the browser.

- What is CSRF? What is the purpose of the CSRF token?

  CSRF is an attack that tricks users into doing actions they didn’t mean to.
  The CSRF token is used to check if the request is legit and came from the right user.

- What is the purpose of `form.hidden_tag()`?
  
  form.hidden_tag() adds hidden fields to the form, like the CSRF token, to help protect the form when it’s submitted.
  Pretty sure validate_on_submit() checks for these hidden fields as well. 
