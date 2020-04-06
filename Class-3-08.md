# SQl
**What is SQL?**
SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.
and that databases including SQLite, MySQL, Postgres, Oracle and Microsoft SQL Server.
and there is some cammand in sql like :
- Database Manipulation
1. CREATE DATABASE database_name	   
2. DROP DATABASE database_name
-  Table Manipulation
1. CREATE TABLE "table_name"("column_1" "data_type_for_column_1","column_2" "data_type_for_column_2",... )
-  Index Manipulation 
1. CREATE INDEX index_name ON table_name (column_name_1, column_name_2, ...)
- Data Manipulation 
1. INSERT INTO table_name VALUES (value_1, value_2,....)
2. INSERT INTO table_name (column1, column2,...) VALUES (value_1, value_2,....)
3. UPDATE table_name SET column_name_1 = new_value_1, column_name_2 = new_value_2 WHERE column_name = some_value
-  Select
1. SELECT column_name(s) FROM table_name
2. SELECT * FROM table_name
3. SELECT DISTINCT column_name(s) FROM table_name
-  Alias
1. SELECT column_name AS column_alias FROM table_name
2. SELECT table_alias.column_name FROM table_name AS table_alias
-  Join
1. SELECT column_1_name, column_2_name, ... FROM first_table_name INNER JOIN second_table_name ON first_table_name.keyfield = second_table_name.foreign_keyfield
-  UNION
1. SQL_Statement_1 UNION SQL_Statement_2
2. SQL_Statement_1 UNION ALL SQL_Statement_2
-  SELECT INTO/IN
1. SELECT column_name(s) INTO new_table_name FROM source_table_name WHERE query
2. SELECT column_name(s) IN external_database_name FROM source_table_name WHERE query
- CREATE VIEW
1. CREATE VIEW view_name AS SELECT column_name(s) FROM table_name WHERE condition
and more 