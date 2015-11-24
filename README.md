# What is DEVSimPy-ws
DEVSimPy-ws is a WebSocket server for DEVSimPy.
It allows a synchronous communication between the Python DEVSimPy models and a DEVSimPy-mob mobile application.

#Tech
DEVSimPy-ws server uses a number of open source projects to work properly:
* [Bottle](http://bottlepy.org/docs/dev/index.html) - a fast, simple and lightweight WSGI micro web-framework for Python.
* [Python](http://python.org)

#Installation
DEVSimPy-ws is a server solution which needs to be start by invoking the ws_server.py script.
```sh
$ python ws_server.py
```
All parameters used by the server are stored in a param.py file and they need to be filled:
- url_server : url of the host
- port_server : port of the host
