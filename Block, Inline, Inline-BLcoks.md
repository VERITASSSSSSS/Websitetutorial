# Block-level Elements

* **Full-width** by default
* Each starts with a **new line**
* Width & Height **can** be set
*  ```<div> <p> <h1> <ul> <footer>```


# Inline Elements
* Side by side
* Takes space as much as needed
* Width & Height **can't** be set

# Grid Templates
* ``grid-template-columns: ; `` → we want columns
* ``grid-template-rows: ;``

* ``fr`` → fraction
	grid-template-columns: 1fr 1fr 2fr; <p>
	|----| |----| |------|
	
* ``auto``→ fill in whatecer avaliable
	grid-template-columns: auto 1fr 2fr;
	| --adjust--| |--| |----|

* ``repeat( )``→ (how many times, fr)
grid-template-columns: repeat(3);
	

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMzQ4MDM4NDYsLTM5ODcyOTA3MiwtND
M2NTQyNjg0LC0xMTkwMjAxNzYwLC05MzUxNjczMDIsLTEwMzYw
OTE5NzAsLTMwNzQ5ODM0NV19
-->