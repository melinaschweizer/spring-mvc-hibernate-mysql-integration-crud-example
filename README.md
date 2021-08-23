

Prerequisites: 
Java 8
Tomcat 9

Instructions for setting up local environment using Eclipsem integrated with Tomcat: 
https://quip-amazon.com/bzbzA1jHOKoB/Setup-Local-Environment

If you're not using eclipse: mvn clean install 
And you'll have to copy the generated war file into the tomcat/webapps folder, which will expand it into its own directory.
App should be available under localhost:8080.

Note: This project was based on http://javabycode.com/spring-framework-tutorial/spring-mvc-tutorial/spring-mvc-hibernate-mysql-integration-crud-example-tutorial.html



