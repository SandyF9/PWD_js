# PWD_js

## JS HOME
<p> Dapat memunculkan tulisan ketika di tekan</p>
<html>
<body>
<h2>My First JavaScript</h2>
<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>
<p id="demo"></p>
</body>
</html> 

## JS Introduction
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

</body>
</html>

## JS Where To
<p>Hampir sama dengan Introduction</p>
<html>
<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
<body>

<h2>Demo JavaScript in Head</h2>

<p id="demo">A Paragraph.</p>

<button type="button" onclick="myFunction()">Try it</button>

</body>
</html>

## JS Output
<ul> 
  <li>Writing into an HTML element, using innerHTML or innerText.</li>
  <li>Writing into the HTML output using document.write().</li>
  <li>Writing into an alert box, using window.alert().</li>
  <li>Writing into the browser console, using console.log().</li>
</ul>
<h1>My Web Page</h1>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "<h2>Hello World</h2>";
</script>

</body>
</html> 

## JS Statements
<html>
<body>

<h2>JavaScript Statements</h2>

<p>A <b>JavaScript program</b> is a list of <b>statements</b> to be executed by a computer.</p>

<p id="demo"></p>

<script>
let x, y, z;  // Statement 1
x = 5;        // Statement 2
y = 6;        // Statement 3
z = x + y;    // Statement 4

document.getElementById("demo").innerHTML =
"The value of z is " + z + ".";  
</script>

</body>
</html>

## JS Syntax
#### How to create variables:
var x;
let y;

#### How to use variables:
x = 5;
y = 6;
let z = x + y;

The JavaScript syntax defines two types of values:
<ul>
  <li>Fixed values</li>
  <li>Variable values</li>
</ul>
<html>
<body>

<h2>JavaScript Numbers</h2>

<p>Number can be written with or without decimals.</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 10.50;
</script>

</body>
</html>

## JS Comments
use // buat memendam data.

## JS Variables
JavaScript Variables can be declared in 4 ways:
<ul>
  <li>Automatically</li>
  <li>Using var</li>
  <li>Using let</li>
  <li>Using const</li>
</ul>
<html>
<body>
<h1>JavaScript Variables</h1>

<p>In this example, x, y, and z are variables.</p>

<p id="demo"></p>

<script>
var x = 5;
var y = 6;
var z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

</body>
</html>

## JS Let
The let keyword was introduced in ES6 (2015)
<ul>
  <li>Variables declared with let have Block Scope</li>
  <li>Variables declared with let must be Declared before use</li>
  <li>Variables declared with let cannot be Redeclared in the same scope</li>
</ul>
<html>
<body>

<h2>Redeclaring a Variable Using let</h2>

<p id="demo"></p>

<script>
let  x = 10;
// Here x is 10

{  
  let x = 2;
  // Here x is 2
}

// Here x is 10
document.getElementById("demo").innerHTML = x;
</script>

</body>
</html>

## JS Const
<html>
<body>

<h2>JavaScript const</h2>

<p id="demo"></p>

<script>
try {
  const PI = 3.141592653589793;
  PI = 3.14;
}
catch (err) {
  document.getElementById("demo").innerHTML = err;
}
</script>

</body>
</html>

## JS Operators
<ul>
  <li>The Assignment Operator = assigns values</li>
  <li>The Addition Operator + adds values</li>
  <li>The Multiplication Operator * multiplies values</li>
  <li>The Comparison Operator > compares values</li>
</ul>

<html>
<body>

<h1>JavaScript Operators</h1>
<h2>The Assignment (=) Operator</h2>

<p id="demo"></p>

<script>
// Assign the value 5 to x
let x = 5;
// Assign the value 2 to y
let y = 2;
// Assign the value x + y to z
let z = x + y;
// Display z
document.getElementById("demo").innerHTML = "The sum of x + y is: " + z;
</script>

</body>
</html>

## JS Arithmetic
Arithmetic operators perform arithmetic on numbers (literals or variables).

Operator Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Remainder)
++	Increment
--	Decrement

<h1>JavaScript Arithmetic</h1>
<h2>Arithmetic Operations</h2>
<p>A typical arithmetic operation takes two numbers (or expressions) and produces a new number.</p>

<p id="demo"></p>

<script>
let a = 3;
let x = (100 + 50) * a;
document.getElementById("demo").innerHTML = x;
</script>

