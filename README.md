# Event_Management
This project is a simple Event Management System developed using Spring Boot. It is designed to demonstrate the core concepts of backend development along with a basic user interface. The application allows users to perform full CRUD operations (Create, Read, Update, Delete) on events. Each event contains details such as name, location, and date. The project follows a clean MVC architecture using controllers, services, repositories, and entities.

The backend of the application is built using Spring Boot 4.x with Spring Data JPA for database interactions. An H2 in-memory database is used, which makes the application easy to run without any external database setup. RESTful APIs are implemented to handle event operations, and these APIs can be tested using tools like Thunder Client or Postman. For frontend rendering, Thymeleaf is used to display event data dynamically on a web page.

The application provides REST endpoints to fetch all events, fetch a single event by ID, create new events, update existing events, and delete events. The UI can be accessed through a browser and displays all events in a tabular format. The H2 database console is also enabled, allowing easy inspection of database records during development.

This project is built using Java (JDK 21/25) and managed with Maven. It was developed in IntelliJ IDEA and follows best practices for beginner-level Spring Boot applications. The project helps in understanding how backend APIs integrate with a frontend template engine, how data flows through different layers of an application, and how Spring Boot simplifies enterprise application development.

In the future, the project can be enhanced by adding forms for creating and updating events from the UI, adding delete buttons, integrating a persistent database like MySQL, implementing validation and exception handling, and improving the user interface using frameworks like Bootstrap.

This project was developed by Ansh Tandon, a first-year Computer Science Engineering student, as a learning exercise to gain hands-on experience with Spring Boot, REST APIs, database integration, and basic UI development.
