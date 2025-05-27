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

String length
String charAt()
String charCodeAt()
String at()
String [ ]
String slice()
String substring()
String substr()
See Also:
String Search Methods
String Templates

## JS String Methods
## JS String Search
## JS String Templates
## JS Numbers
## JS Biglnt
## JS Number Methods
## JS Number Properties
## JS Arrays
## JS Array Methods
## JS Array Search
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
