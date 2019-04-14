```js
// style
/*style*/
```



var myName ;

var a = 7;
var b = 7;
var b = a;

var a = 9;

var a = 5;
var b = 10;
var c = "I am a";
a = 6;
b = 15;
c = "I am a String!"

var studlyCapVar ;
var properCamelCase ;
var titleCaseOver ;
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;

var sum = 10 + 10;

var difference = 45 - 33;

var product = 8 * 10;

var quotient = 66 / 33;

 myVar++;
 
 myVar--;
 
 var myDecimal = 5.7;
 
 var product = 2.0 * 2.5;
 
 var quotient = 4.4 / 2.0; // Fix this line
 
 var remainder = 11 % 3;
 
 a += 12;
b += 9;
c += 7;

a -= 6;
b -= 15;
c -= 1;

a *= 5;
b *= 3;
c *= 10;

a /= 12;
b /= 4;
c /= 11;

var myFirstName = "berry";
var myLastName = "kiflit" ;

"I am a \"double quoted\" string inside \"double quotes\".";

var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';

var myStr="FirstLine\n\t\\SecondLine\nThirdLine"; 

var myStr = "This is the start. " + "This is the end.";

var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";

var myName = "bereketAsmeromKiflit";
var myStr = "My name is " + myName + "and I am well";

var someAdjective = "mindWork!";
var myStr = "Learning to code is ";
myStr += someAdjective;

lastNameLength = lastName.length;

firstLetterOfLastName = lastName[0];

myStr = "Hello World"; // Fix Me

var thirdLetterOfLastName = lastName[2];

var lastLetterOfLastName = lastName[lastName.length - 1];

var secondToLastLetterOfLastName = lastName[lastName.length - 2];

return result+= "My "+myAdjective+" "+myNoun+" "+myVerb+" very "+myAdverb+".";  Basic JavaScript: Word Blanks

 var myArray = ["berry", 27]; Basic JavaScript: Store Multiple Values in one Variable using JavaScript Arrays

var myArray = [["berry", 27], ["hani", 21]]; Basic JavaScript: Nest one Array within Another Array

var myData = myArray[0]; // equals 50 Basic JavaScript: Access Array Data with Indexes

var myArray = [45,64,99];
myArray[0] = 45; // myArray now equels [45,64,99]  Basic JavaScript: Modify Array Data With Indexes

var myData = myArray[2][1];  Basic JavaScript: Access Multi-Dimensional Arrays With Indexes

myArray.push(['dog', 3]);  Basic JavaScript: Manipulate Arrays With push()

var removedFromMyArray = myArray.pop();  Basic JavaScript: Manipulate Arrays With pop()

var removedFromMyArray = myArray.shift();  Basic JavaScript: Manipulate Arrays With shift()

myArray.unshift(["Paul", 35]);  Basic JavaScript: Manipulate Arrays With unshift()

var myList = [["Banana", 3], ["Apple", 4], ["Orange", 5], ["Peach", 6], ["Pineaple", 7]];  Basic JavaScript: Shopping List

function reusableFunction() {
    console.log("Hi World");
}

reusableFunction();              Basic JavaScript: Write Reusable JavaScript with Functions

function functionWithArgs(a, b) {
  console.log(a + b);
}
functionWithArgs(1, 2); // Outputs 3
functionWithArgs(7, 9); // Outputs 16  Basic JavaScript: Passing Values to Functions with Arguments

// Declare your variable here
var myGlobal = 10;

function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal = 5;                   Basic JavaScript: Global Scope and Functions
}

function myLocalScope() {
     'use strict';

  var myVar = "Hello";

  console.log(myVar);
}
myLocalScope();             Basic JavaScript: Local Scope and Functions

var outerWear = "sweater";  Basic JavaScript: Global vs. Local Scope in Functions

function timesFive(num) {
  return num * 5;
}

var answer = timesFive(5);   Basic JavaScript: Return a Value from a Function with Return

function addFive() {
  sum = sum + 5;             Basic JavaScript: Understanding Undefined Value returned from a Function
  }                     

processed = processArg(7);    Basic JavaScript: Assignment with a Returned Value

function nextInLine(arr, item) {
  // Your code here

  var queue = arr.push(item);

  var removeItem = arr.shift();

  return removeItem;  // Change this line
}

// Test Setup
var testArr = [1,2,3,4,5];

// Display Code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6)); // Modify this line to test
console.log("After: " + JSON.stringify(testArr));                     Basic JavaScript: Stand in Line

function welcomeToBooleans() {

// Only change code below this line.

return true; // Change this line

// Only change code above this line.
}                                           Basic JavaScript: Understanding Boolean Values

if(wasThatTrue) return "Yes, that was true";

  return "No, that was false";                 Basic JavaScript: Use Conditional Logic with If Statements     
  
 // Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testEqual(10);                                     Basic JavaScript: Comparison with the Equality Operator

// Setup
function testStrict(val) {
  if (val === 7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict(10);                          Basic JavaScript: Comparison with the Strict Equality Operator

// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
compareEquality(10, "10");                Basic JavaScript: Practice comparing different values

// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line

  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}                                        Basic JavaScript: Comparison with the Inequality Operator

// Change this value to test
testStrictNotEqual(10);                     

// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";                       Basic JavaScript: Practice comparing different values
}

// Change this value to test
compareEquality(10, "10");



  
  










