# MULTITHREADED-CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: HAMEED HILAL

*INTERN ID*: CT04XHI

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# PROJECT DESCRIPTION

In today's digital era, real-time communication has become an essential aspect of our daily lives, and chat applications play a crucial role in enabling seamless interactions. This project, "Multithreaded Console-Based Chat Application," is designed to provide an efficient and lightweight chat system where multiple users can communicate with each other in real time through a centralized server. Built using Java Sockets and Multithreading, this application ensures smooth and concurrent communication between multiple clients while maintaining simplicity through a console-based interface. Unlike traditional single-threaded chat systems, which can handle only one user at a time, this project leverages multithreading to accommodate multiple clients simultaneously without performance degradation.

The chat system consists of three key components: the Chat Server, the Client Handler, and the Chat Client. The Chat Server is responsible for accepting incoming client connections and managing message broadcasting to all connected users. When a client joins, the server assigns a separate Client Handler thread to that user, ensuring that multiple clients can exchange messages independently. The Chat Client component allows users to connect to the server, enter a unique username, send messages, and receive real-time updates from other participants. The server continuously listens for messages from clients and efficiently relays them to all connected users, ensuring a smooth and uninterrupted chat experience.

One of the core features of this project is its ability to handle multiple users concurrently. Each connected client runs on a separate thread, preventing any single client from blocking the communication process. Additionally, the server maintains a list of active users, enabling new participants to receive real-time updates when someone joins or leaves the chat. The application also includes join and leave notifications, ensuring that all users are aware of active participants in the chatroom. This real-time synchronization is made possible through synchronized broadcasting, where messages are sent to all clients except the sender.

From a technical perspective, the project utilizes Java Networking for establishing connections and Multithreading for handling multiple users simultaneously. The ChatServer.java file initializes a server socket and continuously listens for new connections, while the ClientHandler.java file manages the interaction between the server and individual clients. The ChatClient.java program enables users to enter a unique username and participate in conversations. The communication is facilitated using input and output streams, allowing seamless data transfer between the server and clients. The server also logs all messages, ensuring proper monitoring and debugging if needed.

To use the application, the server must be started first, allowing it to accept incoming connections. Once the server is running, multiple clients can launch the ChatClient program, enter their usernames, and begin chatting. Messages typed by one user instantly appear on all connected clients, creating a real-time group chat environment. When a user decides to disconnect, the server notifies all remaining participants, ensuring an organized communication flow.

This project serves as a great foundation for learning network programming, concurrent processing, and server-client communication in Java. It can be further enhanced with additional features such as Graphical User Interface (GUI) integration, private messaging, user authentication, file sharing, and chat history storage. The Multithreaded Console-Based Chat Application is an excellent demonstration of how Java Sockets and Multithreading can be used to create a scalable and efficient chat system, making it a valuable project for students and developers interested in real-time communication systems.

# OUTPUT

*SERVER CONNECTION*

*CLIENT CONNECTION*

*MULTI CLIENT CONNECTION*

*CLIENT DISCONNECTIONS*
