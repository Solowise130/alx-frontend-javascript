 ES6 Basics

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

What ES6 is

New features introduced in ES6

The difference between a constant and a variable

Block-scoped variables

Arrow functions and function parameters default to them

Rest and spread function parameters

String templating in ES6

Object creation and their properties in ES6

Iterators and for-of loops

Resources


ECMAScript 6 - ECMAScript 2015

Statements and declarations

Arrow functions

Default parameters

Rest parameter

Javascript ES6 — Iterables and Iterators

Below were the files created and their expected outputs;

0-constants.js --- Modifies the functions "taskNext" and "taskFirst" to instantiate variables using "let" and "const" respectively.

1-block-scoped.js --- Modifies the variables inside the function "taskBlock" so that the variables aren’t overwritten inside the conditional block.

2-arrow.js --- Rewrites a given standard function to use ES6’s arrow syntax of the function "add".

3-default-parameter.js --- Condense the internals of a  given function to 1 line - without changing the name of each function/variable.

4-rest-parameter.js --- Modifies a given function to return the number of arguments passed to it using the rest parameter syntax.

5-spread-operator.js --- Uses spread syntax to concatenate 2 arrays and each character of a string by modifying a given function.

6-string-interpolation.js --- Rewrites the return statement to use a template literal so I can substitute the variables defined.

7-getBudgetObject.js --- Modifies the a given function’s budget object to simply use the keyname instead.

8-getBudgetCurrentYear.js --- Rewrites the "getBudgetForCurrentYear" function to use ES6 computed property names on the budget object.

9-getFullBudget.js --- Rewrites "getFullBudgetObject" to use ES6 method properties in the fullBudget object.

10-loops.js --- Rewrites the function "appendToEachArrayValue" to use ES6’s for...of operator.

11-createEmployeesObject.js --- Writes a function named createEmployeesObject that will receive two arguments:

-departmentName (String)

-employees (Array of Strings)

12-createReportObject.js --- Writes a function named "createReportObject" whose parameter "employeesList" is the return value of the previous function "createEmployeesObject".

100-createIteratorObject.js --- Writes a function named "createIteratorObject", that will take into argument a report Object created with the previous function "createReportObject".

This function will return an iterator to go through every employee in every department.

101-iterateThroughObject.js --- Writes a function named "iterateThroughObject". The function’s parameter "reportWithIterator" is the return value from "createIteratorObject".
