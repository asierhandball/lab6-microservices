# Web Engineering 2015-2016 / Microservices
Task 1: Two MicroServices running:
![task1] (/images/task1.png)
Task 2: Service Registration has two microservices registered:
![task2a] (/images/task3a.png)
![task2b] (/images/task3b.png)
Task 3: Additional Account microservice running in port 4444:
![task3] (/images/task4.png)
Task 4: Killing microservice with port 2222:
![task3] (/images/task5.png)
The service keeps working a bit time because the system is correctly set up and the web service config is searching for an application that is registered in the service with the name: ACCOUNTS-SERVICE, so when we registered the new account microservice with port 4444, it can receive petitions from the web microservice.
