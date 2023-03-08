# Todo Application
#### This is a simple Todo application built with Spring Boot that allows users to create, read, update, and delete tasks.

# Technologies Used
- Spring Boot
- H2 database
- Maven

# Setup
### Prerequisites
#### Before you can run this application, you need to have the following installed on your computer:

- Java 8 or higher
- MySQL
- Getting Started

### To get started with this application, follow these steps:

1. Clone this repository to your local machine.
2. Open the project in your favorite IDE (such as IntelliJ IDEA or Eclipse).
3. Open the application.properties file located in src/main/resources and set the MySQL database username and password.
Run the application.

## Usage
### Once the application is running, you can access the following URLs:

- `GET /` - Displays a list of all tasks
- `GET /create` - Displays a form to create a new task
- `POST /create` - Creates a new task
- `GET /edit/{id}` - Displays a form to edit an existing task
- `POST /edit/{id}` - Updates an existing task
- `GET /delete/{id}` - Deletes an existing task

# Project Summary
The Todo Application is a simple Spring Boot project that allows users to create, read, update, and delete tasks. The project includes the following components: controller, model, repository, service, and unit tests. The project uses MySQL as a database and Thymeleaf as a templating engine. The project is easy to set up and use, and provides a good starting point for developing more complex Spring Boot applications.
