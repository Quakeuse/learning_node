# Learning Node.js + Express

To check if Node is installed on my computer, run **npm -v** in a terminal

From a GitHub project, use the command **npm install** to install the dependencies

The command **npm run start** let to start the Node server. The associated website can be displayed with the address given

To init a new backend project, run **npm init** in a terminal. There will be several parameters to set up, most of them can remain as they are proposed. Potentially change the "index.js" with "server.js".

To start the Node server, run **node server**
To stop the server, press Control+C

As long as the server is running, any modification in the code won't be taken in account. A restart of the server is required to apply the last modifications. To prevent the manual stop+start, use **nodemon** instead. This will listen the modifications and automatically restart if needed.

**npm install -g nodemon** then launch the server **nodemon server**

## What is Node?

The runtime Node let to execute javascript code on a backend server.

## What is Express?

Express is the most popular Node.js web framework. See the documentation https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Express_Nodejs/Introduction

To install Express : **npm install express --save** (--save is to save the configuration in the package.json)

*"dependencies": {
    "express": "^5.1.0"
  }*

### What is a Middleware?

Middleware in Node.js refers to a concept where functions can be used to process incoming requests before they reach their final destination and handle outgoing responses before they are sent back to the client
