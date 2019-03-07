FROM mariadb:latest
ADD schema.sql /home/schema.sql
CMD service mysql start -D FOREGROUND && mysql -u root -p bookmedik < /home/schema.sql
