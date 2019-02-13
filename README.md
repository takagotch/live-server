### live-server
---
https://github.com/tapio/live-server

```
npm install -g live-server

npm install 
npm install -g
```

```js
var liveServer = require("live-server");
var params = {
  port: 8181,
  host: "0.0.0.0",
  root: "/public",
  open: false,
  ignore: 'scss,my/templates',
  file: "index.html",
  wait: 1000,
  mount: [['/components', './node_modules']],
  logLevel: 2,
  middleware: [function(req, res, next) { next(); }]
};
liveServer.start(params);

var fs = require("fs");

var fs = require("fs");
module.exports = {
  cert: fs.readFileSync(__dirname + "/server.cert"),
  key: fs.readFileSync(__dirname + "/server.key"),
  passphrase: "12345"
};





```


