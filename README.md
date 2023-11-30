# Simple HTTP Server in Python

This is a basic example demonstrating how to create a simple HTTP server in Python using the `http.server` library. In this example, the server listens on port 8080 and responds to any request with the body "Hello, World!".

## How to Use

Make sure you have Python installed on your system. You can run the script as follows:

```bash
python http_server.py

### Script Details
The script utilizes the http.server library and defines a class named HelloHandler, which inherits from BaseHTTPRequestHandler. The do_GET method is overridden to send an HTTP response with the body "Hello, World!".
