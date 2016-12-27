# Web Engineering 2016-2017 (UNIZAR)
##1- The two microservices are running and are registered.
####Account Service running
![Account Service](https://github.com/Belberus/lab6-microservices/tree/test/images/AccountServerTerminal.png)
![Account Service](https://github.com/Belberus/lab6-microservices/tree/test/images/AccountServerLaunched.png)
####Web Service running
![Web Service](https://github.com/Belberus/lab6-microservices/tree/test/images/WebServerTerminal.png)
![Web Service](https://github.com/Belberus/lab6-microservices/tree/test/images/WebServerLaunched.png)
##2- The registration service has the two microservices registered.
####The two microservices are registered
![Registration Service](https://github.com/Belberus/lab6-microservices/tree/test/images/ServicesRegistered.png)
##3- A second account microservice is running in the port 4444 and it is registered.
###Account Service number 2 running
![Account Service 2](https://github.com/Belberus/lab6-microservices/tree/test/images/AccountServer2Terminal.png)
![Account Service 2](https://github.com/Belberus/lab6-microservices/tree/test/images/AccountServer2Launched.png)
###Account Service number 2 registered
![Registration Service updated](https://github.com/Belberus/lab6-microservices/tree/test/images/RegistrationUpdated.png)
##4- What happens when microservice in port 2222 is killed:
<div class="alig-justify">
When the Web server in port 3333 attemps to connect with the microservice in port 2222, it is answered with an error message of connection refused. So when it tries to connect again it asks to the Eureka Registration Server for the Account Service's address and then it gets the right port, in this case the active one, 4444.
</div>


