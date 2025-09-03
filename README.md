SpringBoot Application args :

VM args for running : -Duser.timezone=Asia/Kolkata

Docker setup :

* docker compose up -d (Will create the DB) 
* docker compose ps (Check if DB is created)
* docker exec -it postgres-student-spring-boot bash ( to create conatiner in DB)
* psql -U "username" ( go inside created username - "premram")
* \l (view all DB)
* * create database student (get from datasource url)
* Normal sql queries to insert and select data