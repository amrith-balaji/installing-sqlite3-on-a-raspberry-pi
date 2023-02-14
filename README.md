# installing-sqlite3-on-a-raspberry-pi

![image](https://user-images.githubusercontent.com/124582454/218455671-22909187-b74e-4eaf-8aad-2b4dc4efcf82.png)
 
 to enter sqlite, we use the command in the prompt :
 ```
 sqlite3
 ```
and to create a database , we use the command [name].db

to view tables : 

![image](https://user-images.githubusercontent.com/124582454/218761072-304290de-8666-42d4-9f95-5da421cd481b.png)

to create a table we use the following code :
```
CREATE TABLE database_name.table_name(
   column1 datatype PRIMARY KEY(one or more columns),
   column2 datatype,
   column3 datatype,
   .....
   columnN datatype
);
```
to insert some data into the table , we use the command :
```
INSERT INTO TABLE_NAME [(column1, column2, column3,...columnN)]  
VALUES (value1, value2, value3,...valueN);
```

