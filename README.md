# raspberrypi-socket-comm
raspberry pi socket programming
# To compile the basic server:

Bash

# g++ server-accept.cpp -o basic_server
# 2. Compile the Client
Bash

# g++ client-receive-data.cpp -o client
# 3. Run the Programs
First, start the server:

Bash

# ./server
Then, in a separate terminal or device, run the client.
Note: You may need to update the IP address in the client source code to match your server's local IP (e.g., 127.0.0.1 for local testing).

# Implementation Details
# Protocol: TCP (SOCK_STREAM)

# Port: 8888 (Server) / 80 (Client default example)

# Address: INADDR_ANY is used in servers to bind to all available interfaces.
