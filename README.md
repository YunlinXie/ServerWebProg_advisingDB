# ServerWebProg_advisingDB

You need to implement a web application that is split in three parts, namely, Webpage, PHP and Database. Each of them will be used concurrently to solve the problem described below.
Your implementation should be able to resist all the most common security threats.

Webpage
This is the main page of your application. It would contain two sections, ADD and SEARCH:

ADD section contains:
A text box to input an Advisor name
A text box to input a Student name
A text box to input the Student ID code
A text box to input the class code
A button to allow the user to add the above specified data in the Database
 
SEARCH section contains:
A search box (with corresponding button) that allows the user to query the database for Advisors name

PHP
Implement one or more PHP functions that read the inputs from the ADD section of the Webpage and prepare the corresponding query to add the record in the Database
Implement one or more PHP functions that read the input from the SEARCH section and prepare the corresponding query for the Database
Implement a function that, when a search is made in the SEARCH section, it shows on the webpage the result of the query
 
Database
You need to create a database that contains at least a table to store the information in input to the webpage
 
You need to submit your web application in one or more .php files. No other format are allowed.