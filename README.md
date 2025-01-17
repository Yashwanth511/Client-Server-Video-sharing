This project demonstrates a simple video streaming application using Python's socket programming. It consists of a server and a client:

Server captures video from the host's webcam and streams it to the client.
Client receives and displays the streamed video.
Features
Real-time video streaming over a TCP connection.
Easy setup and configuration.
Uses OpenCV for video processing.
Requirements
Ensure you have the following installed:

Python 3.x
OpenCV (cv2)
Imutils (pip install imutils)
Files
server.py
Handles the video streaming server-side:

Captures video using the system's webcam.
Transmits video frames to the client via TCP.
client.py
Handles the client-side:

Receives video frames from the server.
Displays the video in real time.
Usage
Step 1: Configure the Server
Run the server.py script on the host machine.
Note the host's IP address printed in the console.
Step 2: Configure the Client
Update the host_ip in client.py with the server's IP address.
Run the client.py script on the client machine.
Step 3: Start Streaming
Press q on either the client or server window to terminate the connection
