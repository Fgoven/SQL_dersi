## SQL DERSİ ÖDEV 8 

### SORU 1
``` SQL
CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```
### SORU 2 
```SQL
insert into employee (name, birthday, email) values ('Lin Ahrens', '1936-02-04', 'lahrens0@amazon.de');
insert into employee (name, birthday, email) values ('Rozalie Herculeson', '1950-03-08', 'rherculeson1@reference.com');
insert into employee (name, birthday, email) values ('Linus Salandino', '1980-04-18', 'lsalandino2@shutterfly.com');
insert into employee (name, birthday, email) values ('Shawn Trimble', '1903-02-11', 'strimble3@linkedin.com');
insert into employee (name, birthday, email) values ('Mahmud Dampney', '1996-01-21', null);
insert into employee (name, birthday, email) values ('Meryl Bolf', '1945-10-28', 'mbolf5@examiner.com');
insert into employee (name, birthday, email) values ('Curr Hucks', '1914-08-29', null);
insert into employee (name, birthday, email) values ('Valencia Fitzroy', null, 'vfitzroy7@ihg.com');
insert into employee (name, birthday, email) values ('Zulema Boig', '1933-09-14', 'zboig8@npr.org');
insert into employee (name, birthday, email) values ('Raphael Kellar', '2000-06-04', 'rkellar9@amazon.co.jp');
insert into employee (name, birthday, email) values ('Pierrette Huston', '1984-06-23', 'phustona@homestead.com');
insert into employee (name, birthday, email) values ('Cecil Marwick', '1917-08-18', 'cmarwickb@i2i.jp');
insert into employee (name, birthday, email) values ('Olenolin Crowden', null, 'ocrowdenc@soundcloud.com');
insert into employee (name, birthday, email) values ('Adelind Chasteau', '1964-09-22', null);
insert into employee (name, birthday, email) values ('Harvey Scully', '1933-03-23', 'hscullye@yandex.ru');
insert into employee (name, birthday, email) values ('Gaspard Citrine', null, 'gcitrinef@canalblog.com');
insert into employee (name, birthday, email) values ('Derry Kilgallon', null, 'dkilgallong@umich.edu');
insert into employee (name, birthday, email) values ('Noach Woolbrook', '1999-03-01', null);
insert into employee (name, birthday, email) values ('Huntington Coolbear', '1954-09-10', 'hcoolbeari@google.com.au');
insert into employee (name, birthday, email) values ('Rasia Dorling', '1901-05-08', null);
insert into employee (name, birthday, email) values ('Charlton MacLaughlin', '1922-10-14', null);
insert into employee (name, birthday, email) values ('Zorana Del Monte', '1981-03-13', 'zdell@ycombinator.com');
insert into employee (name, birthday, email) values ('Reggie Warlaw', '1937-05-13', 'rwarlawm@telegraph.co.uk');
insert into employee (name, birthday, email) values ('Angelo Hawtry', '1956-11-13', null);
insert into employee (name, birthday, email) values ('Ivy Farnon', '1951-06-28', null);
insert into employee (name, birthday, email) values ('Keenan Grummitt', null, 'kgrummittp@xing.com');
insert into employee (name, birthday, email) values ('Mano Blagden', '1962-11-17', 'mblagdenq@nbcnews.com');
insert into employee (name, birthday, email) values ('Patin Broome', '1980-12-14', 'pbroomer@histats.com');
insert into employee (name, birthday, email) values ('Cassandre Blackaby', '1916-04-19', null);
insert into employee (name, birthday, email) values ('Britt Dunseath', '1925-02-20', 'bdunseatht@comcast.net');
insert into employee (name, birthday, email) values ('Katherina Hintze', '1940-10-30', 'khintzeu@go.com');
insert into employee (name, birthday, email) values ('Wenonah Simester', '1965-10-17', 'wsimesterv@webmd.com');
insert into employee (name, birthday, email) values ('Tara McDade', '1970-05-17', 'tmcdadew@bloglovin.com');
insert into employee (name, birthday, email) values ('Guillemette Kowalik', '1955-03-10', 'gkowalikx@newyorker.com');
insert into employee (name, birthday, email) values ('Marcelline Surplice', '1967-11-28', 'msurplicey@tripod.com');
insert into employee (name, birthday, email) values ('Donnamarie Yarrington', '1937-01-21', null);
insert into employee (name, birthday, email) values ('Pinchas Klicher', '1960-03-14', null);
insert into employee (name, birthday, email) values ('Tiphany Tigwell', null, 'ttigwell11@odnoklassniki.ru');
insert into employee (name, birthday, email) values ('Wendeline Ewence', '1977-06-02', 'wewence12@nydailynews.com');
insert into employee (name, birthday, email) values ('Penn Yeabsley', null, 'pyeabsley13@goo.gl');
insert into employee (name, birthday, email) values ('Curtis Wyndham', '1923-07-16', 'cwyndham14@facebook.com');
insert into employee (name, birthday, email) values ('Freida Lowsely', '1983-03-14', 'flowsely15@si.edu');
insert into employee (name, birthday, email) values ('Jonah Davies', null, 'jdavies16@bing.com');
insert into employee (name, birthday, email) values ('Natividad Koubek', '1923-10-30', 'nkoubek17@ca.gov');
insert into employee (name, birthday, email) values ('Cyrillus Gush', '1948-03-21', 'cgush18@de.vu');
insert into employee (name, birthday, email) values ('Wright Brigge', null, 'wbrigge19@tiny.cc');
insert into employee (name, birthday, email) values ('Denys Neeves', '1994-01-02', 'dneeves1a@dyndns.org');
insert into employee (name, birthday, email) values ('Waldon Giotto', null, 'wgiotto1b@cmu.edu');
insert into employee (name, birthday, email) values ('Poppy Ebunoluwa', '1906-04-06', null);
insert into employee (name, birthday, email) values ('Marji Wasbrough', '1934-02-27', 'mwasbrough1d@last.fm');
```
### SORU 3
``` SQL
--UPDATE 1
UPDATE employee
SET name = 'Fatma Goven',
	birthday = '1997-01-01',
	email = 'fgoven@gg.com'
WHERE id = '7';
--UPDATE 2
UPDATE employee
SET name = 'Umit Goven',
	birthday = '1996-05-22',
	email = 'ugoven@gg.com'
WHERE id = '8';
--UPDATE 3
UPDATE employee
	SET name = 'ADD LATER',
	birthday = NULL,
	email = NULL
WHERE name LIKE ('P%');
--UPDATE 4
UPDATE employee
	SET email = 'WRONG EMAIL CORRECTED LATER'
WHERE email LIKE ('%.org');
--UPDATE 5
UPDATE employee
	SET name = 'xxx',
	birthday = NULL,
	email = NULL
WHERE id > 25;
```
## SORU 4
``` SQL
--DELETE 1
DELETE FROM employee
WHERE id = '9';
--DELETE 2
DELETE FROM employee
WHERE name = 'ADD LATER';
--DELETE 3
DELETE FROM employee
WHERE name LIKE ('Z%');
--DELETE 4
DELETE FROM employee
WHERE birthday IN ('1997-01-01');
--DELETE 5
DELETE FROM employee
WHERE email LIKE ('%.org');
```
