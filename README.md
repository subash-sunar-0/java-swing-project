# java-swing-project
    This is an individual project for 3 semester to create app using java swing and JDBC CURD.

#Tools and Technologies used
    
    a.JDK 1.8
    b.MySQL Connector Java - 8.0.13
    c.JDBC - 4.2
    d.Eclipse IDE
    
 #What we will  build?
        
    a.User login
    b.User Logout
    c.User Change Password
    
    



#Database Setup

    Make sure that to installed the MySQL server on your machine


    create database swing_project;
    CREATE TABLE student
    ( id int NOT NULL,
     name varchar(250) NOT NULL,
     password varchar(250)
     );

    INSERT INTO student (id, name, password)
    VALUES (1, 'username for your app', 'passwod for your app');

# Connecting With Database
    In order to connect our Java program with the MySQL database, we need to include MySQL JDBC driver which is a JAR file, namely mysql-connector-java-8.0.13-bin.jar.



