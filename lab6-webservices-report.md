# Web Engineering 2016-2017 (UNIZAR)
## 1- The two microservices are running and are registered.
#### Account Service running
![](images/AccountServerTerminal.png?raw=true)
![](images/AccountServerLaunched.png?raw=true)

#### Web Service running.

![Web Service 1](images/WebServerTerminal.png?raw=true)
![Web Service 2](images/WebServerLaunched.png?raw=true)
## 2- The registration service has the two microservices registered.
#### The two microservices are registered.
![Registration Service 1](images/ServicesRegistered.png?raw=true)
## 3- A second account microservice is running in the port 4444 and it is registered.
### Account Service number 2 running.
![Account Service 2 1](images/AccountServer2Terminal.png?raw=true)
![Account Service 2 2](images/AccountServer2Launched.png?raw=true)
### Account Service number 2 registered.
![Registration Service updated 1](images/RegistrationUpdated.png?raw=true)
## 4- What happens when microservice in port 2222 is killed:
<div class="alig-justify">
When the Web server in port 3333 attemps to connect with the microservice in port 2222, it is answered with an error message of connection refused. So when it tries to connect again it asks to the Eureka Registration Server for the Account Service's address and then it gets the right port, in this case the active one, 4444.
</div>


