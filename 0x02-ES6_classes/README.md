ES6 Classes

Resources

https://intranet.alxswe.com/rltoken/IDo2mlwrId8srxeBNEjftw

https://intranet.alxswe.com/rltoken/CQS69TtR8objrRABVPVNZA


Learning Objectives

-How to define a Class

-How to add methods to a class

-Why and how to add a static method to a class

-How to extend a class from another

-Metaprogramming and symbols


Requirements

All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x

Allowed editors: vi, vim, emacs, Visual Studio Code

All your files should end with a new line

A README.md file, at the root of the folder of the project, is mandatory

Your code should use the js extension

Your code will be tested using Jest and the command npm run test

Your code will be verified against lint using ESLint

Your code needs to pass all the tests and lint. You can verify the entire project running npm run full-test


Setup

Install NodeJS 12.11.x
(in the home directory):

curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh

sudo bash nodesource_setup.sh

sudo apt install nodejs -y

$ nodejs -v
v12.11.1
$ npm -v
6.11.3

Files and Expected Functions

0-classroom.js --- Implements a class named "ClassRoom" that accepts one attribute named maxStudentsSize (Number) and assigned to _maxStudentsSize.

1-make_classrooms.js --- Imports  the ClassRoom class from 0-classroom.js. Implements a function named initializeRooms that returns an array of 3 ClassRoom objects with the sizes 19, 20, and 34 (in this order).

2-hbtn_course.js --- Implements a class named HolbertonCourse: Constructor attributes: name (String) length (Number) students (array of Strings).

3-currency.js --- Implements a class named Currency: 
- Constructor attributes:

o	code (String)

o	name (String)

•	Each attribute is stored in an “underscore” attribute version (ex: name is stored in _name)

•	Implements a method named displayFullCurrency that will return the attributes in the following format name (code).

4-pricing.js --- 
