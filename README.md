# helper-memory-javascript

## Helper files if memory fails
- translate jQuery to vanilla Javascript
- promise ES2015
- test ES2015 with Mocha and Chai
- webpack init config
- codeceptsjs acceptance tests

# Start helper project :

`npm i`

## Commands dev webpack build and watch from entry.js
`npm start`

## Unit tests with Mocha + Chai
`npm test`

## Acceptance tests

### Requirements in /acceptance-test-server

- driver Chrome http://bit.ly/2cC3PKp
- java JDK v8 http://bit.ly/2cC2qn8

### Commands
in /acceptance-test-server

`java -jar selenium-server-standalone-2.45.0.jar`

in /

`node server.js`

`codeceptjs run`
