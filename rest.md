# Rest Architecture

## What is Rest?
REST is an acronym for Representational State Transfer. It is an architectural style used for designing network-based applications,
especially web services. It defines a set of rules and constraints that allow systems to communicate over the internet in a simple, scalable, and lightweight way.
During the development phase, API developers can implement REST in a variety of ways.

## How REST Works
A client sends a request to a server using a URL.  
The request uses an HTTP method to specify the type of action.  
The server sends back a response that contains a resource.  
REST uses a clean and structured way to access and manage data.

## Common HTTP Methods in REST
REST uses standard HTTP methods. Each method tells the server what type of action is needed.

* **GET** — Read a resource  
* **POST** — Create a new resource  
* **PUT** — Replace a full resource  
* **PATCH** — Update part of a resource  
* **DELETE** — Remove a resource  

Other methods like OPTIONS and HEAD exist but are less commonly used.

## Difference Between PUT and PATCH
PUT replaces the entire resource.  
PATCH updates only specific fields.  
PUT is idempotent, while PATCH may not always be idempotent.

## Architectural Properties
REST is based on the idea that everything is a resource, and each resource is identified by a unique URI (Uniform Resource Identifier). 
The client interacts with the server by sending HTTP requests, and the server returns a representation of the resource (usually in JSON or XML format).

## Key Features of REST Architecture

### Stateless
The server does not store session data.  
Each request must include all required information.

### Client-Server Model
The client and server are independent.  
This makes scaling easy and keeps the system flexible.

### Cacheable
Server responses can be marked as cacheable.  
This improves speed and reduces server load.

### Uniform Interface
REST follows a consistent structure using clear URLs and standard methods.  
This makes communication smooth and predictable.

### Layered System
REST can use multiple layers such as gateways or load balancers.  
Each layer works independently, improving security and scalability.

## Real-World Use of REST APIs
REST APIs are used in many areas today, including:

* Social media platforms  
* E-commerce systems  
* Location and GPS services  
* Weather information services  

REST is simple, reliable, and widely used across the world.

# References
* https://www.geeksforgeeks.org/rest-api-introduction/
* https://restfulapi.net/
