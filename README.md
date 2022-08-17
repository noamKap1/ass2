# ass2
# Implementation:

We created a class called "Socket" which acts like an interface from java,thats for making the code more polymorphic as requested.
afterwards we created 2 classes that implement the class "Socket": Client, Server.

# Client:

our program creates a client. 
Then, the unclassified data is sent to the server by the socket. The client after the server is done classifing receives the calculated types and writes them into a csv file which we named "result.csv".

# Server:
our program creates a server. 
Then, the server waits for a client, when the client connects the servers gets his needed data as a string of indices separated by spaces and new lines. The server creates an Iris for each set of indices, classifies it using the Classifier class from ass1 and returns the types.

# Running:
(we used the program MobaXterm)
do and write the commands or actions in this order:
open to frames of the program.
write in one of them: mkdir folderName
write in both of them: cd folderName
download the files and copy it to the program inside the folder named folderName.
in one of the frames write: cd server
in the second one write: cd client
in the frame which we written cd server we compile using the command "g++ *.cpp -std=c++11" and then run with the command:./a.out"
now in the second frame we compile using the command "g++ *.cpp -std=c++11" and then run with the command:./a.out "Unclassified.csv" "result.csv"


