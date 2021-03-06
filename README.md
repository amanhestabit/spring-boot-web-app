# Spring Boot web-app


## Step: 1 You will build a simple news web application with Spring Boot and contentstack Java SDK.


- A favorite text editor or IDE

- JDK 1.8 or later

- Gradle 4+ or Maven 3.2+


## Step: 2 How to complete this guide

- To start from scratch, move on to Starting with [Spring Initializr](https://start.spring.io/).

- To skip the basics, do the following:

- Download and unzip the source repository for this guide, or clone it using Git: 
     
        git clone https://github.com/ishaileshmishra/spring-boot-web-app.git.git

- cd into contentstack-java-spring-example/initial

- Jump ahead to Create a Simple Web Application.

- When you finish, you can check your results against the code in gs-spring-boot/complete.


## Step: 3 For View Rendering

```
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-thymeleaf</artifactId>
    </dependency>
```

## Step: 4 Run the Application


To run the application, run the following command in a terminal window (in the complete) directory

```
    ./gradlew bootRun
```

If you use Maven, run the following command in a terminal window (in the complete) directory:

```
    ./mvnw spring-boot:run
```


Now run the service with curl (in a separate terminal window), by running the following command (shown with its output):

```
    $ curl localhost:8080
```



