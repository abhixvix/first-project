# first-project
create database badminton_team;
use  badminton_team;
show tables;

-- create new student;
create table student(
first_name varchar(20),
id int,
age int(30),
height int(10)
);

-- check about table
desc student;
select * from student;
