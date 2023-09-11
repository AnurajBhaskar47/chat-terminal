# Terminal-Based Chat App using Python and TCP Sockets

This is a simple terminal-based chat application built using Python and TCP socket programming. It enables users to communicate with each other over a TCP socket connection and provides a command-line interface for sending and receiving messages in real-time.

![image](https://github.com/AnurajBhaskar47/chat-terminal/assets/97795939/59827f56-f9cb-4830-8a81-abfd0eb071f1)

## Features

- **TCP Socket Communication**: The chat app leverages Python and TCP sockets to establish connections between clients, enabling real-time chat functionality.
- **Server-Client Architecture**: It follows a server-client architecture where one user runs the server, and others can connect as clients.
- **Private Messaging**: Users can send private messages to a specific client by specifying their username.
- **Group Chat**: Users can participate in group chats with multiple clients connected to the server.
- **User Authentication**: Basic username authentication to identify clients.
- **Simple Command Syntax**: Easy-to-use commands for sending messages and switching between different chat modes.

## Getting Started

To use this chat app, follow these steps:

### Prerequisites

- You need to have Python installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AnurajBhaskar47/chat-terminal.git



For simple understanding, the clients connect to the same Chatroom (Server) at a given time. When the respective users join the server, they are given nicknames(tokens) for respective clients. This enables for a simple & easy TCP implementation for sharing messages on a terminal for devices connected to the same network.
