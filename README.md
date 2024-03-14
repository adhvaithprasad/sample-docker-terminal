# 🌐 Browser-Based Interactive Terminal 🖥️

This project provides a browser-based interactive terminal using Node.js for the backend and WebSocket communication.

## Features

- **Real-time Terminal Interaction**: Experience a terminal-like interface directly in your web browser.
- **Execute Commands**: Send commands from the frontend to the backend and execute them in a pseudo-terminal.
- **Display Output**: View the output of executed commands in real-time within the browser terminal.
- **Simple Setup**: Dockerized setup for easy deployment and usage.

## Installation and Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/adhvaithprasad/sample-docker-terminal
    ```

2. Build the Docker image:

    ```bash
    docker build -t <container name> .
    ```

3. Run the Docker container:

    ```bash
    docker run -d -p 3000:3000 <container name>
    ```

4. Access the browser-based terminal by navigating to `index.html` in your web browser.

## Technologies Used

- **Node.js**: Backend server environment.
- **Express.js**: Web application framework for creating the HTTP server.
- **WebSocket (ws)**: Library for WebSocket communication between frontend and backend.
- **node-pty**: Library for spawning and communicating with pseudo-terminal processes.

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests for any improvements or bug fixes.


