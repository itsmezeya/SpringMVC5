In this example, we will use a Java-based configuration that is we configure the Spring DispatcherServlet and spring beans configuration using all Java Code (no XML).
---------------------------------------
Reference links:
https://www.youtube.com/watch?v=FJh1s73oaQ8&list=PLGRDMO4rOGcP0B8ZHYbuz8AsvTyvJ-E7_&index=1
https://www.javaguides.net/2018/10/spring-mvc-5-hello-world-example.html
----------------------------------
Development Steps
Create Maven Web Application
Add Dependencies - pom.xml File
Project Structure
Spring Configuration - AppConfig.java
Servlet Container Initialization - MySpringMvcDispatcherServletInitializer.java
Model Class - HelloWorld.java
Controller Class - HelloWorldController.java
View - helloworld.jsp
Build + Deploy + Run an application
------------------------------
How to run application.
1. Maven plugin already added to pom.xml
2. Right click project--> Run as -->Maven Build -->(maven goal) tomcat7:run
3. From browser hit -->  localhost:8080/spring-mvc/helloworld
