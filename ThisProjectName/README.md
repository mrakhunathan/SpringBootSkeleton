## Spring Boot Application Skeleton

1. Clone the Project
2. run "mvn clean install" from console
3. If you are using it with IDE, import it as "Existing Maven Project";
4. Modify project name, package names in pom.xml and in package declarations if necessary
5. Right click on project and Run As -> maven install
6. Once, it succeeds, Right click on project and Run As -> Spring Boot App (If you use it in Spring Tool Suite, you will have this option. Else You will have to define an External Tools Configuration as its a Spring Boot App)
7. If you wish to run the same from console/command prompt, once you run "mvn clean install" a target directory will be created. Navigate into it and use "java -jar project_name_in_pom.war".
8. Tomcat Server is embedded and will automatically start your application in the port 8484. You can change this from "application.properties"
9. Java Version Set as - 8 - Make sure you have the same.
10. Built in compatibility with H2 DB.
