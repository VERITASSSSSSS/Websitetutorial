
# Grid Templates
* ``grid-template-columns: ; `` → we want columns
* ``grid-template-rows: ;``

* ``justify-items: start;``  → align grid items with start of row axis

## Add in grid templates
* ``fr`` → fraction <p>
	grid-template-columns: 1fr 1fr 2fr; <p>
	|----| |----| |------|
	
* ``auto``→ fill in whatecer avaliable <p>
	grid-template-columns: auto 1fr 2fr; <p>
	| --adjust--| |--| |----|

* ``repeat( )``→ (how many times, fr) <p>
grid-template-columns: repeat(3);
	
## Use this for more response
* grid-template-columns: repeat(**auto-fill**, **minmax(200px, 1fr)**)  

* green{grid-column: 1/4;} <p>
	(where it start) / (where it end)
	<p>
![image](https://user-images.githubusercontent.com/68550874/130927830-2859bd7f-f5dd-4fe7-82f1-28fe949e1335.png){ width=50% }

*`` grid-column: 1/-1;`` → start to **very end**
		
![image](https://user-images.githubusercontent.com/68550874/130942528-92279ea7-850e-4ee3-a5d1-3898512ae5e6.png ){ width=50% }


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMDExOTkwNjEsNDg2MTg4NTMwLC0zOT
c0MzMzMzMsLTE2NzMwMDc5MTcsNTU0NDM4NjkzLC00NzM1MzI2
MTksMTA5NzU2NzkwMiwtODU3NDgxMzQwXX0=
-->