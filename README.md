# CommunicationProgramming
Five projects. They were made for a last-year degree subject. Read the README.md for more info. 

- Every project has his own code and documentation of everything. 
- Although each project (1-4) belongs to the final project (5), you can execute the first 4 independently.
- This document is written in spanish.
- JAVA

Anyway, I'm going to write a short summary:

* Project 1 (ClientServerHTTP): Creation of a Client-Server application using HTTP protocol. The server answers with the same text the client has given. It's called "echo-service". TCP sockets.

* Project 2 (ServersWithUDP): Now we have two servers. They send via broadcast constantly their information and the client listen it. The information simulates the obtaining of weather forecast (temperature, humidity, pressure, wind speed...). The client can communicate with the servers and change some weather units. Now we use UDP instead of TCP.

* Project 3 (XMLandJSON): Now we add to the servers the functionality of parsing XML and JSON files. The messages of our application are using those markup languages. We created two parsers.

* Project 4 (SSLsupport): SSL protocol implementation. Now we can access to our servers using https://localhost, for example, in a browser. The creation of some keystores, certificates and this stuff was necessary. Is important to import them in our system/browser before trying the access, otherwise it will say that it's not a safe site and SSL won't create the secured communication.

* Project 5 (FinalApp): Now the old client is the center of the application and it's the server we access now. From a browser, like Safari, we have 3 ways of obtain the weather forecast. Using HTTP, HTTPS or email. We created a MailServer in the project, which sends the weather forecast via mail. JavaMail was the chosen tool. 

I hope you enjoy this project as much as I did creating it. It displays random weather information, because that's not the objective of the program. The real objective is to learn / applicate the protocols. 


