CREATE DATABASE db_tugas2_day3;
USE db_tugas2_day3;
DROP TABLE data_mhs
CREATE TABLE data_mhs(
nim INT(8) PRIMARY KEY,
nama VARCHAR(100),
ipk DEC(3,2),
spp INT,
jurusan VARCHAR(50)
);

INSERT INTO data_mhs VALUES 
(
(RAND()*10000000),"naMa1",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"mesin"),
((RAND()*10000000),"naMa2",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"Elektro"),
((RAND()*10000000),"naMa3",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"BanGunan"),
((RAND()*10000000),"naMa4",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"KompUter"),
((RAND()*10000000),"naMa5",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"mesin"),
((RAND()*10000000),"naMa6",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"KompUter"),
((RAND()*10000000),"naMa7",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"mesin"),
((RAND()*10000000),"naMa8",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"KompUter"),
((RAND()*10000000),"naMa9",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"Elektro"),
((RAND()*10000000),"naMa10",ROUND((2+(RAND()*2)),2),(1000000+(RAND()*10000000)),"Elektro");

SELECT LOWER(nama) AS 'Nama', LOWER(jurusan) AS 'Jurusan' FROM data_mhs;
SELECT UPPER(nama) AS 'Nama', UPPER(jurusan) AS 'Jurusan' FROM data_mhs;

SELECT spp, nama FROM data_mhs WHERE spp = (SELECT MIN(spp)FROM data_mhs);

SELECT SUM(spp) FROM data_mhs;
