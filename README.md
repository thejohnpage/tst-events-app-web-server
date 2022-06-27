# Events Web Server - Step 1
## Technology
* NodeJS version 16 or greater as the Web Server
* Express for RESTful Routes
* Morgan for Logging
* Mocha, Chai, NYC for Testing  

## Instructions
* Check the version of node with ` node -v`  
if it is less than 16 use nvm to install version 16  
You can check if you have nvm installed with `nvm -v`  if this returns the version of nvm  
you can then use  `nvm install 16`  
Then this command `nvm alias default 16`
If you don't have nvm installed I suggest that you install it because it is by far the easiest way to switch between version of NodeJS.  
* Run ` npm install ` to load the dependencies.  
* Now `npm start` will start the web server on `port 8080`  

## Starting Point  
Simple Web server interacting with simple API server that uses volatile storage. Data will be stored in an array on the API server.
