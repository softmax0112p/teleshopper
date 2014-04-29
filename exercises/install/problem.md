Create a new project directory initialise it and install telehash

----------------------------------------------------------------------

## HINTS

```sh
$ mkdir yourprojname
$ cd yourprojname
$ npm init
```

Now install Telehash it is available on npm. 

```sh 
$ npm install telehash --save
```

Now create a simple telehash program that initialises telehash and prints "WOW SERVERLESS"

```js
var th = require("telehash");
th.init({}, function(err, self){
  if(err) return console.log("hashname generation/startup failed",err);
  console.log("WOW SERVERLESS");
});
```

When you are done, you must run:

```sh
$ {appname} verify myprogram.js
```

to proceed. Your program will be tested, a report will be generated, and the lesson will be marked 'completed' if you are successful.

----------------------------------------------------------------------
