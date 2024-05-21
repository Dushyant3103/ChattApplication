Desktop Chat Application
This project is a simple desktop chat application developed using Java Swing, AWT, and Socket Programming. The application allows multiple users to communicate with each other in real-time over a network.
Features
1.Real-time messaging between clients.
2.User-friendly graphical interface using Java Swing and AWT.
3.Supports multiple clients connecting to the server simultaneously.

Technologies Used
1.Java Swing and AWT for GUI components.
2.Java Socket Programming for network communication.

Getting Started
Prerequisites
To run this application, you need to have Java Development Kit (JDK) installed on your system. You can download it from Oracle's official website.

Installation
Clone the repository:

sh
Copy code
git clone[ https://github.com/yourusername/DesktopChatApplication.git](https://github.com/Dushyant3103/ChattApplication)
cd DesktopChatApplication
Compile the code:

sh
Copy code
javac -d bin src/*.java
Run the server:

Open a terminal and navigate to the bin directory:

sh
Copy code
cd bin
java Server
Run the client:

Open another terminal, navigate to the bin directory, and start a client:

sh
Copy code
java Client
Repeat this step for each additional client.

Usage
Starting the Server:

Run the Server class to start the chat server. This will allow clients to connect and start chatting.

Connecting Clients:

Run the Client class to start the chat client. Enter a username and connect to the server. You can open multiple clients to simulate different users.

Chatting:

Once connected, users can send and receive messages in real-time. The chat window will display all messages from all connected users.

Project Structure
python
Copy code
DesktopChatApplication/
│
├── src/
│   ├── Server.java       # Main server-side application
│   ├── Client.java       # Main client-side application
│   └── Message.java      # Message class for message objects
│
├── bin/                  # Compiled bytecode files
│
├── README.md             # Project readme file
│
└── LICENSE               # License file
Classes Description
Server.java: Handles client connections, message broadcasting, and managing connected clients.
Client.java: Manages the client-side GUI and communication with the server.
Message.java: Represents a message object with sender, content, and timestamp.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the coding standards and include appropriate tests.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
If you have any questions or suggestions, feel free to contact me at dushyantsinghvishani@gmail.com.


