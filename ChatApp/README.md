# Real-Time Chat Application


Welcome to my real-time chat application, built from scratch to provide a seamless and secure messaging experience. The application is designed to handle real-time communication between users, with a focus on security, scalability, and user-friendly design.

## Features

1. *Real-Time Communication*: Instant messaging with live updates using Socket.io.
2. *Secure Authentication*: User data is protected with JWT tokens and bcrypt.js for password hashing.
3. *Responsive UI*: Clean and responsive user interface designed with Daisy UI, optimized for both desktop and mobile devices.
4. *User Management*: Full user management system including registration, login, and profile updates.
5. *Scalability*: Designed to support multiple users simultaneously, with 10+ active users currently using the application.
6. *Persistent Chat History*: All chat data is stored in MongoDB, ensuring users can access their chat history anytime.
7. *Easy Deployment*: Built with a modular structure, making it easy to deploy and maintain.

## Tech Stack

- *Frontend*: ReactJS
- *Backend*: NodeJS with Express
- *Database*: MongoDB
- *Authentication*: JWT Token, bcrypt.js
- *Real-Time Communication*: Socket.io
- *UI Design*: Daisy UI
- *Version Control*: Git and GitHub

## How It Works

1. *User Registration and Login*:

   - Users can register with a unique username and password.
   - Passwords are hashed using bcrypt.js before being stored in MongoDB.
   - Upon successful login, a JWT token is issued, which is used for secure session management.

2. *Real-Time Messaging*:

   - Users can send and receive messages in real time.
   - Messages are broadcast to all connected users using Socket.io.
   - Chat history is saved in MongoDB, allowing users to view past conversations.

3. *Security*:

   - JWT tokens ensure that only authenticated users can access the chat features.
   - Passwords are never stored in plain text, ensuring user security.


