# The Odin Project 
1.  Write a function called  `add7`  that takes one number and returns that number + 7.
	```java
	function  add7(){
	let num =  prompt("Enter a number: ");
	alert(Number(num)+7);19
	}
	add7();
	```
	**Number(num)+7**
	
2.  Write a function called  `multiply`  that takes 2 numbers and returns their product.

	```java
	function  multiply(){
	let num1 =  prompt("Enter the first number: ");
	let num2 =  prompt("Enter the second number: ");
	alert("Your number is "+num1*num2);
	}
	```

4.  Write a function called  `capitalize`  that takes a string and returns that string with  _only_  the first letter capitalized. Make sure that it can take strings that are lowercase, UPPERCASE or BoTh.
	```java
	function  capitalize(string) {

	const lower = string.toLowerCase();
	return string.charAt(0).toUpperCase() + lower.slice(1);
	}
	console.log(capitalize('gRaCiouS'));
	```
	**string.charAt(0).toUpperCase() + lower.slice(1);**

5.  Write a function called  `lastLetter`  that takes a string and returns the very last letter of that string:

	```java
	function  lastLetter(string) {
	return string.slice(-1);
	}
	console.log(lastLetter('gRaCiouS'));
	```

6.  `lastLetter("abcd")`  should return  `"d"`
	```java
	function  lastLetter(string) {
	return string.slice(-1);
	}
	console.log(lastLetter('abcd'));
	```
	**string.slice(-1)**

7. Make a keyless car
	```java
	var age =  prompt("How old are you?");
	if(Number(age)<18){
	alert("Sorry, you are too young to drive this car. Powering off.");}
	else  if(Number(age)===18){
	alert("Congratulations on your first year of driving. Enjoy the ride!");}
	else  alert("Powering On. Enjoy the ride!");
	```
	8. Im a way better keyless car
	```java
	var checkAge=function(){
	
	var age  =  prompt("What is your age?");
	if (Number(age) <  18) {
	alert("Sorry, you are too yound to drive this car. Powering off");
	} else  if (Number(age) >  18) {
	alert("Powering On. Enjoy the ride!");
	} else  if (Number(age) ===  18) {
	alert("Congratulations on your first year of driving. Enjoy the ride!");
	}}
 
	checkAge();
	```
	

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAxNTUxMjM0NywxNTY5NDkwNTY1LC0yMT
QzMTE1NTUsLTQ0NzU1MDg0MywxMTQwMDA1NjI3LC00ODk2NDE1
MzYsLTExMjUyMDk3NDEsLTEwMjgzOTYwMzMsMTc0NDIwNzEzOS
wtOTIyNjQ4MjI3LDczMDk5ODExNl19
-->