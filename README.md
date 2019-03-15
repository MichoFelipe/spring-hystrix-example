# Spring Hystrix Example
This project use Hystrix and Spring Data REST Example. Here, we can see two responses where Hystrix help us to Fault Tolerant. 

## Description
This Project shows the list of Users which are stored in another microservice `https://spring-data-rest-jpa-example/users/all`. 
Now, let's consume that service using spring-hystrix-example with the following endpoints:
- `/rest/users` - This returns the list of Users from another microservice(General)
- `/rest/users/hystrix` - This returns the list of Users and safegaurded by Spring Cloud Hystrix using Fallback implementation.

