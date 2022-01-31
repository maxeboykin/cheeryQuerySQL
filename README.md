![customer](https://user-images.githubusercontent.com/89083313/151842585-362c561e-b97b-437e-a308-a716fa171d93.png)

## Select
SELECT first_name FROM customer;

SELECT first_name, last_name, email FROM customer; 

SELECT * FROM customer

SELECT FIRST_name || ' ' || last_name FROM customer; //this is concatenating into one column


## Column Aliases

SELECT column_name AS alias_name FROM table_name;

same thing above as below...

SELECT column_name alias_name FROM table_name; 

## Order By Clause

SELECT select_list FROM table_name ORDER BY sort_expression (ASC | DESC)

SELECT first_name, last_name FROM customer ORDER BY first_name ASC 

SELECT first_name, last_name FROM customer ORDER BY first_name ASC, last_name DESC --> sorts first name first hen it sorts last name if any of the first names are the **same** 

You can also use length() function in SQL. 

SELECT first_name, LENGTH(first_name)len FROM customer ORDER BY len DESC
![PostgreSQL-ORDER-BY-expressions](https://user-images.githubusercontent.com/89083313/151853467-eabb81c9-22c6-4deb-ae54-24e72ea4cfce.png)

