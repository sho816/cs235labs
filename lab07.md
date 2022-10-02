# CS235 LAB07
## Notes:
- Using databases for two weeks (SQLite), last week for it now
- testing basic CRUD operations (Create, Read, Update, Delete) operations through SQLAlchemy
- Learning SQLAlchemy ORM (Object-Relational Mapping)
- ORM helps map python object to a database without writing an SQL query
- SQLAchemy supports many relational databases that isn't tied to flask

## Reflection: 
This lab was quite fun, using SQLAlchemy to create and visualise a database is something quite interesting while testing the functions of CRUD (Create, Read, Update, Delete).
This will definitely assist me with my assignment that is due soon.

## Questions:
 
#### Steps for implementing SQLite features:
the steps in which i implemented SQLite features were:
1. pulling latest update from the cs235_lab_code repo
2. cloning the covid app, switching to SQLite_database_repo
3. trying out queries in the demo, create table instance and implement crud operations,
4. check output

#### So far we encountered two sessions, one is the SQLAlchemy session, another is the web session. Are they the same? If not, briefly explain what each session does.
they're not the same as SQLAlchemy session, the session can be directly instantiated, establishes all conversations with the database
web bessions take place in a given timeframe

#### SQLite is a built-in package for Python. Why do we need SQLAlchemy ORM? Can you explain the benefits of using SQLAlchemy?
- SQL Alchemy provies the support to many relational databases, helps facilitate communication between programs and databases
- we need ORM to translate the python classes to tables on relational databases and converts function calls to SQL statements
