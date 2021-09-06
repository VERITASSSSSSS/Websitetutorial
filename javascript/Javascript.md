# Questions
### **-    How do you declare a variable?**

Variable means anything that can *vary*. 
In JavaScript, a variable stores the data value that can be changed later on.

Use the reserved keyword `var` to declare a variable in JavaScript.

**Syntax**
   
 ``` java
 var <_variable-name_>;
 var <_variable-name_> = <_value_>;
```

   **Example: Variable Declaration**
   ```java
var msg; // declaring a variable without assigning a value
```

**Example: Variable Initialization**
```java
var msg; 
msg = "Hello JavaScript!"; // assigned a string value
alert(msg); // access a variable

//the following declares and assign a numeric value
var num = 100; 
var hundred = num;  // assigned a variable to varible
```
**Example: Multiple Variables**

```java
var one = 1, two = 'two', three;

//Output
1
two
undefined
```

### **-   What are three different ways to declare a variable?**
1. ```var```
	
	**Syntax**
	   
	 ``` java
	 var variableName = "Variable-Value;"
	```

	**Example: Variable Declaration**
	
	 ```java
	<script>
	    var geeks = "GeeksforGeeks";
	    console.log(geeks);
	</script>
	```

3. ```let```
4. ```const```

### **-   Which one should you use when?**


### **-   What are the rules for naming variables?**


### **-   What are operators, operands, and operations?**


### **-   What is concatenation and what happens when you add numbers and strings together?**


### **-   What are the different types of operators in JavaScript?**
### **-   What is the difference between  `==`  and  `===`?**

Check Equality
Go with ===

- **Abstract** Equality Comparison (==) 
	- automatically convert the types of the two values behind the scenes and only then will it make the actual comparison check

- **Strict** Equality Comparison (===)
	 - take data type into account, meaning a String will never be equal to a Number.

'2'==2 -> True


### **-   What are operator precedence values?**
### **-   What are the increment/decrement operators?**
### **-   What is the difference between prefixing and post-fixing them?**
### **-   What are assignment operators?**
### **-   What is the “Unary +” Operator?**
-   Unary plus (`+`) – convert an operand into a number

-   Unary minus (`-`) – convert an operand into a number and negate the value after that.

```java
let a = 10; 
a = +a; // 10 
a = -a; // -10
```

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE4MTI3MDkyXX0=
-->