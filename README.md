# Chat Application 💬

A simple real-time chat application built using Python, Socket Programming, and Tkinter.

## Features

- Real-time messaging
- Client-Server architecture
- Graphical User Interface (Tkinter)
- Multiple clients can connect to the server
- Simple and user-friendly design
- Lightweight and easy to run

## Technologies Used

- Python 3
- Socket Programming
- Tkinter
- Threading

## Project Structure

```
ChatApp/
│
├── server.py
├── client.py
├── GUI.py
└── README.md
```

## How It Works

1. The server starts and listens for incoming connections.
2. Clients connect to the server using sockets.
3. Messages sent by one client are broadcast to all connected clients.
4. The GUI allows users to send and receive messages easily.

## Installation

### Clone the Repository

```bash
git clone <your-repository-url>
cd ChatApp
```

### Requirements

Python 3.x

Verify installation:

```bash
python --version
```

## Running the Application

### Step 1: Start the Server

```bash
python server.py
```

Expected output:

```text
Server started...
```

### Step 2: Launch Chat Clients

Open one or more terminals and run:

```bash
python GUI.py
```

or

```bash
python client.py
```

## Screenshots

Add screenshots of your chat application here.

Example:

```
screenshots/chat-window.png
```

## Future Enhancements

- User Authentication
- Multiple Chat Rooms
- Message History
- Emoji Support
- File Sharing
- End-to-End Encryption
- Notifications
- Dark Mode

## Learning Outcomes

This project helped me understand:

- Socket Programming
- Networking Concepts
- Client-Server Communication
- Multithreading
- GUI Development with Tkinter

## Author

CHARVI MALAKA

## License

This project is open-source and available under the MIT License.
