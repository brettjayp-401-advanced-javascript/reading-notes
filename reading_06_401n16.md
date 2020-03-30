# Reading 05
## 401n16


## Discussion
### 1. What does protocol mean?
- A set of rules.

### 2. How does any web browser understand how to open any webpage?
- By following HTTP protocol, it is given a response with instructions it will understand.

### 3. Name one thing a request object must have, and one thing a response object must have
- Method (and URL/endpoint, and headers)
- Body (and status code)

### 4. What is the difference between HTTP and REST?
- HTTP is the protocol governing data transmission across the internet, while REST is a guideling governing the format of a server's API's that travel through HTTP requests.

### 5. Why is REST important?
- REST is important because we need rules.



## Vocabulary
* **Server**
- Any application/host responsible for responding to a request.
* **HTTP**
- Hyper Text Transfer Protocol
- How data is shared over the internet
- How your web browser loads websites onto the screen
- As a protocol, is a set of rules governing how requests and responses should be structured in the WRRC
- Methods are: GET POST PUT DELETE HEAD CONNECT OPTIONS TRACE PATCH
* **REST**
- Representational State Transfer
- Guidelines that "how to format a server’s APIs so that a client can access all the methods / functionality they need"
* **Request**
- Needs a method, url/endpoint, and headers
- Comes from a client to a server
- Commonly a request for data
* **Response**
- May or may not be the desired respose (could be error instead of data, or no response)
- Important parts of the response are body and status
* **Web Request Response Cycle (WRRC)**
- The pattern of requests and responses between clients and servers.
* **HTTP Status Codes**
- Numerical codes used in responses to indicate a server, data, or response status
* **Client**
- Any source application/host of a request for data for the end user.
* **Application Programming Interface (API)**
- "...a collection of commands that let external applications interact with your application"
- In most contexts, this refers to a web based API
- Almost all hardware and programs also have an API
* **Swagger**
- A service for automated dynamically generated API documentation
* **REST Endpoint**
- URL endpoint in REST application where data is stored, is the destination for operations (such as CRUD operations)









[Return to Home](https://brettjayp-401-advanced-javascript.github.io/reading-notes/)
