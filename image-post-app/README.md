# Setup

## Server setup
1. Make server files directory by `mkdir {server-folder-name}`
1. Change directory by `cd {server-folder-name}`
1. Import modules
    - If package.json already exists, then `npm install`
    - If not, then `npm init -y` and `npm install {module-name}`
1. Create index.js like following
    ```js
    const express = require('express');
    const app = express()

    app.get('/', function(req, res){
        res.send('Hello World');
    });

    app.listen(3000);
    ```
1. Start server by `node .`

## Front-end setup
1. Create HTML/CSS/JS files to generate a web page