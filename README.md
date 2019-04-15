# spring-mvc-hibernate-CRM

This is a web application created by using Spring MVC, Hibernate and MySQL.  

We can do CRUD operations on Customers. We can add customers, view them, update and delete them.  

* Controller layer has all the logic of handling requests and serving .jsp forms  
* Service Layer is only implemented as a good design practice and it delegates the requests to the DAO, as we only have one DAO.
* DAO with the help of Hibernate handles all the interaction with a SQL Database.  

