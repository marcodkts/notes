1. Acess as super user
1. Login to mysql: $ mysql -u root -p
2. Create a database: $ CREATE DATABASE (database name);
3 USE db_connect;
4. Create a user : $ CREATE USER '(name_user)'@'localhost' IDENTIFIED by '(password)';
5. Grant privileges to the user for that db : GRANT ALL PRIVILEGES ON (database name).* TO '(name_user)'@'localhost';
6 .Connect with MySQL Workbench on that db and create the first table

DON'T FORGET TO CHANGE THE CONTENT BETWEEN ()
EXEMPLE: CHANGE (database name) to db_connect