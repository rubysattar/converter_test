# Independent practice using Mocha with Chai assertion library in JS
I started this repository in order to practice running asynchronous code and get into the habit of test-driven-development.

## Directions to follow along
1. clone this repo to your local computer
2. `cd` into the directory
2. run the Web API with `node app/server.js`
3. run `npm test`

## My set-up involved:
- run `npm install --save mocha chai` for the testing libraries
- run `npm install --save request` for the server
- run `npm install --save express` for the server requests
- run `npx mocha --reporter spec` for the reporting format in my terminal. *Note that you can also hard code `mocha --reporter spec` into your package.json as a value for 'test' in the 'scripts' object.