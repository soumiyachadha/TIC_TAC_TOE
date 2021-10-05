# TIC_TAC_TOE
This project outlines the steps involved in socket programming and the
deployment of a server-client connection. It presents the steps of a game of
noughts and crosses along with a practical implementation of the same, using
TCP.
The result of simulation and of post-deployment revealed the successful
working of the connection, with the game being played by both, the server and
the client.
All the necessary information needed in the project is documented below:
Socket programming: It is a way of connecting two nodes on a network to
communicate with each other. One socket listens on a particular port at an IP,
while the other socket reaches out to the other to form a connection.
The server forms the listener socket while the client reaches out to the server.
Protocol: TCP
Variables: socket_id, bind_id, choice of client and server.
Methods: socket(), bind(), listen(), accept(), connect(), send(), recv(),
checkwin(), board()
Structure: sockaddr_in for setting the ip family, address, portno.
