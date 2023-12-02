# InterviewQuestionFullStackRealTime

Java Concepts:
What is the parent class of the main class in Java?

Answer: java.lang.Object
Explain the differences between an Abstract Class and an Interface in Java.

Answer: Abstract classes can have both abstract and non-abstract methods, while interfaces can only have abstract methods. Interfaces support multiple inheritances, and all interface methods are public abstract by default.
What is the purpose of the @SpringBootApplication annotation in Spring Boot?

Answer: It combines @EnableAutoConfiguration, @ComponentScan, and @Configuration. It auto-configures the application context, scans for components, and indicates the class has @Bean definitions.
Describe the features enabled by the @SpringBootApplication annotation in Spring Boot.

Answer: Features include auto-configuration, component scanning, and configuration of the Spring Boot application.
Explain the role of Spring Cloud in distributed systems.

Answer: Spring Cloud provides tools for common patterns in distributed systems, such as configuration management, service discovery, and circuit breakers.
How does Spring Boot Actuator help in monitoring and managing applications?

Answer: Spring Boot Actuator provides endpoints for monitoring and managing applications, offering insights into application health, metrics, and more.
Write an SQL query to find the third-largest salary from an employee table.

Answer:
sql
Copy code
SELECT MIN(salary) FROM
(SELECT DISTINCT salary FROM emp ORDER BY salary DESC)
WHERE ROWNUM < 3;
Explain the SOLID principles in Java with examples.

Answer: SOLID principles include SRP (Single Responsibility), OCP (Open-Closed), LSP (Liskov Substitution), ISP (Interface Segregation), and DIP (Dependency Inversion). Examples include designing classes with a single responsibility and extending classes without modifying existing code.
Spring Boot Annotations:
Distinguish between @PathVariable and @RequestParam annotations in Spring Boot.

Answer: @PathVariable extracts values from the URI path, while @RequestParam extracts values from the query string.
Explain the purpose of the @Controller and @RestController annotations.

Answer: @Controller is used to define Spring MVC controllers, while @RestController is a specialized version for RESTful services, combining @Controller and @ResponseBody.
Java Programming:
What is a Class Loader in Java, and what is its role during runtime?

Answer: A Class Loader dynamically loads Java classes into the JVM during runtime, allowing classes to be added or replaced without restarting the JVM.
Discuss the design pattern used in your Java project.

Answer: The answer would depend on the specific design pattern used in your project.
Explain the differences between Comparable and Comparator interfaces in Java.

Answer: Comparable is used to define natural ordering of objects, while Comparator allows custom ordering.
Can we override immutable functions in Java?

Answer: No, immutable functions or methods cannot be overridden, as they are declared as final.
Provide a step-by-step procedure for creating a complete REST application in Java.

Answer: The answer would involve creating controllers, services, and defining endpoints using annotations like @RestController.
Discuss the differences between LinkedList and ArrayList in Java.

Answer: LinkedList uses a doubly-linked list, while ArrayList is backed by an array. ArrayList provides fast random access, while LinkedList is more efficient for insertions and deletions.
If Java is an Object-Oriented Programming language, why do we still use primitive data types?

Answer: Primitive data types in Java are used for efficiency and memory conservation, as they directly represent simple values without the overhead of objects.
How does the Stream API work in Java, and what is its purpose?

Answer: The Stream API provides a functional approach for processing collections in Java, allowing operations like filtering, mapping, and reducing to be performed on data streams.
Explain the concept of Serialization in Java.

Answer: Serialization in Java is the process of converting an object into a byte stream, which can be saved to a file, sent over a network, or stored in a database. Deserialization is the reverse process of reconstructing the object from the byte stream.

