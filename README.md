 The project comprises a simple client-server architecture for a calculator application. The server, 
running on port 5000, continuously listens for incoming client connections. Upon connection, the 
server receives mathematical expressions from clients, processes them using a calculate 
method, and returns the results. The calculate method handles a variety of mathematical 
operations, including basic arithmetic, exponentiation, trigonometric functions, and more. 
The server operates indefinitely, providing a continuous service to multiple clients. The client 
program allows users to interact with the server by entering mathematical expressions through 
the console. The client establishes a connection with the server, sends user input, receives and 
displays the server's responses, and can exit the interaction by typing "exit." 
The project showcases a basic distributed computing scenario where clients delegate 
mathematical computations to a server. It serves as a foundation for a scalable calculator system 
that could be extended with additional functionalities, improved user interfaces, or integrated into 
larger distributed applications. The implementation demonstrates socket programming, 
input/output handling, and error management in a networked environment. 