</body>
</html>

## JS Assignment
Operator	Example	Same As
=	x = y	x = y
+=	x += y	x = x + y
-=	x -= y	x = x - y
*=	x *= y	x = x * y
/=	x /= y	x = x / y
%=	x %= y	x = x % y
**=	x **= y	x = x ** y

## JS Data Types
 JavaScript has 8 Datatypes :  
<ul>
  <li>String</li>
  <li>Number</li>
  <li>Bigint</li>
  <li>Boolean</li>
  <li>Undefined</li>
  <li>Null</li>
  <li>Symbol</li>
  <li>Object</li>
</ul>
// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

// Date object:
const date = new Date("2022-03-25");

## JS Functions
The code inside the function will execute when "something" invokes (calls) the function :
<ul>
  <li>When an event occurs (when a user clicks a button)</li>
  <li>When it is invoked (called) from JavaScript code</li>
  <li>Automatically (self invoked)</li>
</ul>

<html>
<body>
<h1>JavaScript Functions</h1>

<p>Call a function which performs a calculation and returns the result:</p>

<p id="demo"></p>

<script>
function myFunction(p1, p2) {
  return p1 * p2;
}

let result = myFunction(4, 3);
document.getElementById("demo").innerHTML = result;
</script>

</body>
</html>

## JS Object
car.name = Fiat
car.model = 500
car.weight = 850kg
car.color = white	
car.start()
car.drive()
car.brake()
car.stop()

#### Object Properties
A real life car has properties like weight and color:
<ul>
  <li>car.name = Fiat, car.model = 500, car.weight = 850kg, car.color = white.</li>
  <li>Car objects have the same properties, but the values differ from car to car.</li>
</ul>

#### Object Methods
A real life car has methods like start and stop:
<ul>
  <li>car.start(), car.drive(), car.brake(), car.stop().</li>
  <li>Car objects have the same methods, but the methods are performed at different times.</li>
</ul>

<p id="demo"></p>

<script>
// Create an Object:
const car = {type:"Fiat", model:"500", color:"white"};

// Display Data from the Object:
document.getElementById("demo").innerHTML =
"The car type is " + car.type;
</script>

</body>
</html>

<html>
<body>
<h1>JavaScript Variables</h1>
<h2>Creating a Variable</h2>
<p id="demo"></p>

<script>
// Create and a Variable:
let car = "Fiat";
document.getElementById("demo").innerHTML = "Car: " +  car;
</script>

</body>
</html>

## JS Object Properties
// objectName.property
let age = person.age;
or

//objectName["property"]
let age = person["age"];
or

//objectName[expression]
let age = person[x];

<html>
<body>
<h1>JavaScript Object Properties</h1>
<h2>Access a Property with .</h2>

<p id="demo"></p>

<script>
const person = {
  firstname: "John",
  lastname: "Doe",
  age: 50,
  eyecolor: "blue"
};

document.getElementById("demo").innerHTML = person.firstname + " is " + person.age + " years old.";
</script>

</body>
</html>

## JS Object Methods
<html>
<body>
<h1>JavaScript Objects</h1>
<h2>Object Methods</h2>
<p>A method is a function definition stored as a property value.</p>

<p id="demo"></p>

<script>
const person = {
  firstName: "John",
  lastName: "Doe",
  id: 5566,
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};

document.getElementById("demo").innerHTML = person.fullName();
</script>
</body>
</html>

## JS Object Display
<html>
<body>
<h1>JavaScript Objects</h1>
<h2>Display Properties with JSON</h2>

<p id="demo"></p>

<script>
// Create an Object
const person = {
  name: "John",
  age: 30,
  city: "New York"
};

// Display JSON
document.getElementById("demo").innerHTML = JSON.stringify(person);
</script>

</body>
</html>

## JS Object Constructors
<html>
<body>
<h1>JavaScript Object Constructors</h1>

<p id="demo"></p>

<script>
// Constructor Function for Person objects
function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}

// Create a Person object
const myFather = new Person("John", "Doe", 50, "blue");

// Display age
document.getElementById("demo").innerHTML =
"My father is " + myFather.age + "."; 
</script>

</body>
</html>