General Java Concepts:
What is the parent class of the main class in Java?
How do you access data without a native query?
Explain overloading and overriding.
Object-Oriented Programming (OOP):
Discuss all scenarios of OOP and how you apply them in current projects.
Why is Java not completely object-oriented?
Spring Boot and Spring Annotations:
Differences between JPA and Hibernate.
What is @Transactional used for in Spring?
How does security work in microservices? What do you use for microservice security?
Explain the purpose of @Controller and @RestController annotations.
Scope in Spring Boot.
Types of autowiring in Spring.
What is the @Component and @Autowired annotations?
How does @SpringBootApplication work? Explain the annotations it includes (@EnableAutoConfiguration, @ComponentScan, @Configuration).
Java Programming:
LinkedList vs ArrayList.
Find duplicates in ArrayList using Java 8.
Find the second-highest employee salary in an array using streams.
Difference between put and fetch.
How to handle exceptions in the final block?
What is a Class Loader in Java, and what is its role during runtime?
Explain the differences between Comparable and Comparator interfaces.
Can we override immutable functions in Java?
Provide a step-by-step procedure for creating a complete REST application in Java.
Discuss the differences between LinkedList and ArrayList in Java.
Java 8 and Stream API:
Functional programming and lambda functions.
Features of Java 8.
Stream API in Java.
Serialization in Java.
How to find the occurrence of the first character in a string using Java 8?
All the OOP concepts and how they have been implemented.
Spring Boot Advanced Concepts:
How to configure multiple databases at once in Spring Boot, and how does the controller know which database is currently active?
How to handle exceptions in the final block?
What is @Qualifier and @Primary?
Explain the concept of thread pools.
What is an executor service?
Angular and JavaScript:
var vs let.
Routing in Angular.
Differences between var and let in JavaScript.
Find duplicates using streams.
Solid design principles.
Miscellaneous:
Rest API and how to communicate with a REST server.
API Gateway.
How security works in your projects?
HTTP response codes in REST services.
Custom exception handling in Java.
How to break the Singleton design pattern?
Find the first repeating character in a string using Java 7/8.
Serial version ID and its use.
How to create cookies in Java?
Capgemini Client Interview (18th July):
Abstract class or interface, which one is more convenient to use?
Why use microservices instead of connecting projects through remote procedures?
Multithreading framework.
How do annotations work in Spring Boot?
What is Actuator in Spring Boot?
Java's pass-by-reference or pass-by-value?
SQL query optimization.
Lazy loading in Hibernate.
Java Profiling.
Fault tolerance in microservices.
Capgemini Client Interview (4th July):
Design patterns in Spring Boot.
Immutable classes and their use.
How to communicate between different applications?
How many threads are created in parallel streams?
How to secure REST APIs?
What is the difference between parallel stream and thread pool?
Thread pool and multi-threading.
API Gateway.
How design patterns work.
How to consume REST APIs.
Capgemini Client Interview (2nd July):
What is SOA?
Get and load in Hibernate.
States of objects in Hibernate.
CRUD in Spring Boot using JPA.
Scope of microservices.
How equals works if we compare objects instead of strings?
Two ways to iterate elements of a collection.
Differences between ArrayList and LinkedList.
Differences between HashMap and ConcurrentHashMap.
Differences between HashMap and Hashtable.
Capgemini Client Interview (24th June):
Hierarchy for exceptions.
Session and sessionFactory in Hibernate.
HashMap vs Hashtable.
Abstract vs Interface.
Handling multiple exceptions.
Collections vs Collection.
MetaSpace in Java.
Design patterns in microservices.
Default in an interface.
Capgemini Client Interview (18th June):
Class loader.
Design pattern used.
Microservice scalability.
Spring Boot annotations.
Spring MVC vs Spring Boot.
Fault tolerance.
How do you implement encapsulation?
Creating a thread pool.
Serialization in Java.
SpringApplication.run(CitizenServiceApplication.class, args) return value.
Capgemini Client Interview (8th June):
Class loader.
Design pattern used.
Microservice scalability.
Spring Boot annotations.
Spring MVC vs Spring Boot.
Fault tolerance.
How do we implement encapsulation?
How to create a thread pool?
Serialization in Java.
SpringApplication.run(CitizenServiceApplication.class, args) return value.
Capgemini Client Interview (3rd June):
ConcurrentHashMap vs HashMap.
Find the occurrence of the first character in a string using Java 8.
OOP concepts.
LinkedList vs ArrayList.
Restrict repeated characters in an ArrayList.
Custom exception implementation.
Capgemini Client Interview (2nd June):
Scope in Spring Boot.
Autowired types.
Self-join.
Configuring multiple databases in Spring Boot.
Handling exceptions in the final block.
@Component and @Autowired.
Java 8 features and functional interfaces.
Collection hierarchy.
Exception hierarchy.
Map and flatMap difference.
Class object methods.
ConcurrentHashMap and List.
Asynchronous collections.
Functional interfaces in Java 8.
Exceptions in Spring Boot.
Capgemini Client Interview (1st June):
Default interface.
Abstract class and interface differences.
Parent class of the main class.
Spring Boot entry point (@SpringBootApplication).
Features enabled by @SpringBootApplication.
Spring Cloud.
Spring Boot Actuator.
SQL query for the third-largest salary.
SOLID principles.
Design patterns.
HashMap internal working.
Is List interface or class.
Other Dates:
Solid design principles.
Rest API.
How to communicate with the REST server.
Security in projects.
Rest API error codes.
Program to generate an array of random numbers.
Argos in Java.
If Java is OOP, why use primitive data types?
Design pattern used in your project.
Stream API.
Serialization.




