# postgresql

### create database
- CREATE DATABASE test;
### create table
- CREATE TABLE movies(
  id: BIGSERIAL PRIMARYKEY,
  name: VARCHAR(50) NOT NULL,
  yearofrelease: DATE NOT NULL
);
### insert data
- INSERT INTO movies (name,yearofrelease) VALUES('kai po che',2000);
- INSERT INTO movies (name,yearofrelease) VALUES('dil bechara',2000);
- INSERT INTO movies (name,yearofrelease) VALUES('ms dhoni',2000);
### get data
- SELECT * FROM movies;
### get data by id
- SELECT * FROM movies WHERE id = 1;
### update 
- UPDATE movies SET name = 'chichhore' WHERE id = 1;
### delete
- DELETE FROM movies WHERE id = 3;


### drop table
DROP TABLE movies;
### drop database
DROP DATABASE test;
