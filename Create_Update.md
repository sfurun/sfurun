CREATE table employee 
(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE NOT NULL,
	email VARCHAR(100)
)

2- insert into employee (name, birthday, email) values ('Gail', '03/11/2020', 'gheinl0@netvibes.com');
insert into employee (name, birthday, email) values ('Tobie', '04/08/2020', 'ttombleson1@cbsnews.com');
insert into employee (name, birthday, email) values ('Jacquelyn', '22/02/2021', 'jdignam2@friendfeed.com');
insert into employee (name, birthday, email) values ('Ebony', '22/01/2021', 'egrayne3@toplist.cz');
insert into employee (name, birthday, email) values ('Ryun', '02/04/2021', 'rfridlington4@sphinn.com');
insert into employee (name, birthday, email) values ('Winona', '27/04/2021', 'wgaineofengland5@parallels.com');
insert into employee (name, birthday, email) values ('Jeanna', '04/04/2021', 'jbowlas6@latimes.com');
insert into employee (name, birthday, email) values ('Archy', '24/05/2021', 'asarjeant7@zimbio.com');
insert into employee (name, birthday, email) values ('Noreen', '25/07/2020', 'nrowlands8@craigslist.org');
insert into employee (name, birthday, email) values ('Lyssa', '27/09/2020', 'lgunther9@vinaora.com');
insert into employee (name, birthday, email) values ('Bordy', '10/03/2021', 'borreda@weebly.com');
insert into employee (name, birthday, email) values ('Sherrie', '09/03/2021', 'sjeeksb@devhub.com');
insert into employee (name, birthday, email) values ('Merry', '08/02/2021', 'msheringtonc@theguardian.com');
insert into employee (name, birthday, email) values ('Edeline', '26/11/2020', 'eerskinesandysd@china.com.cn');
insert into employee (name, birthday, email) values ('Tripp', '20/04/2021', 'tgannawaye@techcrunch.com');
insert into employee (name, birthday, email) values ('Aline', '31/08/2020', 'acordesf@people.com.cn');
insert into employee (name, birthday, email) values ('Krishna', '14/03/2021', 'kblunseng@vk.com');
insert into employee (name, birthday, email) values ('Dallas', '23/05/2021', 'dweinh@archive.org');
insert into employee (name, birthday, email) values ('Roscoe', '23/11/2020', 'rlambertii@sfgate.com');
insert into employee (name, birthday, email) values ('Kele', '09/12/2020', 'kdyottj@cpanel.net');
insert into employee (name, birthday, email) values ('Candida', '10/09/2020', 'ccousenk@sakura.ne.jp');
insert into employee (name, birthday, email) values ('Gualterio', '07/01/2021', 'gduminil@hubpages.com');
insert into employee (name, birthday, email) values ('Gloriane', '06/05/2021', 'gtenbym@youku.com');
insert into employee (name, birthday, email) values ('Gonzales', '05/10/2020', 'gyegorkovn@nsw.gov.au');
insert into employee (name, birthday, email) values ('Brendan', '16/04/2021', 'bbroadburyo@toplist.cz');
insert into employee (name, birthday, email) values ('Joella', '11/12/2020', 'jpleasantsp@weather.com');
insert into employee (name, birthday, email) values ('Letti', '08/11/2020', 'lwimbushq@sciencedaily.com');
insert into employee (name, birthday, email) values ('Chase', '18/03/2021', 'cgumaryr@sciencedaily.com');
insert into employee (name, birthday, email) values ('Othilie', '22/11/2020', 'osharnocks@bravesites.com');
insert into employee (name, birthday, email) values ('Melvyn', '29/05/2021', 'mlandmant@google.com');
insert into employee (name, birthday, email) values ('Nola', '30/05/2021', 'ncorraganu@hubpages.com');
insert into employee (name, birthday, email) values ('Rivalee', '03/10/2020', 'rputmanv@si.edu');
insert into employee (name, birthday, email) values ('Lorinda', '15/11/2020', 'lgrittenw@scribd.com');
insert into employee (name, birthday, email) values ('Rosabelle', '13/04/2021', 'rtompkinsonx@artisteer.com');
insert into employee (name, birthday, email) values ('Arnie', '11/10/2020', 'apydcocky@diigo.com');
insert into employee (name, birthday, email) values ('Lianne', '22/12/2020', 'lfarnyz@myspace.com');
insert into employee (name, birthday, email) values ('Suellen', '09/03/2021', 'snoir10@shinystat.com');
insert into employee (name, birthday, email) values ('Margaux', '13/12/2020', 'mhaynesford11@virginia.edu');
insert into employee (name, birthday, email) values ('Chris', '15/12/2020', 'chayland12@yahoo.com');
insert into employee (name, birthday, email) values ('Ermina', '17/03/2021', 'eamphlett13@vk.com');
insert into employee (name, birthday, email) values ('Rafaelita', '14/02/2021', 'rtunnicliffe14@quantcast.com');
insert into employee (name, birthday, email) values ('Nicolais', '20/11/2020', 'ndosdill15@dot.gov');
insert into employee (name, birthday, email) values ('Darelle', '05/01/2021', 'dlarcher16@canalblog.com');
insert into employee (name, birthday, email) values ('Lefty', '18/11/2020', 'lmerry17@vkontakte.ru');
insert into employee (name, birthday, email) values ('Beatrisa', '14/06/2021', 'bkinlock18@columbia.edu');
insert into employee (name, birthday, email) values ('Franklyn', '13/07/2021', 'fpym19@t-online.de');
insert into employee (name, birthday, email) values ('Cleve', '26/04/2021', 'cbromehed1a@princeton.edu');
insert into employee (name, birthday, email) values ('Dione', '27/01/2021', 'dhorsfield1b@unicef.org');
insert into employee (name, birthday, email) values ('Eloise', '17/03/2021', 'edomnin1c@usa.gov');
insert into employee (name, birthday, email) values ('Trueman', '04/10/2020', 'tfinneran1d@theguardian.com');

3- UPDATE employee SET birthday = '2021-01-10' WHERE name LIKE 'L%' RETURNING *

4- DELETE FROM employee WHERE name LIKE 'L%' RETURNING *
