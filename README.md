Mini Chat System

A simple console-based chat application developed in Python using Object-Oriented Programming (OOP) concepts. This project simulates a basic chatroom where users can join, leave, send messages, and view chat history.

Features
Create users and chatrooms
Users can join and leave chatrooms
Send and broadcast messages within a chatroom
Store and display chat history
Automatic message ID generation
Demonstrates core OOP principles such as classes, objects, encapsulation, and interaction between objects
Project Structure
Message Class

Represents a message sent by a user.

Attributes:

sender - User who sent the message
content - Text content of the message
id - Unique identifier for each message
User Class

Represents a user in the chat system.

Methods:

join_chatroom(chatroom) - Join a chatroom
leave_chatroom() - Leave the current chatroom
send_message(content) - Send a message to the chatroom
ChatRoom Class

Represents a chatroom where users communicate.

Methods:

add_user(user) - Add a user to the chatroom
remove_user(user) - Remove a user from the chatroom
broadcast(sender, content) - Send a message to all users
show_chat_history() - Display all previous messages
Technologies Used
Python 3
Object-Oriented Programming (OOP)
How to Run
Clone this repository:
git clone <repository-url>
Navigate to the project directory:
cd mini-chat-system
Run the Python file:
python main.py
Sample Output
Alice joined Python Lounge
Bob joined Python Lounge
(1) Alice: Hello everyone!
(2) Bob: Hi Alice!
Charlie joined Python Lounge
(3) Charlie: Hey guys, what's up?

Chat History of Python Lounge:
(1) Alice: Hello everyone!
(2) Bob: Hi Alice!
(3) Charlie: Hey guys, what's up?
Learning Objectives

This project demonstrates:

Class creation and object interaction
Encapsulation and data management
Method implementation
Object relationships
Basic simulation of real-world chat systems
Author

Developed as a Python OOP mini project.
