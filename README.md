# Chatting-module

Problem-Statement: Implementation of a server in a client/server model using Linux Stream sockets Which consists of a server that implement a chat service using simple text protocol that clients use to message other clients on the service through telnet message.


DESCRIPTION: A C program to support the server in a client/server model using LINUX stream sockets. The program will consist of a server that will implement a service (like a chat room). using simple text protocol that clients can use through telnet to message to other clients on the service. We have implemented this project using threads, for every client that is connected will be a separate thread to execute their requirements. To perform JOIN, LIST, MESG, BCST user must registered that means their record must be in the database. If they are not registered, we request them to register to perform the operations. For QUIT operation regardless of user registered or not the user can perform QUIT. If the user is registered and performs QUIT we need to remove its entry from the database. JOIN command is used to registered into database for this we need username of the specified client. LIST command will display the information of all the registered clients. MESG command is used to send message from one client to other. BCST command is used to send broadcast message to all the registered users.

