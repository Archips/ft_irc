# ft_irc (ircserv)

The "ircserv" project involves the development of an IRC (Internet Relay Chat) server using C++ 98. This server is designed to accept incoming connections on a specified port and requires a password for client authentication. Its primary goal is to replicate the functionality of an IRC server, allowing clients to authenticate, set nicknames, join channels, send and receive private messages, and perform channel-specific operations. The server should be non-blocking, supporting multiple simultaneous clients and efficient I/O operations using polling or equivalent mechanisms.

## Score

-  125%

## Project Highlights:
- Developed in C++ 98, focusing on creating a functional IRC server.
- Supports client authentication with a password.
- Allows clients to set nicknames, join channels, send and receive messages, and perform channel-specific operations.
- Ensures non-blocking operations without using forking.
- Utilizes polling or equivalent mechanisms for efficient I/O handling.
- Ensures compatibility with a reference IRC client for evaluation.
- Offers optional features like file transfer and a bot for extended functionality.

## Usage:
To use the "ircserv" server, follow these steps:

1. Compile the server using the provided Makefile and appropriate build commands.
2. Run the server using the following command:
  `./ircserv <port> <password> `
  - `<port>`: The port number on which the server will listen for incoming connections.
  - `<password>`: The password required for client authentication.
3. Connect IRC clients (nc or irssi) to the server using the provided port and password.

## Authors

Archibald Thirion  
Cristina Mois   
Léa Murtin
