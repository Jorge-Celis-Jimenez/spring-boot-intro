# Spring Boot Intro

This is a repository that will contain all of the code for my Spring Boot Introduction course.


Insights

 # **Core**     

* Should use the setter injection approach in order to ease testing activities.
* Can define properties using 3 approaches.
     1. Properties file
     2. YML properties file (Superset of JSON)
     


# **MVC**

* You can define a index.html in your static resources, by default, it will be displayed for the root route if haven't specified a controller to handle it.

* Should use @RestController if want to return data as a response, if you want to return a view, should use @Controller.
* The **index.html** file, if placed in the folder /src/main/resources/static, will be displayed when you visit the base path http://localhost:8080

### Dependency management:
* If you want to include dependecies like Jquery or Bootstrap, you have 3 options.
    1. Include them manually.
    2. Use the webjar approch to let maven handle this task. (WebJars are client-side libraries packaged into JAR file).
    https://www.webjars.org/
    3. Use bower (package manager).
    
 ### Template Engines
 
 * **JSPs should be avoided if possible**, there are several known limitations when using them with embedded servlet containers.
 
 ### Thymeleaf
 * This dependency can be added using the spring initializer
 * Allow us to use layout, fragments and other nice stuff
 
 ### GSP Template
 * Need to add (manually) 4 dependencies
    




