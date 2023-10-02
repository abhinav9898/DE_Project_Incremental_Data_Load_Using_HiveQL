# DE_Project_Incremental_Data_Load_Using_HiveQL
This repository contains the files, execution logs and procedure to work on the project.
This is basically data of employees working on daily wage basis, with variable eod income. Increment/decrement in salries is being stored as eod batch updates in Hive DB.
Tech stacks used:
dataproc(GCP) -- FOR HADOOP CLUSTER
db- Hive
scripting -- shell, HiveQL, SQL

Day1:
---------- daily refresh table -- contains only current day records. 
> create raw data table in Hive
> load raw day 1 data into table.
> create master table
> create temp table
> copy raw table contents in temp table
> copy master table contents in 
> enter only partioned data based on emp_id, and latest row.

Day2:
-------
repeat the same steps as Day 1

**use shell script to auromate this job.

** Code available in /bin
** Execution available in /Execution Logs
** Final DB result available in /Hive/DB/Results
** Dataset available in /datasets