## JS Events
Event	Description
onchange = An HTML element has been changed
onclick	= The user clicks an HTML element
onmouseover	= The user moves the mouse over an HTML element
onmouseout	= The user moves the mouse away from an HTML element
onkeydown	= The user pushes a keyboard key
onload	= The browser has finished loading the page

<html>
<body>
<h1>JavaScript HTML Events</h1>
<h2>The onclick Attribute</h2>

<button onclick="document.getElementById('demo').innerHTML=Date()">The time is?</button>

<p id="demo"></p>

</body>
</html>

<button onclick="this.innerHTML = Date()">The time is?</button>

## JS Strings
<html>
<body>

<h1>JavaScript Strings</h1>
<p>You can use quotes inside a string, as long as they don't match the quotes surrounding the string.</p>

<p id="demo"></p>

<script>
let answer1 = "It's alright";
let answer2 = "He is called 'Johnny'";
let answer3 = 'He is called "Johnny"'; 

document.getElementById("demo").innerHTML =
answer1 + "<br>" + answer2 + "<br>" + answer3; 
</script>

</body>
</html>

## JS String Methods
Basic String Methods
Javascript strings are primitive and immutable: All string methods produce a new string without altering the original string.
<ul>
<li>String length</li>
<li>String charAt()</li>
<li>String charCodeAt()</li>
<li>String at()</li>
<li>String []</li>
<li>String slice()</li>
<li>String substring()</li>
<li>String substr()</li>
</ul>
See Also:
<ul>
<li>String Search Methods</li>
<li>String Templates</li>
<li>String toUpperCase()</li>
<li>String toLowerCase()</li>
<li>String concat()</li>
<li>String trim()</li>
<li>String trimStart()</li>
<li>String trimEnd()</li>
<li>String padStart()</li>
<li>String padEnd()</li>
<li>String repeat()</li>
<li>String replace()</li>
<li>String replaceAll()</li>
<li>String split()</li>
</ul>

<html>
<body>

<h1>JavaScript String</h1>
<h2>The charAt() Method</h2>

<p>The charAt() method returns the character at a given position in a string:</p>

<p id="demo"></p>

<script>
var text = "HELLO WORLD";
document.getElementById("demo").innerHTML = text.charAt(0);
</script>

</body>
</html>

## JS String Search
String Search Methods :
<ul>
<li>String indexOf()</li>
<li>String lastIndexOf()</li>
<li>String search()</li>
</ul>
See Also:
<ul>
<li>Basic String Methods</li>
<li>String Templates</li>
<li>String match()</li>
<li>String matchAll()</li>
<li>String includes()</li>
<li>String startsWith()</li>
<li>String endsWith()</li>
</ul>

<html>
<body>

<h1>JavaScript Strings</h1>
<h2>The lastIndexOf() Method</h2>

<p>The position of the last occurrence of "locate" is:</p>

<p id="demo"></p>

<script>
let text = "Please locate where 'locate' occurs!";
let index = text.lastIndexOf("locate");
document.getElementById("demo").innerHTML = index;
</script>

</body>
</html>

## JS String Templates
<html>
<body>
<h1>JavaScript Template Strings</h1>
<p>Templates allow multiline strings:</p>

<p id="demo"></p>

<p>Templates are not supported in Internet Explorer.</p>

<script>
let text =

`The quick
brown fox
jumps over
the lazy dog`;

document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>

## JS Numbers
let x = 100;         // x is a number

let y = "100";       // y is a string

<html>
<body>

<h2>JavaScript Numbers</h2>

<p>JavaScript will try to convert strings to numbers when dividing:</p>

<p id="demo"></p>

<script>
let x = "100";
let y = "10";
let z = x / y;   
document.getElementById("demo").innerHTML = z;
</script>

</body>
</html>

## JS Biglnt
With BigInt the total number of supported data types in JavaScript is 8:
<ul>
<li>1. String</li>
<li>2. Number</li>
<li>3. Bigint</li>
<li>4. Boolean</li>
<li>5. Undefined</li>
<li>6. Null</li>
<li>7. Symbol</li>
<li>8. Object</li>
</ul>

ecause of this, JavaScript can only safely represent integers:
Up to 9007199254740991 +(253-1)
and
Down to -9007199254740991 -(253-1).
Integer values outside this range lose precision.

<html>
<body>

<h1>JavaScript Numbers</h1>
<h2>Create a BigInt</h2>

<p id="demo"></p>

