# SQL-Odev-8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

SELECT * FROM employee (
	
  id INTEGER PRIMARY KEY,
	
  name VARCHAR (50) NOT NULL,
	
  birthday DATE NOT NULL,
	
  email VARCHAR (100)

);



2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Tabbie', '2019-03-07', 'traiston0@blogger.com');

insert into employee (id, name, birthday, email) values (2, 'Joelle', '2009-10-17', 'jlehrmann1@homestead.com');

insert into employee (id, name, birthday, email) values (3, 'Caldwell', '1998-05-06', 'cnouch2@merriam-webster.com');

insert into employee (id, name, birthday, email) values (4, 'Arabel', '2009-06-24', 'agidney3@livejournal.com');

insert into employee (id, name, birthday, email) values (5, 'Estele', '2015-02-24', 'eleggon4@pen.io');

insert into employee (id, name, birthday, email) values (6, 'Brenda', '2014-08-26', 'btidbold5@homestead.com');

insert into employee (id, name, birthday, email) values (7, 'Corby', '2013-05-27', 'crighy6@google.com');

insert into employee (id, name, birthday, email) values (8, 'Lea', '2005-01-16', 'lgerren7@amazonaws.com');

insert into employee (id, name, birthday, email) values (9, 'Dell', '2019-08-03', 'dghidini8@sakura.ne.jp');

insert into employee (id, name, birthday, email) values (10, 'Laura', '2006-09-14', 'lfusco9@alibaba.com');

insert into employee (id, name, birthday, email) values (11, 'Packston', '2019-12-29', 'pmccroriea@constantcontact.com');

insert into employee (id, name, birthday, email) values (12, 'Emelda', '2016-02-21', 'eforrestillb@nature.com');

insert into employee (id, name, birthday, email) values (13, 'Bran', '1995-08-28', 'bshaylorc@cafepress.com');

insert into employee (id, name, birthday, email) values (14, 'Stesha', '1996-08-17', 'skalinovichd@wikispaces.com');

insert into employee (id, name, birthday, email) values (15, 'Andrej', '2005-10-19', 'agarratte@ucoz.com');

insert into employee (id, name, birthday, email) values (16, 'Harris', '1998-05-11', 'hkeaysellf@fotki.com');

insert into employee (id, name, birthday, email) values (17, 'Verna', '2004-05-22', 'vduvalg@umn.edu');

insert into employee (id, name, birthday, email) values (18, 'Kata', '2007-04-14', 'kdingwallh@yahoo.com');

insert into employee (id, name, birthday, email) values (19, 'Ki', '2005-07-25', 'krutherfordi@vimeo.com');

insert into employee (id, name, birthday, email) values (20, 'Marilin', '2000-11-08', 'mowainj@gov.uk');

insert into employee (id, name, birthday, email) values (21, 'Caralie', '2017-07-22', 'cizkovitchk@redcross.org');

insert into employee (id, name, birthday, email) values (22, 'Nanette', '2006-07-02', 'narnaudonl@51.la');

insert into employee (id, name, birthday, email) values (23, 'Romola', '2006-09-05', 'rgallantm@forbes.com');

insert into employee (id, name, birthday, email) values (24, 'Zola', '2020-09-03', 'zwinchcumn@amazon.de');

insert into employee (id, name, birthday, email) values (25, 'Dannye', '2009-11-13', 'dmorenao@baidu.com');

insert into employee (id, name, birthday, email) values (26, 'Annamaria', '2022-07-16', 'amunciep@time.com');

insert into employee (id, name, birthday, email) values (27, 'Maurine', '2015-05-22', 'mblackstoneq@wufoo.com');

insert into employee (id, name, birthday, email) values (28, 'Gwenni', '2015-06-23', 'gdjekovicr@hp.com');

insert into employee (id, name, birthday, email) values (29, 'Esther', '2016-03-07', 'emarwoods@fc2.com');

insert into employee (id, name, birthday, email) values (30, 'Elvis', '2007-10-14', 'emadgint@cisco.com');

insert into employee (id, name, birthday, email) values (31, 'Lizzy', '1998-03-30', 'lstacyu@craigslist.org');

insert into employee (id, name, birthday, email) values (32, 'Charla', '2005-10-04', 'cgarretv@vk.com');

insert into employee (id, name, birthday, email) values (33, 'Welby', '2009-02-26', 'wkinavanw@blogger.com');

insert into employee (id, name, birthday, email) values (34, 'Darline', '2008-03-05', 'dvakhoninx@harvard.edu');

insert into employee (id, name, birthday, email) values (35, 'Mair', '1996-01-13', 'mfloodgatey@cnn.com');

insert into employee (id, name, birthday, email) values (36, 'Katrinka', '2021-01-19', 'kisworthz@soundcloud.com');

insert into employee (id, name, birthday, email) values (37, 'Chevalier', '1994-01-11', 'cjorioz10@google.ca');

insert into employee (id, name, birthday, email) values (38, 'Kally', '2001-04-04', 'kgladstone11@technorati.com');

insert into employee (id, name, birthday, email) values (39, 'Mort', '2022-01-19', 'mwaith12@cnet.com');

insert into employee (id, name, birthday, email) values (40, 'Eduino', '2004-12-02', 'epetett13@reuters.com');

insert into employee (id, name, birthday, email) values (41, 'Licha', '2006-11-02', 'ljeyes14@printfriendly.com');

insert into employee (id, name, birthday, email) values (42, 'Guglielmo', '2006-07-22', 'gleyson15@sfgate.com');

insert into employee (id, name, birthday, email) values (43, 'Salvidor', '2022-07-16', 'sjefferys16@usatoday.com');

insert into employee (id, name, birthday, email) values (44, 'Malvin', '2002-06-29', 'mbaldcock17@wired.com');

insert into employee (id, name, birthday, email) values (45, 'Max', '2012-04-27', 'mguiraud18@google.com');

insert into employee (id, name, birthday, email) values (46, 'Zabrina', '2016-10-25', 'zkiddie19@uiuc.edu');

insert into employee (id, name, birthday, email) values (47, 'Northrup', '1993-02-23', 'nslateford1a@merriam-webster.com');

insert into employee (id, name, birthday, email) values (48, 'Adore', '2006-07-30', 'amccuthais1b@noaa.gov');

insert into employee (id, name, birthday, email) values (49, 'Caddric', '1998-08-20', 'cmackellar1c@goodreads.com');

insert into employee (id, name, birthday, email) values (50, 'Monroe', '1998-01-28', 'mcord1d@sohu.com');


3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee

SET name = 'Joellie'

WHERE name LIKE 'Joell%';


UPDATE employee

SET birthday = '1993-08-01'

WHERE name = 'Arabel';


UPDATE employee

SET birthday = 'www.oguzhancakmak.com.tr'

WHERE name LIKE 'Zo%';




Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee

WHERE id = 50;


DELETE FROM employee

WHERE name LIKE 'A%';


DELETE FROM employee

WHERE email LIKE 'lgerren%';


