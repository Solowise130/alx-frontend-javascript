ES6 Promises

The Promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting value.
To learn about the way promises work and how you can use them, read   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

Learning Objectives
•	Promises (how, why, and what)
•	
•	How to use the then, resolve, catch methods
•	
•	How to use every method of the Promise object
•	
•	Throw / Try
•	
•	The await operator
•	
•	How to use an async function

Resources📚
Read or watch:

Promise
JavaScript Promise: An introduction
Await
Async
Throw / Try

Requirements🔨
Ubuntu 18.04 LTS using NodeJS 12.22.x
Jest Testing Framework
ESLint

Install NodeJS 12.22.x
foo@pop-os:~$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
foo@pop-os:~$ sudo bash nodesource_setup.sh
foo@pop-os:~$ sudo apt install nodejs -y

Check version
foo@pop-os:~$ nodejs -v
v12.22.1
foo@pop-os:~$ npm -v
6.14.12

Install Jest, Babel, and ESLint
foo@pop-os:~$ npm install --save-dev jest
foo@pop-os:~$ npm install --save-dev babel-jest @babel/core @babel/preset-env
foo@pop-os:~$ npm install --save-dev eslint

Tasks

Below are the files created and their expected outputs;

0-promise.js --- Returns a Promise using this prototype function getResponseFromAPI().

1-promise.js --- Uses the prototype getFullResponseFromAPI(success) to return a promise. The parameter is a boolean.

2-then.js --- Uses the prototype function handleResponseFromAPI(promise)


