# Web Engineering 2015-2016 / Microservices
Please, go to the [Wiki](https://github.com/UNIZAR-30246-WebEngineering/lab6-microservices/wiki) in order to get the instructions for this assignment.

#Eureka's fail-over demo

Node boot order:

- *registration:1111*
- *accountA:2222*
- *web:3333*
- *accountB:4444*

In order to change the port. The fastest way is by editing **application.yml**

It should look like this:

![Screenshot](/Capture.png)

Now if you kill the process accountA you'll see how eureka redirects traffic to AccountB.