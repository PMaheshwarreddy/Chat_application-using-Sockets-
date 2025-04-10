🗨️ Java Chat Application (Client-Server Model)

Welcome to the Java Chat Application! This is a simple real-time chat
application built using Java Swing for the user interface and Sockets (TCP) for communication between a client and a server.
📌 Features





✅ Real-time Messaging between a client and a server

✅ Graphical User Interface (GUI) using Java Swing

✅ Multi-threaded Server to handle multiple clients (extendable)

✅ Chat Bubbles with Timestamps for better conversation experience

✅ Attractive UI Design inspired by modern chat apps

✅ Exit Button Functionality to close the chat application


🛠️ How to Run

1️⃣ Clone the Repository

git clone https://github.com/your-username/Java-Chat-App.git

cd Java-Chat-App

2️⃣ Compile & Run the Server

javac Server.java

java chatting.application.Server

3️⃣ Compile & Run the Client

javac Client.java

java chatting.application.Client



📜 Project Structure

📂 Java-Chat-App

 ┣ 📂 icons             # Contains images for UI icons
 
 ┣ 📜 Client.java       # Client-side application
 
 ┣ 📜 Server.java       # Server-side application
 
 ┣ 📜 README.md         # Project documentation

 
📌 How It Works

The server listens on port 6001 and waits for a client to connect.

The client establishes a connection with the server using Sockets.

Messages sent from the client appear on the server-side (and vice versa).

The messages are formatted into chat bubbles with timestamps.

The application follows a single-threaded client-server model but can be extended for multiple clients.

🤝 Contribution
Feel free to fork this repository and submit pull requests. If you have any ideas for improvements, create an issue!

📝 License
This project is open-source and available under the MIT License.

⭐ If you like this project, don't forget to give it a star on GitHub! ⭐
