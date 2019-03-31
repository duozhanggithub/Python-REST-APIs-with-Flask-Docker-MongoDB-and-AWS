# Python-REST-APIs-with-Flask-Docker-MongoDB-and-AWS

# Used ubuntu for demo, so summarize some of the common Linux commands here

ls: list files in a directory

cd: change directory

cat: show the content of file, or merge several files

sudo: allows users to run programs with the security privileges of another user, by default the superuser

apt: Advanced Package Tool, handle the installation and removal of software on Debian, Ubuntu, and related Linux distributions

apt install, apt update, apt remove...

mkdir xxx: make a directory called xxx

cp: copy, sudo cp ../app.py . cope app.py into a directory

touch: create or modify a file


# How to dockerizing an application:

Code (refer to Dockerizing application demo https://github.com/duozhanggithub/Python-REST-APIs-with-Flask-Docker-MongoDB-and-AWS/tree/master/Dockerizing%20application%20demo)

Run the docker compose file:

sudo docker-compose build

sudo docker-compoase up


# MongoDB

MongoDB server > Database > Collections > Documents

![alt text](https://github.com/duozhanggithub/Python-REST-APIs-with-Flask-Docker-MongoDB-and-AWS/blob/master/SQL%20and%20NoSQL%20database.png)

Database is a physical container for collections where each database gets its own set of files of the file system.

Collection is a group of Mongo documents and it's equivalent of an RDBMS table. Collections do not enforce schema.

Document is a set of key value pairs and the documents have dynamic schema. Very similar to JSON

![alt text](https://github.com/duozhanggithub/Python-REST-APIs-with-Flask-Docker-MongoDB-and-AWS/blob/master/example%20of%20documents.png)

Relational database has a typical schema design that shows a number of tables and the relationships between these tables while in MongoDB there is no concept of relationship.

Create or switch to the database: use mydb

Write documents into db: db.movie.insert({"name":"xyz"})

Delete database: db.dropDatabase()
