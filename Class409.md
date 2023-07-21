# Review: High-level HTTP

### What are the five steps in the HTTP Request Lifecycle?

Resolve: Client resolves server's IP address.
Connect: Client establishes TCP connection.
Send: Client sends HTTP request.
Process: Server processes request and generates response.
Receive: Server sends HTTP response to client.

## What are the two things the client needs before it can make an HTTP Request?

The client needs the server's address/URL and the appropriate HTTP request method before making an HTTP request.

## Explain the four way handshake and what it does.

The four-way handshake is a method used by devices to establish and terminate a connection, ensuring smooth and reliable data transfer.

# Java HTTP Request example

### True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.

True. Redirects in HTTP requests should be followed to ensure proper navigation and access to the requested resource.

### Which built-in Java class can be used to perform an HTTP request?

java.net.HttpURLConnection.

### What HTTP status codes represent a successful response? A redirect? A client error?

Successful response: HTTP status codes 200 to 299.
Redirect: HTTP status codes 300 to 399.
Client error: HTTP status codes 400 to 499.

References:

https://dev.to/dangolant/things-i-brushed-up-on-this-week-the-http-request-lifecycle-

https://www.baeldung.com/java-http-request






