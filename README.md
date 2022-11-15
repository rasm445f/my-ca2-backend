too use the code and its functions you have to do these steps:

1. make sure the JDK is set to version 11.

2. go to edit configurations and add tomcat local server.

3. in the pom.xlm file change the name of the artifactId and the name of the project.

4. in the pom.xml file edit the database name to the name of your database.

6. check that it uses the correct branch main/master.

7. Add a mysql datasource with the database you are going to use.

8. make sure it uses the correct DB and has the right username and password in persistence.xml. 
