JAVASCRIPT TYPES
-----------------
1. Number  -> 8/3, 7%2
2. String -> "this isn**\'t** very nice"
3. Boolean
4. Undefined
5. Null
6. Symbol (new in ECMAScript 6) 
7. Object
8. **Arguments** 
	 ```java 
	 console.log(Im an argument)
	```
9. **Parameters**
	 ```java 
	function  multiply(im a parameter){
	return  a*b;)
	```

JAVASCRIPT COMPARISONS
-----------------

    ===  (3 EQUALS)
    !==
    >=
    <=
    >
    <

JAVASCRIPT VARIABLES
-----------------
`var`
```java 
INPUT:
var George ="These pretzels are making me hungry."

OUTPUT
undefined
```
```java
INPUT:
George

OUTPUT:
"These pretzels are making me hungry."
```

` let `

Declare a variable with the name "message"
```java
let message;
```

String is saved into memory 
```java
let message;  
message = 'Hello'; // store the string 'Hello' in the variable named message_
```
`const `
Unchanging variable, can't be reassigned


JAVASCRIPT CONDITIONALS
-----------------
if
else
else if
<!-- ternary operator -->
<!-- switch -->
```java
var name="Billy"; //Hi Billy
var name="Susan"; //Oh! You are Billy's sister!
var name="Suzy" //I don't know you

if(name==="Billy") {alert("Hi Billy");}
else if(name==="Susan"){alert("Oh! You are Billy's sister!")}
else alert("I don't know you.");
```

JAVASCRIPT LOGICAL OPERATORS
-----------------
&&
||
!
```java 
var name="Ann"
if(name==="Billy"||name==="Ann"){alert("Hi "+ name)}
```
JAVASCRIPT FUNCTIONS
-----------------
var a = function name() {}
function name() {}
return
<!-- () => (new in ECMAScript 6) -->

JAVASCRIPT DATA STRUCTURES
-----------------
Array
Object

JAVASCRIPT LOOPING
-----------------
for
while
do 
forEach (new in ECMAScript 5) 


JAVASCRIPT KEYWORDS
-----------------
break
case
catch
class
const
continue
debugger
default
delete
do
else
export
extends
finally
for
function
if
import
in
instanceof
new
return
super
switch
this
throw
try
typeof
var
void
while
with
yield

JAVASCRIPT EXERCISE
-----------------
//Evaluate the below:
5 + "34" -> 534
5 - "4" -> 1
10 % 5 -> 0
5 % 10 -> 5 
"Java" + "Script" -> JavaScript
" " + " " -> ""
" " + 0 -> "0"
true + true -> 2
true + false ->1
false + true -> 3
false - true -> -1
3 - 4 = -1
"Bob" - "bill" =NaN


//Evaluate the below comparisons:
5 >= 1 -> true
0 === 1 -> false
4 <= 1 => false
1 != 1 -> false
"A" > "B" -> false
"B" < "C" -> true
 **"a" > "A" -> true
"b" < "A" -> false
( A>a  {UPPERCASE>lowercase})**
true === false -> false
true != true ->false


// Make the string: "Hi There! It's "sunny" out" by using the + sign:
"Hi There!" + "It\'s \"sunny\" out" 

// add variable "firstName" and "lastName" // so that they equal your name
```java
var firstName = "Patricia"
var lastName = "Kuo"
var fullName = firstName +" "+ lastName
alert("My name is " + fullName )
```

// create a variable that holds the answer // of "firstName" + " " + "lastName"

// Evaluate this question. What is a + b?
var a = 34;
var b = 21;
a = 2;
a + b // what is the answer here?
**23**

// What is c equal to?
var c;
**undefined**

Name the eight data types in JavaScript.

Understand the difference between single, double, and backtick quotes.

Embed a variable/expression in a string.

Define what a method is.

Name the three logical operators.

Understand what the comparison operators are.

Understand what conditionals are.

Understand what nesting is.

Understand what truthy and falsy values are.



## Make a Easy cac

ALL
```java
var  first  =prompt("Enter first Number");
var  second  =prompt("Enter second number");
var  op  =prompt("Select an operation mode(+ - / *): ");

switch(op) {
case  '+':
alert("The sum is: "+Number(first)+Number(second));
break;

case  '-':
alert("The sum is: "+Number(first)-Number(second));
break;

case  '*':
alert("The sum is: "+Number(first)*Number(second));
break;

case  '/':
alert("The sum is: "+Number(first)/Number(second));
break;

default:
alert("Wrong Input");
}
```

BREAK IT UP
```java
var first =prompt("Enter first Number");    //34
var second =prompt("Enter second number");    //55

undefined
```
```java
var sum = Number(first) + Number(second)

undefined
```
```java
sum 
69
```



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwOTA2NjkzMTEsLTY1NjQyNzMyMSwtMj
A5NDEyNjc5MSwxODA4ODUxMDIzLDY3MDg4NzExMCwtMTE4NDI3
Mjk1NiwtMTI4ODY3MDkyNiwxNzA3MjgzNTEyLDExMTM0NjMxOT
csNTI4NTYyNjMxLC0xMDYyNzg3MDcwLC0xOTIwMzc0Mjc4LDg3
NzY3OTQzMCwtMTExODY5NTM5NSwxNDE5NDg2NTYwLDczMDk5OD
ExNl19
-->