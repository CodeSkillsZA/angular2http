# Angular 2 starter project: HTTP

# Instructions to run the project
The "index.html" page won't run off the file system as it accesses an external HTTP address.  The easiest way to run the project is to install live-server.
npm install -g live-server
Then to run the project:
live-server

# Some areas of importance:
 - be sure to import the HTTP library into your HTML page (https://code.angularjs.org/2.0.0-alpha.44/http.dev.js)
 - the HTTP service needs to be injected into the class, but also stored in a local variable for later use
 - because TypeScript allows for much greater control over types compared to JavaScript, it's NB to leverage off this as much as possible
