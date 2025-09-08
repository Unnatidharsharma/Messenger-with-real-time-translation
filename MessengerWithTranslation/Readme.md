# Messenger with Real-Time Translation

This project is a real-time chat application with translation features, built with a Spring Boot backend and a React frontend.

## Features

- Real-time messaging using WebSocket
- User authentication and authorization
- Group chat and single chat support
- Message translation in real-time
- Responsive and user-friendly UI

## Technologies Used

- Backend: Spring Boot, Spring Security, Spring Data JPA, WebSocket
- Frontend: React, Redux, Tailwind CSS
- Database: MySQL
- Build Tool: Maven

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven
- Node.js and npm
- MySQL database

### Running the Backend

1. Configure your MySQL database in `backend/src/main/resources/application.properties`.
2. Build the backend jar:
   ```bash
   cd backend
   ./mvnw clean package
   ```
3. Run the backend:
   ```bash
   java -jar target/whatsapp_clone-0.0.1-SNAPSHOT.jar
   ```

### Running the Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm start
   ```

## How to Use

- Register or sign in to the application.
- Create or join group chats.
- Send messages and see real-time translations.
- Manage your profile and settings.

## Contribution

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License.
