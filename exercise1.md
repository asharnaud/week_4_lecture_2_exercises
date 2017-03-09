#Exercise 1 Answers

##1. List the five falsey values in JavaScript:
####False, 0, null, undefined, an empty string, and NaN.

##2. List five truthy values in JavaScript:
####Numbers other than 0, true, non-empty strings, objects, and the string "false".

##3. Take a look at the code example below and state what the variable sameAge will be set to and explain why.
var myAge = 33;
var yourAge = "33";

var sameAge = (myAge === yourAge) ? "Yes!" : "No!";

####It will be set to No! because 33 and "33" are different types if they were evaluated with == then it would be Yes!.
