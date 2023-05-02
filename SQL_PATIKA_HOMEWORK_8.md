# SQL PATIKA HOMEWORK 8
1. `CREATE TABLE employee (id SERIAL PRIMARY KEY, name VARCHAR(50), birthday DATE, email VARCHAR(100));`
2. `insert into employee (first_name, last_name, email, birthday) values ('Tasia', 'Adanet', 'tadanet0@nifty.com', '2022-05-27');`
3. 	`Update employee
	Set
	name = 'Abidin DARICI',
	birthday  = '2017-02-23',
	email = 'abidindarici@hotmail.com'
	Where id = 12;
	
	Update employee
	Set
	name = 'Ege GUNGOR',
	birthday  = '1998-01-01',
	email = 'egegungor@gmail.com'
	Where id = 33;
	
	Update employee
	Set
	name = 'Ahmet SOLAK',
	birthday  = '2003-11-22',
	email = 'ahmetslk@gmail.com'
	Where id = 32;
	
	Update employee
	Set
	name = 'Aycan GUVEN',
	birthday  = '1999-11-11',
	email = 'aycangvn@gmail.com'
	Where id = 39;
	
	Update employee
	Set
	name = 'Gülizar DURAN',
	birthday  = '2004-10-11',
	email = 'glzrdrn@gmail.com'
	Where id = 50;`
4. 	`DELETE FROM employee
	WHERE name ='Abidin'
	RETURNING*;

	DELETE FROM employee
	WHERE id=33
	RETURNING*;

	DELETE FROM employee
	WHERE email = 'glzrdrn@gmail.com'
	RETURNING*;

	DELETE FROM employee
	WHERE id=50
	RETURNING*;

	DELETE FROM employee
	WHERE birtday ='1999-11-11'
	RETURNING*;
