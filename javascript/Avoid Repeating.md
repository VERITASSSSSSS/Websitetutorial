# Add Arguments
```java
function  sing(song){
console.log(song);
}

sing("LADSSSS");
sing("ewdsfwe");
sing("backsssrfew");
```
```java
function  multiply(a,b){
return  a*b;
}

var  total  =  multiply(4,5);
alert(total);
```
//add argument to avoid repeating
```java
var functionList = [function apple(){
console.log("apple");
}]
//undefined

//functionList
[ƒ]
0: ƒ apple()length: 1[[Prototype]]: Array(0)
```
## How arrays work
```var  list  = ["bear","cat", "duck"];```
list
```
(3) ["bear", "cat", "duck"]
```
list.**pop**();
The `pop()` method removes the **last** element from an array:

```
"duck"
```
list.**shift**();
The `shift()` method removes the **first** array element and "shifts" all other elements to a lower index.
```
"bear"
```
list;
```
["cat"]
```
list.**push**("elephant");
```
2
```
list
```
(2) ["cat", "elephant"]
```
list.concat(["bee","deer"])
```
(4) ["cat", "elephant", "bee", "deer"]
```

var myList =["cat", "elephant", "bee", "deer"]
```
undefined
```
var myNewList = myList.concat(["monkey"]);
 **gotta define**
```
undefined
```
myList
```
(4) ["cat", "elephant", "bee", "deer"]
```
myNewList
```
(5) ["cat", "elephant", "bee", "deer", "monkey"]
```
## Practice
1. Remove the Banana from the array.
	 ```java
	 array.shift();
	 "Banana"

	(3) ["Apples", "Oranges", "Blueberries"]
	 ```

2. Sort the array in order.
	 ```java
	 array.sort();
	 
	(3) ["Apples", "Blueberries", "Oranges"]
	 ```

3. Put "Kiwi" at the end of the array.
	 ```java
	 array.push("Kiwi");
	4

	(4) ["Apples", "Blueberries", "Oranges", "Kiwi"]
	 ```

4. Remove "Apples" from the array.
	 ```java
	 array.shift();
	"Apples"

	(3) ["Blueberries", "Oranges", "Kiwi"]
	 ```

6. Sort the array in reverse order. (Not alphabetical, but reverse
the current Array i.e. ['a', 'c', 'b'] becomes ['b', 'c', 'a'])
	 ```java
	 array.shift();
	 "Banana"

	(3) ["Apples", "Oranges", "Blueberries"]
	 ```

//you should have at the end:
["Kiwi", "Oranges", "Blueberries"]

using this array,
var array2 = ["Banana", ["Apples", ["Oranges"], "Blueberries"]];
// access "Oranges".

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAwNjYyMDQzNCwtMzQzNjIyNjA1LDgyMj
EyNDQ1NSwtMTMyNTE3MjM4Miw1MzkyMDU2MjldfQ==
-->