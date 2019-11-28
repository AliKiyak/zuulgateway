# Zuul gateway
The Zuul gateway is a load balancer that connects to our edge service. The Eureka Server is an application that holds the information about all client-service applications. Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery Server.

## Context
The Esports wiki allows you to find every bit of information about the games, teams, tournaments and players that are involved in Espors. You can look at them in detail, add, delete or even edit them. This way you can keep your own database about your favorite esports game / team.

## Installation
* Clone our project (git clone https://github.com/AliKiyak/zuulgateway.git)

## Usage
Run the project and make sure that the Eureka Server, Edge service and the other microservices are all running.
The functionality of the service can be tested while it is isolated from the other services.

## Client
This is a school project made for the course Java Advanced Topipcs

## Authors and acknowledgment
* Ali Kiyak (AliKiyak)
* Bosz Srisan (BoszS)
* René Vanhoof (VanhoofR)
* Chris Tophe (Christophe195)
