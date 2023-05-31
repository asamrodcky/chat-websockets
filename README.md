# React WebSocket App

This is a WebSocket App built using React.js, which allows real-time communication between clients and the server. The app utilizes the Socket.IO library for WebSocket functionality. This project was built to learn about WebSockets and the Socket.IO library.

## Technologies Used

- React.js
- JavaScript
- HTML
- CSS
- Socket.IO

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies by running `npm install` in your terminal.
4. Run the project using `npm run dev`.
5. Open the project in your web browser by navigating to `http://localhost:3000`.

## How to Use

The WebSocket App allows real-time communication between clients and the server. Users can send and receive messages in real-time. When a new client connects to the server (one of the chatrooms), they can assign themselves a username. Users can then send messages, which will be instantly displayed to all connected clients. This app demonstrates the power of WebSockets for real-time communication.

## Development Process

This project was built using React.js, with the WebSocket functionality implemented using the Socket.IO library. The app has a client-side component that manages the WebSocket connection and handles sending and receiving messages. The server-side component handles the WebSocket connection, assigns usernames, and broadcasts messages to all connected clients.

## Conclusion

This project was built to learn about WebSockets and the Socket.IO library. It demonstrates how to establish a real-time communication channel between clients and the server using React.js. By building this app, you can gain a better understanding of WebSocket technology and how to utilize the Socket.IO library in your own projects for real-time communication requirements.