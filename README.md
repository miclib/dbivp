# dbivp
Install Verification Procedures (IVP) for Db2 on z/OS and LUW

List of tests: 

    * Drop all IVP database left from previous runs (DBIVP*)

--- simple table tests 

    * Create database 
    * create tablespace 
    * Create table1 with all types of columns 
    * Create index on table1
    * Test insert/select/update/delete operation on table1 

-- Referential integrity tests 

    * Create table2 with Primary Key 
    * Create table3 with Forign Key 
    * Create RI from table3 to table2 
    * Test insert/select/delete operations on table2 

-- BLOB and CLOB tests 
    * Create table4 with CLOB object 
    * insert CLOB into table4 
    * select CLOB from table4
    * Create table5 with BLOB object 
    * insert BLOB into table4 
    * select BLOB from table4 

--


