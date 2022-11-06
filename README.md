# computerNetworking
Running UDPClient.py and UDPServer.py: 

First, split terminal into two separate terminals (or open two terminals).

Second, run UDPServer.py. This will create a UDP socket with specified port number. After running this file, you should see "server is ready" printed in the terminal.

Third, run UDPClient.py. This will create a UDP client socket. After running this file, you will be asked to enter a sentence. Your input will be sent to the UDP server socket that you created in the second step. After receiving the input at the server side, the input will be capitalized and sent back to the client. You should be able to see your input will all of the letters capitalized on the client terminal.

Running TCPClient.py and TCPServer.py:

The procedure is exactly like running UDPClient.py and UDPServer.py. The only difference is that instead of UDP connection, a TCP connection will be established between the client and the server.
