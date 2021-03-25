# SQL-for-Data-Analysis

This repository contains the quizzes along with their SQL commands for the concepts taught in the course [SQL for Data Analysis](https://in.udacity.com/course/sql-for-data-analysis--ud198) by [MODE](https://modeanalytics.com) at [Udacity](http://udacity.com/).

You can restore the toy dataset  "parch and posey" to your local machines from the file **parch_and_posey_db** using the following steps:

1.) Download and install PostgreSQL from the official website.

2.) Windows users will need to add path of /bin and /lib; 

3.) This PC -> Properties -> Environmental Variables -> Path -> New 

4.) Add `C:\Program Files\PostgreSQL\13\bin` and `C:\Program Files\PostgreSQL\13\bin` to path;

5.) Go to download location of **parch_and_posey_db** file; 

6.) Open CMD prompt; 

7.) Run `pg_restore --create --db_name=postgres --username=postgres parch_and_posey_db`

8.) Run pgAdmin and look up for Parch and Posey Database; 

Now, SQL commands can be used to explore the dataset and run queries on it.

</br>
Here is the schema of the database used for all the queries. </br>

![](schema.png)

</br>







