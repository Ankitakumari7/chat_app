# chat_app
A Local Area Network Messaging App

Language Used
* C++


A minor project for 3rd Sem OOP project
Feautres

Multi Client Handling Server using select()
Read / Write at same time using timers and non-blocking mode
File transfer ( Under Development )
Group Chat
Online Clients information
User friendly GUI
Login System ( Enter username, default password is password )


Usage:

set the ip address and port in the server.hpp and client.cpp as per requirements
build and run server.cpp on terminal
build main.cpp on other terminal
open the exe file as much as you can and enjoy chatting. (10 max Clients)
->for server:
g++ server.cpp -o server
./server

->for client
g++ main.cpp Client.cpp -o main pkg-config --cflags --libs gtkmm-3.0
./main
