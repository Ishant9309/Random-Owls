# Random Owls

A real-time one to one chat web application built using Java 17, MySQL, Spring Boot, Spring Security, WebSocket, and Thymeleaf. This application allows users to chat with other users is a seperate environment, featuring a modern tech stack with a responsive user interface.

## Team Member:
  - # Ishant Teli
  - # Rohit Tamkhane
  - # Tanvi Bagate

## Features

- **Instant Messaging**: Seamless, real-time communication enabled by WebSocket technology for instantaneous message delivery.
- **Secure Login and Registration**: User authentication and access management powered by Spring Security for a robust and secure experience.
- **User Notifications**: Instant alerts for new messages and user activity, such as logins, ensuring you stay updated in real-time.
- **Chat History Persistence**: Effortless storage and retrieval of chat data from a MySQL database, providing access to previous conversations anytime.
- **Responsive Interface**: Optimized for all devices using Bootstrap, delivering a consistent and user-friendly design across platforms.
- **Integrated Social Media Links**: Quick access to social profiles directly from the chatroom header for easy networking.

## Tech Stack

- **Backend**: Java 17, Spring Boot, Spring Security, MySQL Database, Lombok
- **Frontend**: Thymeleaf, Bootstrap, Font Awesome
- **Real-Time Communication**: Spring WebSocket, STOMP protocol
- **Build Tool**: Maven

## Setup Instructions

### Prerequisites
- Java 17 or higher
- Maven 3.6+

### Steps to Run Locally

   
1. Create MySQL database using [SQLScript](src/main/resources/static/sql-script/SQLScript.txt)

2. Update MySQL password in [application.properties](src/main/resources/application.properties)

3. **Build the Project**:
   ```sh
   mvn clean install
   ```

4. **Run the Application**:
   ```sh
   mvn spring-boot:run
   ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:8080`.

## Usage

- **Login**: Create a new account or securely log in using your existing credentials to access the platform.
- **Chat**: Engage in real-time conversations with other users. Stay informed with instant notifications when new users join or send you messages.


## Contact

For permissions related to commercial use or any questions, please contact: Rohit Tamkhane (rohittamkhane76@gmail.com)

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project.

## Screenshots

![Login Page](<img width="1913" height="880" alt="image" src="https://github.com/user-attachments/assets/2bc1a600-a1a3-41d7-b7e2-85d84ea150e0" />
)
![Register Page](<img width="1913" height="878" alt="image" src="https://github.com/user-attachments/assets/3735b829-6ae2-4cac-9394-532b29ba6d40" />
)
![Chat App Page](<img width="1916" height="867" alt="image" src="https://github.com/user-attachments/assets/d366be2e-56c5-4143-8239-418604b29724" />
)

## Future Enhancements

- **Profile Management**: Update username, details, or profile picture.
- **Privacy Controls**: Block or restrict messages from others.
- **Message Encryption**: Ensure secure chats with encrypted storage and transmission.
- **Media Sharing**: Share images and files effortlessly in chats.
- **Voice Messaging**: We can Try to Add The Voice Messaging Function.

