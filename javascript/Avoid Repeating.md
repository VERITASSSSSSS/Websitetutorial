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
list.pop();
```
"duck"
```
list.shift();
```
"bear"
```
list;
```
["cat"]
```
list.push("elephant");
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
undefined
myList
(4) ["cat", "elephant", "bee", "deer"]
myNewList
(5) ["cat", "elephant", "bee", "deer", "monkey"]

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDcyMjY1MjMsLTEzMjUxNzIzODIsNT
M5MjA1NjI5XX0=
-->