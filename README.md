### Simple Add, Edit, Delete and View (CRUD) using Node.js, MySQL & Express

Install all pre-requisites with `npm install`

Access MySQL to create database and table of the project

```
mysql -u root

CREATE DATABASE test;

USE test;

CREATE TABLE users (
  id int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
  name varchar(100) NOT NULL,
  age int(3) NOT NULL,
  email varchar(100) NOT NULL
);
```
Run application with `node app.js`

*Reference: http://blog.chapagain.com.np/node-js-express-mysql-simple-add-edit-delete-view-crud*
