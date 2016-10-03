1. command: npm init
2. add new file: .gitignore
3. open ".gitignore" and add "node_modules"
4. command: git init
5. command: npm install express --save
6. create new file: server.js
7. Add code below to "server.js": (source: http://expressjs.com/en/starter/hello-world.html)
var express = require('express');
var app = express();

app.get('/', function (req, res) {
  res.send('Hello World!');
});

app.listen(3000, function () {
  console.log('Example app listening on port 3000!');
});
8. run: node server.js
9. commit to git:
    git status
    git add .
    git commit "initial commit"
    git remote add origin https://github.com/fybwid/Timestamp-Microservice.git
    git push origin master
    