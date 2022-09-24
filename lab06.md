# CS235 LAB06
## Notes:
- Using databases for two weeks (SQLite)
- testing out basics (SQL query, and DB Browser)
- Will be connecting the database with flask using SQLAlchemy
- good for caching data, embedded environments, only suits low traffic, no administration
-

## Reflection: 
This lab was quite fun, using SQLite to create and visualise a database is something quite interesting and i found the lab not too difficult
unlike the other ones, it will be fun to see what next week will bring

## Questions:
 
#### Task 1: Creating conditional select queries
- Your search results also need a pagination. Whatʼs the query for selecting the 2nd page of articles with title contains “US” with each page limits to
10 rows?
  - `SELECT * FROM articles WHERE title LIKE '%US%' ORDER BY date LIMIT 10 OFFSET 10;`
- Does search keyword case sensitive? If it doesnʼt, how can we only select
“US” but not “us”?
  - the search keyword when doing "US" does not search for it in capitals, the way to select it would be changing the collation

#### Task 2: Joining tables
- How can “mjackson” find all articles he has commented? Only returns
article_id and article title. Note that he may comment multiple times on
1 article, but we only want to return the same article in 1 row. 
  - `SELECT DISTINCT article_id, title`
- Give one example for each type of joins: inner, left, right and outer.
  - inner would be user_id
  - left join returns all values from left and matching records from t2, so similar to inner + more
  - right join  returns all records from the right table, and matching records from the left table 
  - full join eturns all records when matched in either left or right table
  
#### Task 3: Creating a table
Just like Netflix, each user can only has one reading list.
- Where fields would you include in the table?
  - fields I would include in the readinglist would be article_id, title, user_id, list
- Whatʼs the schema of the table?
  - the schema of the reading list table would be