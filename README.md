
### Tic-Tac-Toe

+ The objective of this code is to implement a barebones version of two player tic-tac-toe game. 
 This is the first approach in its implementation of this game.Html and CSS are both use for frontend while JavaScript is for interactive with the game.Though this one work very well, its can't handle game state and session. 

   <a href="http://initialtic-tac-toe.bitballoon.com/"target="target">InitialTic-tac-toe</a>

+ In the second approach the game is implemented with Node.js server and a client with javascript applications.


### Tools Used
+ Node.js
+ Javascript
+ Json API
+ HTML 5
+ CSS 3

### How to run the Application

This version has been written on a Windows x32 system and some incompatibility may occur.

To install, clone the repo in the target system

#### Backend

+ Install Node.js based on your OS architecture. Use the default NPM(Node package manager)
+ Charge directory to current working directory and start the server.
+ The server responds to POST requests with json formatted data. The client should send init as the first command. While no response is received, the client is the only connected to the room given and game can't be started. As soon as there is second player, the server responds to the init command, telling each client which player it is.

#### Frontend
+ Go to clone repo and right click on client.html to your prefer browser. 
+ Wait for connection to complete and other player to join.
+ Enjoy the game.

