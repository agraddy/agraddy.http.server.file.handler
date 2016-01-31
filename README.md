# agraddy.http.server.file.handler

A simple file server handler.

MIT License

## Install

```npm install agraddy.http.server.file.handler```

Or the shortcut version:

```npm install ag-file-handler```

## Use

```
var file = require('agraddy.http.server.file.handler');
// Or the shortcut version
//var file = require('ag-file-handler');
var http = require('http');
var server;

server = http.createServer(file('location_of_file/example.htm'));

server.listen(8080);
```

## Todo

* Create an example directory with the above example (include step-by-step instructions from scratch and include assumptions).
* Explain how the test is setup

