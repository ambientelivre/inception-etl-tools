# inception-etl-tools
Inception ETL Tools

Travels of a Data Engineer with ETL Tools Migration Issue

Starting with the question of the best way to migrate ETLs from Pentaho Data Integration to Talend using Apache Hop :)


The great difficulty of migrating from one ETL model to another and the way each one determined to solve their data transformation, in one of our basic tests (Pentaho to Talend) it is clear that we will not be able to perform a migration from 1 step to 1 step, but the whole context of the ETL must be understood, in the example documented here, 3 steps in Pentaho became 2 steps in Talend.

## Sample Project
 Here have project with similar write in differet ETL Tools, generete 100 rown with name newColumn, value random and write a log. 

### Pentaho Data Integration - Sample Simple Project in 
Generete 100 rows, create a colunm with name newColumn with Step Random Value, write a log.
![Pentaho Data Integration Project](documentations/images/pentaho-data-integration-demo-sample-project.png)
 
### Talend - Sample Simple Project
Generete 100 rown with name newColumn and exec a function TalendString.getAsciiRandomString(int) from value random and write a log. 

![Talend Project](documentations/images/talend-demo-sample-project.png)

### Apache Hop - Sample Simple Project in 
Generete 100 rows, create a colunm with name newColumn with Step Random Value, write a log.
![Apache Hop Project](documentations/images/apache-hop-demo-sample-project.png)


# License 
Apache 2.0
