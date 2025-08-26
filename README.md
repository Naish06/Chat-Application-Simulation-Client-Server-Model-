# Chat-Application-Simulation-Client-Server-Model-
A simple socket-based chat application implemented in Python using the client–server model and multithreading.
The project demonstrates real-time message broadcasting between multiple clients connected to a central server.

**Features**<br>
Server:<br>
- Handles multiple client connections concurrently using threads.
- Broadcasts incoming messages to all connected clients.
- Cleans up disconnected clients gracefully.
Client:<br>
- Connects to the server and exchanges messages.
- Uses a dedicated thread to continuously receive incoming messages.
- Simulates user interaction with predefined messages and delays.

Simulation:<br>
- Runs a server in the background.
- Spawns multiple simulated clients (Alice, Bob, Charlie) that chat with each other.
- Demonstrates concurrency, networking, and message passing.

**Technologies**<br>
- Python 3
- Socket Programming (TCP/IP)
- Multithreading

**Project Structure**<br>
`chat_app.py`    # Contains server, client, and simulation code

**How to Run**<br>

Clone the repository:<br>

`git clone https://github.com/your-username/chat-app-simulation.git
cd chat-app-simulation`

Run the script:

`python chat_app.py`


Watch the server start and clients exchange messages.

**Example Output**
`[SERVER STARTED] Listening on port 5000...`<br>
`[NEW CONNECTION] ('127.0.0.1', 54321)`<br>
`[NEW CONNECTION] ('127.0.0.1', 54322)`<br>
`[NEW CONNECTION] ('127.0.0.1', 54323)`<br>
`[SERVER RECEIVED] Alice: Hi!`<br>
`[Bob RECEIVED] Alice: Hi!`<br>
`[Charlie RECEIVED] Alice: Hi!`<br>
`...`<br>
`[CHAT SIMULATION COMPLETE]`<br>
