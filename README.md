### spring-boot-rest-api-crud-hibernate

## Real time projects with rest APIs to perform CRUD operations via PostMan on a database 

These projects are based on lessons given by Chad Darby'course: Spring and Hibernate on Udemy, which is a "must-be" - in my humble opinion - both for an entry level or even en experienced developer in Spring. This course is very seasoned and give you a systematic approach in the world of Spring and Hibernate. 

Ok, for this repository I am showing four projects to perfom CRUD operations on a table in MySQL. The difference is in which implementation I used to perfom the ORM based on the JPA standard.

- First: Hibernate
- Second: JPA
- Third: Spring data JPA
- Spring data Rest

Now, I will show some screenshot that I took when I was testing the code with PostMan... In general for the first three projects the response is similar, the differences is in how you implement operations on the back-end to perform them. The project with Spring data JPA is less boilerplate than the two former: Hibernate and JPA. Why?  Because you do not need to write code for every operation like: get, put, delete or post. They are implemented by Spring Data JPA!

Table where the operations are performed 
![Initial Table](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/SQL_table_init.png)

Some examples with Postman - (The results are similar for the first three projects)

![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/postman_get.png)


![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/postman_post.png)


![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/postman_put.png)


![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/postman_delete.png)

In this last part, I will show some screnshoot when I was testing basic CRUD operations via Postman in the last project: Spring Data Rest. This library has more advanced features like pagination, sorting and send responses according to HATEOAS specification. And of course CRUD operations are included in the library like it was in Spring data JPA. 

![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/hate_oas_info_get.png)

![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/hate_oas_info_post.png)

![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/hate_oas_info_put.png)

![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/hate_oas_info_delete.png)

![a](https://github.com/caivosco/spring-boot-rest-api-crud-hibernate/blob/main/cruddemo/cruddemo/src/main/resources/images/hate_oas_sorting.png)

## Technologies

# Backend
- Languaje: Java 1.8
- Database: MySQL
- ORM: Hibernate, JPA, Spring JPA, Spring data rest
# Frontend
- Postman
# Tools
- MySQL Workbench
- GitBash
- Eclipse Version: 2020-06 (4.16.0)
- Github
# Support
- Course's Q&A
- Stackoverflow
- Searching :)



