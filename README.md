# Basic OpenSocial Gadgets In XML, HTML, CSS, and JS

This is an example project for creating opensocial gadgets written in XML, HTML, CSS and JS.

## Steps 
First install the necessary dependencies, this may take a few minutes.
```
npm install
```

Start the HTTP Server
This project uses the http-server to run a basic HTTP server to serve all files in the public directory. It is not meant for production, but rather just for development and testing.
The following command starts the server and uses port 3000 (default port is 8080).
```
http-server -p 3000
```
You can now access the gadget from http://localhost:3000

## Adding to an Open Social Container (dashboard)
To add this gadget to an open social container, specify the URL to the gadget specs, e.g.
http://localhost:3000/basicopensocial.xml
or
http://localhost:3000/basicopensocial2.xml

