# back-end-task
What is HTTP?
HTTP (HyperText Transfer Protocol) is the foundational protocol used by the web for communication between clients (like browsers) and servers. It’s a stateless request-response protocol, meaning each interaction is independent.

-HTTP Request
An HTTP request is what a client (like a browser) sends to a server to ask for a resource, such as a webpage, image, or data.

Structure of an HTTP Request:
-Request Line:

METHOD /resource HTTP/version
Example:

GET /index.html HTTP/1.1
-Request Headers:
Key-value pairs that provide meta-information about the request.

-Empty Line:
Separates headers from the body.

-Request Body (optional):
Used mainly with methods like POST or PUT to send data.


- HTTP Response
An HTTP response is what the server sends back to the client after processing the request.

Structure of an HTTP Response:
-Status Line:

Example:

HTTP/1.1 200 OK
-Response Headers:
Provide information about the response and server.

-Empty Line

-Response Body:
The actual content (HTML page, image, JSON, etc.)

- HTTP Methods
Method	Description
GET	Retrieve data from the server (no body).
POST	Submit data to be processed (has body).
PUT	Replace a resource or create it if it doesn’t exist.
DELETE	Delete a resource.
PATCH	Partially update a resource.
HEAD	Same as GET but returns only headers.
OPTIONS	Returns supported methods for a resource.

- HTTP Headers
Common Request Headers:
Host: The domain name (required in HTTP/1.1).

User-Agent: Info about the client software.

Accept: Preferred response media types.

Authorization: Credentials for authentication.

Common Response Headers:
Content-Type: The type of data sent (HTML, JSON, etc.).

Set-Cookie: Set cookies in the client.

Cache-Control: Caching policies.

Location: Used for redirects.

 HTTP Status Codes
Code	Meaning	Example Use
100	Informational	100 Continue – Client should continue with request.
2xx	Success	200 OK, 201 Created
3xx	Redirection	301 Moved Permanently, 302 Found
4xx	Client Errors	400 Bad Request, 401 Unauthorized, 404 Not Found
5xx	Server Errors	500 Internal Server Error, 503 Service Unavailable
--------------------------------------------------------------------------------------------------------
What is an API?
An API (Application Programming Interface) allows different software systems to communicate. It defines how requests and responses should be structured. APIs enable modular design, reusability, and integrations between applications.

- What is a REST API?
A REST API (Representational State Transfer) is a style of web API design that uses standard HTTP methods and principles.

REST (Representational State Transfer) is an architectural style — not a protocol or language — for designing networked APIs, particularly web APIs. It defines a set of principles and constraints for how clients and servers should communicate over HTTP.


REST Core Concepts:
Resources: Everything is treated as a resource, identified by URLs.

HTTP Methods:

GET – Read

POST – Create

PUT – Update

DELETE – Remove

Stateless: Every request contains all the info needed; no session is stored on the server.

JSON Format: Commonly used for data transfer.

Status Codes: Uses standard HTTP codes (200, 404, 500, etc.)



 Why APIs Matter:
Enable communication between software components.

Allow independent development of frontend & backend.

Support integrations with third-party services (e.g., Stripe, Google Maps).

Promote scalability, modularity, and code reuse.


------------------------------------------------------------------------
Client-Server Architecture is a model in which two separate systems (client and server) communicate over a network:

Client: Requests services or resources.

Server: Provides those services or resources.

This design divides responsibilities between the client and the server.

- How It Works
The client ( browser, mobile app) sends a request .

The server processes the request, accesses the database if needed, and sends back a response.

The client receives the response and updates the UI accordingly.

* Real-World Examples
You open a website:

Your browser (client) sends a request to the website’s server.

The server responds with HTML, CSS, and JS files.

Your browser displays the page.

Benefits of Client-Server Model
Separation of concerns: UI vs. data/business logic

Scalability: Many clients can connect to one server

Security: Servers manage authentication, validation, ...

Maintainability: Easier to update or replace frontend/backend separately







أنت قلت:
