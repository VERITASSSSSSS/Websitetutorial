
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
	
* ``justify-items: start;``  → align grid items with start of row axis

* grid-template-columns: repeat(**auto-fill**, **minmax(200px, 1fr)**)  

* green{grid-column: 1/4;}
	![image](https://user-images.githubusercontent.com/68550874/130927830-2859bd7f-f5dd-4fe7-82f1-28fe949e1335.png)


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTU0NDM4NjkzLC00NzM1MzI2MTksMTA5Nz
U2NzkwMiwtODU3NDgxMzQwXX0=
-->
