# myfirst.js

```js
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/html'});
  res.end('Hello World!');
}).listen(8080);
```

## Command Line Interface

> Node.js files must be initiated in the "Command Line Interface" program of your computer.

> How to open the command line interface on your computer depends on the operating system. For Windows users, press the start button and look for "Command Prompt", or simply write "cmd" in the search field.

> Navigate to the folder that contains the file "myfirst.js", the command line interface window should look something like this:

```
C:\Users\Your Name>_
```

# Initiate the Node.js file

> The file you have just created must be initiated by Node.js before any action can take place.

> Start your command line interface, write node myfirst.js and hit enter

Now, your computer works as a server!

If anyone tries to access your computer on port 8080, they will get a "Hello World!" message in return!

***Start your internet browser, and type in the address: http://localhost:8080***


<img src="img/3.png">

***노드는 서버를 구동하는 것이구낭***
***노드를 이용해서 내가 클라이언트가 접속하였을 때, 어떤 것을 내보일지를 써서 내고, 서버를 구동시켜서 내 포트로 접속했을 때 해당 내용을 보여주는 것이구낭***