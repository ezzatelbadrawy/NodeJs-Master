# Assignment 1

It's a simple RESTful API Node.js application with single rout '/hello'. 

It return this JSON object on '/hello' route:
{
    "name": "Hello World From My First RESTful API !!"
}
With status code 200

Else it return empty JSON object ({}) with status code 406 (Not-Found). 


This web-app support HTTP on these configured ports:
1- Port 333 for staging environmet
2- Port 444 for production environment

Also it support HTTPs on these configured ports:
1- Port 666 for staging environmet
2- Port 777 for production environment
