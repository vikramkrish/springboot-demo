# Springboot-demo Application
This repository holds the demo of a simple Spring Boot application

This project is about a "REST API" demo. Here we have a controller called "BookController", Where it will store the and retrieve the book details, and also it will delete all the books.s

For now all the book details will be stored in system memory, moving forward the plan is to move it to SQL Database.


Default port no. for this application: 8080

**Sample REST APIs:**

| HTTP HEADERS | URI              | BODY MESSAGE                                           | PURPOSE                                            | URL                              |
|:-------------|:-----------------|:-------------------------------------------------------|:---------------------------------------------------|:---------------------------------|
| POST         | /                | {"id": 1, "name": "Maths","title": "Educational book"} | To add new books to the memory                     | http://localhost:8080/           |
| GET          | /findall         |                                                        | To list down all the books available in the memory | http://localhost:8080/findall    |
| GET          | /findbyid/1      |                                                        | To get book details by ID                          | http://localhost:8080/findbyid/1 |
| DELETE       | /delete          |                                                        | To delete all the books                            | http://localhost:8080/delete     |






## Author
- [Vikram V B](https://github.com/vikramkrish) 
