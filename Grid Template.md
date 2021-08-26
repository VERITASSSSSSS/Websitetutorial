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

* ``fr`` → fraction <p>
	grid-template-columns: 1fr 1fr 2fr; <p>
	|----| |----| |------|
	
* ``auto``→ fill in whatecer avaliable <p>
	grid-template-columns: auto 1fr 2fr; <p>
	| --adjust--| |--| |----|

* ``repeat( )``→ (how many times, fr) <p>
grid-template-columns: repeat(3);
	

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU3MjA3ODIyXX0=
-->