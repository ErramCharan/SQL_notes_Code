# SQL_notes
This repository have both notes and code
#Normalization:
Database Normalization is a process and it should be carried out for every database you design. The process of taking a database design, and apply a set of formal criteria and rules, is called Normal Forms.
First Normal Form (1 NF):
1.every column attribute need to have single value 
2.each row should be unique, either thorugh single or multiple columns- not mandate to have a primary key.
Second Normal Form (2 NF):
1. should be 1nf
2. all non key columns should completely depend on counter key or primary key(if partially depend split them into tables)
3. each table should have primary key and relation should be formed using foreign key 
Third Normal Form (3 NF):
Avoid transitive dependencies.
A database is considered third normal form if it meets the requirements of the first 3 normal forms.
