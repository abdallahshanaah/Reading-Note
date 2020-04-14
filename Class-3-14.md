# Database Normalization 
**Database normalization** is a process used to organize a database into tables and columns.  The main idea with this is that a table should be about a specific topic and only supporting topics included. 

## There are three main reasons to normalize a database. 
 1. The first is to minimize duplicate data, 
 2. the second is to minimize or avoid data modification issues
 3.  the third is to simplify queries. 

 ## Data Duplication and Modification Anomalies
 Duplicated information presents two problems:

1. It increases storage and decrease performance.
2. It becomes more difficult to maintain data changes.

## Insert Anomaly
There are facts we cannot record until we know information for the entire row.

## Update Anomaly 
In this case we have the same information in several rows. For instance if the office number changes, then there are multiple updates that need to be made.  If we don’t update all rows, then inconsistencies appear.

## Definition of Database Normalization
There are three common forms of database normalization: 1st, 2nd, and 3rd normal form. They are also abbreviated as 1NF, 2NF, and 3NF respectively. 
1. **First Normal Form** : The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
2. **Second Normal Form** : The table is in first normal form and all the columns depend on the table’s primary key.
3. **Third Normal Form** : the table is in second normal form and all of its columns are not transitively dependent on the primary key