<script>
let x = 123456789012345678901234567890n;
let y = BigInt("123456789012345678901234567890");
document.getElementById("demo").innerHTML = x + "<br>" + y;
</script>

</body>
</html>

## JS Number Methods
Method	Description
toString()	Returns a number as a string
toExponential()	Returns a number written in exponential notation
toFixed()	Returns a number written with a number of decimals
toPrecision()	Returns a number written with a specified length
valueOf()	Returns a number as a number

<html>
<body>

<h2>JavaScript Number Methods</h2>

<p>The toString() method converts a number to a string.</p>

<p id="demo"></p>

<script>
let x = 123;
document.getElementById("demo").innerHTML =
  x.toString() + "<br>" +
   (123).toString() + "<br>" +
   (100 + 23).toString();
</script>

</body>
</html>

## JS Number Properties  
Property	Description
EPSILON	The difference between 1 and the smallest number > 1.
MAX_VALUE	The largest number possible in JavaScript
MIN_VALUE	The smallest number possible in JavaScript
MAX_SAFE_INTEGER	The maximum safe integer (253 - 1)
MIN_SAFE_INTEGER	The minimum safe integer -(253 - 1)
POSITIVE_INFINITY	Infinity (returned on overflow)
NEGATIVE_INFINITY	Negative infinity (returned on overflow)

<html>
<body>

<h1>JavaScript Number Properties</h1>

<p>Using a Number property on a variable, or value, will return undefined:</p>

<p id="demo"></p>

<script>
let x = 6;
document.getElementById("demo").innerHTML = x.MAX_VALUE;
</script>

</body>
</html>

## JS Arrays
let car1 = "Saab";
let car2 = "Volvo";
let car3 = "BMW";

<html>
<body>
<h1>JavaScript Arrays</h1>

<p id="demo"></p>

<script>
const cars = [];
cars[0]= "Saab";
cars[1]= "Volvo";
cars[2]= "BMW";
document.getElementById("demo").innerHTML = cars;
</script>

</body>
</html>

## JS Array Methods
Array length	Returns the length (size) of an array
Array toString()	Converts an array to a comma separated string of values
Array at()	Returns an indexed element from an array
Array join()	Joins all array elements into a string
Array pop()	Removes the last element from an array
Array push()	Adds a new element to an array
Array shift()	Removes the first array element
Array unshift()	Adds a new element at the beginning of an array
Array delete()	Creates undefined holes in the array
Array concat()	Creates a new array by merging existing arrays
Array copyWithin()	Copies array elements to another position in the array
Array flat()	Creates a new array from sub-array elements
Array slice()	Slices out a part of an array
Array splice()	Adds new items to an array
Array toSpliced()	Adds new items to an array in a new array
See Also:
Search Methods	  Different array index or find methods
Sort Methods	    Different array sort methods
Iteration Methods	Different array ineration methods

const fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits.toString();

<html>
<body>
<h1>JavaScript Arrays</h1>
<h2>The at() Method</h2>

<p>The at() method returns an indexed element from an array:</p>

<p id="demo"></p>

<script>
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let fruit = fruits.at(2);

document.getElementById("demo").innerHTML = fruit;
</script>

</body>
</html>

## JS Array Search
Array indexOf()	Returns the first position of an element value
Array lastIndexOf()	Returns the last position of an element value
Array includes()	Returns true if an element value is present in an array
Array find()	Returns the value of the first element that passes a test
Array findIndex()	Returns the index of the first element that passes a test
Array findLast()	Returns the value of the last element that passes a test
Array findLastIndex()	Returns the index of the last element that passes a test

<html>
<body>
<h1>JavaScript Arrays</h1>
<h2>The lastIndexOf() Method</h2>

<p id="demo"></p>

<script>
const fruits = ["Apple", "Orange", "Apple", "Mango"];
let position = fruits.lastIndexOf("Apple") + 1;

document.getElementById("demo").innerHTML = "Apple is found in position " + position;
</script>

</body>
</html>

## JS Array Sort
## iS Array Iteration
## JS Array Const
## JS Dates
## JS Date Formats
## JS Date Get Methods
## JS Date Set Methods
## JS Math
## JS Booleans
## JS Comparisons
## JS If Else
## JS Switch
## JS Loop For
## JS Loop For In
## JS Loop For Of
## JS Loop While
