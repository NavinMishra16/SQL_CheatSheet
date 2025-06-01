## This is the CheatSheet for Java backend interview 

#### Document link & Question: 
```http
 https://drive.google.com/drive/folders/1B63EcuYCRHhcUlnz5mpdvXFmFYkhGHHq
```


#### Basic Way to check table  to use Below Query : 

 `To read the table from MYSQL workbench`
```SQL
  select * from worker table
```


#### There are 3 tables refered by Worker Table, bonus Table, ex Table 


## String Function : 

## Q. Write an SQL query to fetch “FIRST_NAME” from Worker table in upper case.
## Answer : upper() keyword return's change the character of atrribute of column into uppercase

```SQL
select UPPER(first_name) from worker;
```

## Q. Write an SQL query to print the first three characters of  FIRST_NAME from Worker table.
## Answer : substing(columnName, start, length) NOTE : start with 1 based indexing
```SQL
select substring(first_name, 1, 3) from worker;
```


## Q.Write an SQL query to find the position of the alphabet (‘b’) in the first name column ‘Amitabh’ from Worker table.
## Answer : 
```SQL
select locate('b', first_name) from worker where first_name = 'Amitabh';
```
## locate(substring/character, column_Name) -> returns first occurance or index of character or substring 
```This is my edit```











