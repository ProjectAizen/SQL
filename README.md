create database odev01;


use odev01;


create table student
(
id varchar(4),
name varchar(30),
age int
);

-- VERİ GİRİŞİ

insert into student values('1000', 'Ali Can', 25);
insert into student values('1001', 'Veli Yanan', 25);
insert into student values('1002', 'Ayşe Tan', 25);
insert into student values('1003', 'Derya Canan', 25);

select * from student;
-- student tablosundaki herşeyi getirir

select name from student;
-- student tablosundaki name sütununu getirir

select id from student;
-- student tablosundaki id sütununu getirir

select id, name from student;
-- student tablosundaki id ve name sütununu geirir

drop table student;
