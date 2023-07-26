# Spring guide: Accessing Data with JPA

### How are query methods defined when using Spring Data JPA?

Query methods in Spring Data JPA are defined by method signatures in the repository interface following a naming convention that automatically generates database queries.

### Which dependencies will you need in order to complete the Spring guide?

To complete the Spring guide, you will need specific dependencies for Spring Boot and Spring Web.

### What annotations are used to specify an auto generated identification number for an Entity?

you can use the @Id and @GeneratedValue annotations.

# Baeldung: Comparing repositories (we’ll be using JpaRepository)

### Which of the Spring Data Repositories covered in the readings has the most methods available to it?

Among the Spring Data Repositories covered in the readings, JpaRepository has the most methods available to it

### Name a downstide of a Spring Data Repository.

The downside of a Spring Data Repository is reduced control over the generated database queries

### How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?

 you can define the method as findByStudentName(String name)

References 

https://canvas.instructure.com/courses/7139363/discussion_topics/18669322#submit

https://www.baeldung.com/spring-data-repositories






