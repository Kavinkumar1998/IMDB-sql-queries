-- create a table
CREATE TABLE IMDB (
  id INTEGER PRIMARY KEY,
  name text,
  image text,
  video text,
  artist text,
  genre text
);
CREATE TABLE Artist (
 id INTEGER PRIMARY KEY,
name text,
role text,
skills text);

CREATE TABLE Reveiw(
id INTEGER PRIMARY KEY,
reveiw_id integer,
reveiw integer
);
-- insert some values
INSERT INTO IMDB VALUES (1, 'Vikram', 'https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcRcywLT8os8ZXJb7n3hmSzrSzpnLIDNgHeIufdEvCprHyuxThul','https://www.youtube.com/watch?v=NXSigiaZ0W0','Kamal_Hassan','Action');
INSERT INTO IMDB VALUES (2, 'Ironman', 'https://i.ytimg.com/vi/ydEtH-0R7DY/movieposter_en.jpg','https://www.youtube.com/watch?v=8ugaeA-nMTc','Robert_Downey','Adventure');
INSERT INTO Artist VALUES(1,'Kamal_Hassan','Hero','Director,Actor');
INSERT INTO Artist VALUES(2,'Robert_Downey','Hero','Actor');
INSERT INTO Reveiw VALUES(1,1,10);
INSERT INTO Reveiw VALUES(2,2,10);
-- fetch some values
SELECT * from IMDB;
SELECT * from Reveiw;
SELECT * from Artist;

--JOINING
SELECT * from IMDB  JOIN Artist on IMDB.id=Artist.id ;
SELECT * from IMDB  JOIN Reveiw on IMDB.id=Reveiw.id ;
SELECT * FROM IMDB INNER JOIN Artist ON IMDB.id = Artist.id INNER JOIN Reveiw ON IMDB.id = Reveiw.id;