## A Journey to Reliable Databases: from SQL Generation to Test-Oracle Construction 

### Abstract 

Database management systems (DBMSs) provide fundamental functionalities, such as storing, manipulating, and querying data, for modern data-driven software. Their reliability critically impacts any downstream applications; bugs in DBMSs can lead to serious consequences such as data loss and leakage. In this talk, I will present our recent work on improving the reliability of DBMSs via automated testing. We have introduced a series of techniques spanning from effective test-case generation (i.e., how to generate complex SQL queries for testing deep DBMS logic) to general test-oracle construction (i.e., how to build referencing results for validating the correctness of general SQL queries). Our work has helped improve the reliability of widely used production DBMSs like MySQL, PostgreSQL, and SQLite by exposing hundreds of bugs in them that cause crashes, incorrect query results, and non-compliant transaction executions. We have open-sourced our tools to facilitate further research and benefit the large DBMS community. 

### Bio 

Zu-Ming Jiang is a PhD student at ETH Zurich advised by Zhendong Su. His research interests include databases, operating systems, and computer security. His work has appeared in top systems and security venues such as OSDI, USENIX Security, and NDSS. His dissertation research focuses on developing novel, practical techniques for improving the reliability of database management systems (DBMSs).
