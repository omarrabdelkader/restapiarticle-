# REST API (ARTICLE) 

## Introduction

I still recall the first time I have developed the first REACT front-end project. It was nine months ago. I'd given my friend, Safy, a call: "Safy, I have developed this project. However, I do need a REST API. Do you know any website, which provides a RESTful API, where I can fetch it? He replies, "Why don't you develop one?" I was so dumbfounded. I thought back-end was for geeks, and it was impossible. However, I've ended up being a back-end developer since then. In this article, I will be elaborating every aspect related to RESTful API.

------------

## Application Program Interface

APIs are mechanisms that enable two software components to communicate with each other using a set of definitions and protocols. API stands for Application Programming Interface. In the context of APIs, the word Application refers to any software with a distinct function. Interface can be thought of as a contract of service between two applications. This contract defines how the two communicate with each other using requests and responses.
(Amazon AWS)

Just visualize that we are in a restaurant. The kitchen is what we call the server, and the waiter is the API. The waiter, or the API is responsible to get orders from the restaurant's customers. (Web Application's clients)  

------------


## REST

REST stands for Representational State Transfer. REST defines a set of functions like GET, PUT, DELETE, etc. that clients can use to access server data. Clients and servers exchange data using HTTP.

The main feature of REST API is statelessness. Statelessness means that servers do not save client data between requests. Client requests to the server are similar to URLs you type in your browser to visit a website. The response from the server is plain data, without the typical graphical rendering of a web page.

(Amazon AWS)

Statelessness means that every HTTP request happens in complete isolation. Each request from the client to server must contain all the information needed to process that request and that information cannot be stored at the server side for any future reference. This restriction is called Statelessness.

(Geek for Geeks)

------------

What are the different types of APIs?
APIs are classified both according to their architecture and scope of use. We have already explored the main types of API architectures so let’s take a look at the scope of use.

Private APIs
These are internal to an enterprise and only used for connecting systems and data within the business.

Public APIs 
These are open to the public and may be used by anyone. There may or not be some authorization and cost associated with these types of APIs.

Partner APIs 
These are only accessible by authorized external developers to aid business-to-business partnerships.

Composite APIs 
These combine two or more different APIs to address complex system requirements or behaviors. 

------------


## HTTP Methods

As we have mentioned before, the server and the client do exchange data using HTTP methods.

HTTP Methods:

1) Get: Get data from a specific source
2) Put: Post data to a specific source
3) Post: Update data, using endpoint with the data's ID
4) Delete: Delete data, using endpoint with the data's ID

-----------

## Endpoints 

API endpoints are the final touchpoints in the API communication system. These include server URLs, services, and other specific digital locations from where information is sent and received between systems. API endpoints are critical to enterprises for two main reasons: 

1. Security
API endpoints make the system vulnerable to attack. API monitoring is crucial for preventing misuse.

2. Performance
API endpoints, especially high traffic ones, can cause bottlenecks and affect system performance.

Example:

GET https://www.restaurant.com/listdata => this is an endpoint in order to get the data

-------

## Conclusion

I've written this article, as a reason of boredom. 
