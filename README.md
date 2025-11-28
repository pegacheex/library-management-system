# Library Management System

A JavaFX-based Library Management System that supports multiple libraries, book management, member management, and transaction tracking using MongoDB as the database.

## Features

- Support for multiple libraries
- Book management (add, update, delete, list)
- Member management (register, update, remove)
- Book borrowing and return tracking
- MongoDB integration for data persistence
- Modern JavaFX UI with FXML

## Prerequisites

- Java 17 or later
- Maven 3.6 or later
- MongoDB 4.4 or later
- JavaFX SDK 17 or later

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd LibraryManagementSystem
```

2. Make sure MongoDB is running on your system:
```bash
# Start MongoDB service
mongod
```

3. Build the project using Maven:
```bash
mvn clean install
```

4. Run the application:
```bash
mvn javafx:run
```

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── library/
│   │           ├── Main.java
│   │           ├── controller/
│   │           ├── model/
│   │           └── util/
│   └── resources/
│       └── fxml/
```

## Database Schema

The application uses MongoDB with the following collections:
- libraries
- books
- members
- transactions

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 