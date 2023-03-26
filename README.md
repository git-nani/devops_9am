# devops_9am
Git Repo for Devops Practise

FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD-root
copy ./databse_emplyees.sql /docker-entrypoint-intdb.d/







CREATE DATABASE employee;
use employee
CREATE TABLE employee(
    EmployeeID int not null AUTO_INCREMENT,
    FirstName varchar(100) NOT NULL,
    Surname varchar(100) NOT NULL,
    PRIMARY KEY (EmployeeID)

);

INSERT INTO employee (FirstName,Surname)
VLUES("harinarayan das", "pandith"),("hnd","pandi");
