# College Analaytics Project
I made that project as a final project of BI Developer Extended Course in Naya College.

This project is a comprehensive BI solution for the college:
  1) I started with exploring the data and mapping all the relevant tables and columns, everything is documented in the 'Source to Target' file.
  2) I created 2 databases in SQL SERVER - one as a stagind DB and the other as the DWH, also created all the relevant tables I needed, the code is in the 'DWH Script' file.
  3) I built an ETL process using SSIS - it is built as many small packages which pull all the raw data from all the many sources into the staging db, 
     and then transform it as needed to the DWH itself, as can be found in the 'ETL - SSIS' folder.
  4) I made a dashboard in PowerBI that reflects all the conclusions I found - as can be found in 'Dashboard.pbx' file.
