# Wholesale Management System

The Wholesale Management System is a Java-based application designed to streamline wholesale operations for businesses. It provides tools for managing inventory, orders, customers, and user authentication.

## Technologies Used

- **Java**: The core programming language used for developing the backend logic and business logic of the application.
- **JavaFX**: A Java library for creating desktop applications with rich graphical user interfaces (GUIs). Used for building the frontend user interface.
- **MySQL**: An open-source relational database management system used for storing and managing data related to inventory, orders, customers, etc.
- **Maven**: A build automation tool used for managing dependencies and building the project.
- **MySQL Connector/J**: A JDBC driver for connecting Java applications with MySQL databases.
- **FXML**: A markup language for defining user interfaces in JavaFX applications.

## Architecture

The Wholesale Management System follows a three-tier architecture:

- **Presentation Layer**: The user interface is developed using JavaFX, providing a modern and intuitive interface for users to interact with the system.
- **Business Logic Layer**: Java classes encapsulate the business logic of the application, including functionalities for managing inventory, processing orders, managing customers, etc.
- **Data Access Layer**: DAO (Data Access Object) classes handle interactions with the MySQL database, including CRUD operations for accessing and manipulating data.

## Installation

To run the Wholesale Management System locally, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Java Development Kit (JDK) installed (version 8 or higher).
3. Set up a MySQL database and import the provided `databaseSchema.sql` file to create the necessary tables.
4. Update the database connection settings in the `DatabaseUtils.java` file if needed.
5. Compile the Java files: `javac src/main/java/com/example/wholesalemanagementsystem/*.java`
6. Run the application: `java -cp src/main/java com.example.wholesalemanagementsystem.Main`

## Usage

Once the application is running, you can use the user interface to perform various tasks such as managing inventory, creating orders, and managing customers. The interface is designed to be user-friendly and intuitive, providing easy navigation and operation.

