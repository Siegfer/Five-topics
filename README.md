# Five-topics

### number 1

how to import a module

``` javascript
const http = require("http"); // import http module
```

there are 3 kinds of modules
Core Modules
these are built in 

Local Modules
these are made by you
```javascript
const beBasic = () => {
    return "That's so fetch";

};
```
Third Party Modules
these are downloaded and installed


### number 2

introduction to creating a server

``` javascript
http
  .createServer((req, res) => {
    res.write("Hello, SURF UPPPPPPPPP!!!");
    res.end();
  })
  .listen(8000);
```
you can also use the express module
```javascript
const express = require('express'); // importing express
const app = express(); // inovking and assigning express to app

const PORT = process.env.PORT || 8000; // establising a PORT

// Telling the port to listen
app.listen(PORT, () => {
    console.log(`Server running on PORT:`, PORT);
});
```


### 3

importants of .gitignore

``` javascript
inside .gitignore usually contain node_modules/
```
modules contain a lot of data that shouldn't be pushed to github - .gitignore allows you to use modules but not include them when you push to github

### 4

understanding what dependencies are

``` javascript
"dependencies": {
    "express": "^4.17.1"
  }
```

### 5
how to initialize a node.js project &
installing different modules

``` 
npm init -y
npm instal express
```
npm init without the -y allows you to set up each component manually 


### 6

XOR was stupid................................
``` sql
SELECT name, population, area
FROM world
WHERE (area > 3000000 AND population <=250000000)
OR (area <= 3000000 AND population > 250000000)
```

SQL
