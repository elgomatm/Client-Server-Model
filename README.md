# Client-Server-Model
How to run:

- Open two Shell Terminal(Putty in my case)
-To get server to run, type chmod a+x server
-To get client to run, there is a make file for client so just type make
-./client <ip> <1818>
-./server 1818
-Code should execute from there!
-!!!! MAKE SURE WHEN TYPING IP ADDRESS FOR CLIENT EXECUTABLE, IT IS THE IP ADDRESS THAT THE SERVER IS ONE!!!




What I was able to do:
-Client asks user to input string
-Server listens for string and has a windowSize
-There is a nested for loop with an if statement that determines
whether one or two bytes is being sent
-Server outputs the total amount of bytes with the window
