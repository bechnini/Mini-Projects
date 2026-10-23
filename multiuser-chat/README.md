# MultiUser Chat
Lets break it down together :p
## Client
Its mostly as every client in the world , connects to the server and waits for data to come in , tho we arent only waiting for data we are also waiting for the user to send it so we use multithreading to solve this problem
## Server
In this server we use select to be able to handle more than one user at a time 
