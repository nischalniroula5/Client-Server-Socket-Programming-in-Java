# Client-Server-Socket-Programming-in-Java
This project demonstrates a simple implementation of client-server communication in Java using sockets. It showcases how messages can be exchanged between a client and a server application. The communication is established through Java's socket programming, allowing messages to be sent from the client and acknowledged by the server with a "Message Received" response.

**Features**
Client Application (com.client.Client): Represents the client-side of the communication. It connects to the server, sends messages, and receives acknowledgments.

Server Application (com.server.Server): Represents the server-side of the communication. It listens for incoming connections, receives messages from clients, and responds with "Message Received" acknowledgments.

**Usage**
Clone this repository to your local machine using Git.
Open the Client and Server projects in NetBeans (included in the repository).
Compile and run the Server project to start the server application.
Compile and run the Client project to start the client application.
In the client console, enter messages to send to the server. Observe the "Message Received" acknowledgments from the server.

**Dependencies**
Java Development Kit (JDK)
NetBeans IDE (for project compilation and execution)

**Notes**
This project provides a basic foundation for understanding client-server communication using sockets. Real-world applications require additional features, security measures, and error handling.
