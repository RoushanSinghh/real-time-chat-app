# Real Time Chat Application

## Overview

This Real Time Chat Application enables multiple users to engage in real-time conversations without storing any data on servers or devices. Built with Socket.IO, Node.js, Mustache, HTML5, and CSS3, it offers a seamless chat experience prioritizing privacy.

## Getting Started

### Server
1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies with `npm install`.
4. Start the server using `node server.js`.

### Client
1. Open your web browser.
2. Enter the server URL (e.g., `http://localhost:3000`).
3. Enter a username and choose a chat room.
4. Start chatting in real-time.

## Architecture

Utilizes a client-server model with Socket.IO for real-time communication.
- **Server**: Built with Node.js and Socket.IO, managing connections and broadcasting messages.
- **Client**: HTML5, CSS3, and Mustache for dynamic rendering. Utilizes Socket.IO for real-time bidirectional communication.

## Assumptions and Design Choices

- **No Data Storage**: Prioritizes privacy by not storing any data on servers or clients.
- **Socket.IO**: Chosen for its simplicity and real-time communication capabilities.
- **Mustache for Templating**: Allows dynamic rendering of HTML content based on server data.

## Accessing the Chat Application

Once the server is running, users can access the chat application through any web browser by entering the server URL. They'll be prompted to choose a username and chat room to begin real-time interactions.

## Conclusion

The Real Time Chat Application offers a simple yet privacy-focused platform for real-time conversations. Leveraging Socket.IO, Node.js, Mustache, HTML5, and CSS3, it ensures a seamless chat experience while maintaining data privacy and security.
