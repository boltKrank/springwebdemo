# springwebdemo

Example web application (Tomcat) done with Spring Boot with goal to deploy to Tomcat container

## NOTES

Following this guide initially: [https://spring.io/guides/gs/spring-boot/#scratch]

File definitions are as follows:

SpringwebdemoApplication.java: This file has the @SpringBootApplication annotation (scans the whole com.boltkrank.springwebdemo package for other annotations)
HelloController.java: RESTful GET listener, listens to the "/" path, and returns a String back.
ServletInitializer.java: An arboratory class to trigger a servlet initialisation.

Other files in the /test directory are unit tests.

Now that this is built, do the following to run it:

In the base directory, run `./gradlew bootRun` (this needs CTRL+C to kill though)
