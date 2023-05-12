# Roman-Service-System
A distibuted system used to provide users to domestic services

# C# Client
This is a GUI made using C# that allows users to add services and view the services in the database as well as authenticate into the system. It works by making a request to the server through the use of remoting.
![client1](https://github.com/Haxor44/Roman-Service-System/assets/50330948/32b72f22-b739-4f4e-9180-c081f83d8d37)<br/>
![client2](https://github.com/Haxor44/Roman-Service-System/assets/50330948/39053fee-1971-4d39-822c-e537216495e7)

# C# Server
This is a GUI made using C# that provides a remotable object to the C# client. It enables the client to be able to perform basic crud operations on the database such as adding users, services and authentication.
![server](https://github.com/Haxor44/Roman-Service-System/assets/50330948/b0afe685-0198-4765-a58b-32d3fb47f881)

# Java desktop Application
This application is an interface for developers to be able to view data collected as well as keep record of their tasks.

# Rest-Apis
The rest-apis used provide data to the frontend and enable a user to be able:
1. Authenticate<br/>
2. View data<br/>
3. Checkout functionality(coming soon)
4. Payment (coming soon)

The apis were made using java spring-boot and were deployed and hosted on the following links.<br/>
1. https://roman-webservice.onrender.com/api/v1/services
2. https://service-api-0nnq.onrender.com/api/v2/services
<br/>
The code for the two apis can be found at the following github pages respectively.
1. https://github.com/Haxor44/Views-webservice
2. https://github.com/Haxor44/Services-Api

# React Frontend
This provides users with an interface to be able to interact with the apis.<br/>
![front](https://github.com/Haxor44/Roman-Service-System/assets/50330948/6131ed63-1ff2-4710-9fa5-37fb6a90ae82)
