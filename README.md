# Single-Client-Server

Below are some points to note:

      * Here Server application simply makes a server socket on a port 5000. This starts our server listening to the request which is sent by the client for port 5000.
      * After this server makes a new socket to communicate with the client.
      * You can simply see we used the client.accept() method and accept() method blocks until our client connects to the server.
      * We simply sent the message from the client-side and the server simply displays that message.
      * When we sent Done then it simply closes the connection and socket.
      
If you are using IntelliJ Idea, Eclipse, or some other IDE then you need to follow the below steps for running these programs:

      * Compile SeverSideProgram.java and ClientSideProgram.java on two different tabs or terminals.
      * Run your SeverSideProgram first and then run ClientSideProgram.
      * Type messages in the ClientSideProgram and that message will be displayed simultaneously in the ServerSideProgram window.
      * For stopping and closing, the connection enters Done.
      
      
