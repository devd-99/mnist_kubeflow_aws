# web-ui

- flask_server.py
  - main server code. Handles incoming requests, and renders HTML from template
- mnist_client.py
  - code to interact with TensorFlow model server
  - takes in an image and server details, and returns the server's response
- Dockerfile
  - builds a runnable container out of the files in this directory

