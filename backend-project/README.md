# codefoo
This project is for Code Foo 9 application Back End project.

1. importToMysql.php: I build the service to read csv file, connect to mysql databse, create 7 tables
(content, author, state, tag, thumbnail_1, thumbnail_2, thumbnail_3), and insert csv file data to different tables.
* content table has content info, description, headline and slugs.
* author table has content id and author info.
* state table has content id and duration and series.
* tag table has content id and tag info.
* each thumbnail table has content id and each thumbnail info. 
I use content_id to index data, so that we can get different info from diffent tables for the product we needed. 


2. countTwoAuthors.php is a simple service to utilize data in mysql database. This service count how many products has 
two authors. I connect to mysql database and select needed table and data and count, display count result in the console.


