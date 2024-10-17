# README.md

## Eclair Chat Server in Python

This project implements a simple chat server in Python using sockets and threading. Users can connect to the server, register their usernames, and exchange messages in real time.

### Key Features

- **User Registration**: Users can choose unique usernames that are used for identification in the chat.
- **Message Exchange**: Users can send text messages that are displayed to all other participants in the chat.
- **Logging**: All messages and user actions are saved in a log file (`log.txt`), allowing for activity tracking.
- **Disconnection Handling**: The server correctly handles client disconnections, notifying other participants in the chat.

### How to Run

1. Clone the repository:
   ```bash
   git clone <URL>
   cd <repository>
   ```

2. Start the server:
   ```bash
   python server.py
   ```

3. Start the client in another terminal window or on a different device:
   ```bash
   python client.py
   ```

4. Log in using the command:
   ```
   /username <your_username>
   ```

### Future Development in C++

In the future, we plan to port this chat implementation to C++, which will improve performance and reduce latency. This version will provide greater flexibility and control over low-level network operations.

### Requirements

- Python 3.x
- Libraries: `socket`, `threading`
