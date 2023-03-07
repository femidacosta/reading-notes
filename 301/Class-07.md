<h1>How to make an API</h1>

run these commands;

```
cd into projects
npx create-react-app
cd into folder
code .
make new folder in VS code- server
open VScode terminal
cd into server
npm init -y
```

package.json file has been created into server

run in terminal;

`npm i express cors dotenv nodemon axios``

** purpose of this command;
installed dependencies to make a server. into the package.json within the server folder.
open package.json, close without saving, re-open to see dependencies.**

where it says main : index.js - change to server.js
save.

Back in the terminal run;

````
 ➜ server touch server.js
➜  server touch .env
➜  server touch .gitignore```
````

//Lets create API
`"use strict";`

//importing the dotenv pakge + running the config method
`require("dotenv").config();`

// import express and setting vraiable
`const express = require("express");`

// your server, and someone eles, by default they cannot commnuicate due to security.
//cors is a bridge - to communicate between servers.

`const cors = require("cors"); `

//instanciating (creating an instance of ) your instance of express setting app to the return value
`const app = express();`

//telling our express instance to use the cors bridge
`app.use(cors());`

//set the port number for the server
`const PORT = process.env.PORT || 8080;`

//
`` app.listen(PORT, () => console.log(`Server is running on port ${PORT}`)); ``

terminal
run
➜ server node server
Server is running on port 8080

this has effectively run a server, but on computer and its been logged in terminal.
`cmd c`
in terminal to clear
run
`nodemon server` - will run t

npm i -g nodemon
package needs nodemon and also the computer needs to know its installing nodemon (installing globally)

run;

````
nodemon server```

everytime file saves , it will restart the server

Note:
=>{}
this is a callback function
````
