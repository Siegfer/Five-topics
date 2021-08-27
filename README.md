# Five-topics

### number 1

how to import a module

``` javascript
const http = require("http"); // import http module
```

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

### 3

importants of .gitignore

``` javascript
inside .gitignore usually contain node_modules/
```

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

### 6

XOR was stupid................................
``` sql
SELECT name, population, area
FROM world
WHERE (area > 3000000 AND population <=250000000)
OR (area <= 3000000 AND population > 250000000)
```