# mocha-sample-testing
Sample Mocha Testing

npm install mocha --save
npm install chai --save
npm install request --save
npm install express --save

Note that we are using the --save option to automatically save these dependencies in our package.json file.

Change the test scripts to:

"scripts": {
    "test": "./node_modules/.bin/mocha --reporter spec"
  }
  
  
  
Package.json should look like this.

{
  "name": "converter",
  "version": "0.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "./node_modules/.bin/mocha --reporter spec"
  },
  "author": "",
  "license": "ISC"
}


To run tests:
1. In one CMD/Powershell, run the server from the app folder. (node app/server.js)
2. Open 2nd cmd/powershell, run the npm test. 

If you have troubles, please go through the following link,
https://semaphoreci.com/community/tutorials/getting-started-with-node-js-and-mocha
