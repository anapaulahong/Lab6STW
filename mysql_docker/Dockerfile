#dockerfile: configuracion de la imagen que quiero levantar
#get the latest mysql image (traer la imagen de sql y usarla para ese docker)
#que tipo de tecnologia quiero usar
FROM mysql:latest

#set environment variables for mysql
ENV MYSQL_DATABASE=blog_db
ENV MYSQL_ROOT_PASSWORD=root_password

#user and password for mysql
ENV MYSQL_USER=blog_user
ENV MYSQL_PASSWORRD=blog_password

#copy the database schema to the image
COPY schema.sql ./docker-entrypoint-initdb.d/