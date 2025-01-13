# Socket.IO Real-Time Chat

This project is a real-time chat application based on **Socket.IO**, using **Flask** for the backend and **HTML/JavaScript** for the frontend. It is a simple example of how to implement two-way communication between a client and a server.

---

## Features

- Real-time communication between client and server.
- Support for multiple connected users.
- Automatic chat update for all connected clients.
- Based on modern technologies like **WebSockets** and **Socket.IO**.

---

## Technologies Used

- **Python** with **Flask** and **Flask-SocketIO**.
- **Socket.IO** for two-way real-time communication.
- **HTML** and **JavaScript** for the frontend.

## Project Structure

```plaintext
SOCKETIO/
├── server.py              # Servidor Flask con integración de Socket.IO
├── templates/
│   └── index.html         # Interfaz del cliente (frontend)
└── README.md              # Documentación del proyecto
```

## Instructions for Using the Project
1. Clone the Repository

To clone this repository, use the following command:

 ```bash
 git clone https://github.com/tu_usuario/socketio-chat.git

 ```

2. Install the necessary dependencies:
Initialize and download the dependencies Required dependencies:
 
 ```bash
 pip install flask flask-socketio

 ```

3. Run the Server
Start the REST API server:
 
 ```bash
  python server.py
 
 ```
4. Open your browser and go to:

 http://localhost:5000

## How It Works
Client-Server Connection:

1. When the client accesses the server URL, a WebSocket connection is established using the Socket.IO library.
Message Exchange:

2. The client sends messages to the server, and the server retransmits them to all connected clients.
Real-Time Update:

3. Messages are dynamically updated on the page without the need to reload it.

## Author
EDWIN PROAÑO
GitHub: Daniielpro10