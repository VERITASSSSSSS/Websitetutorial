
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

<img scr="https://user-images.githubusercontent.com/68550874/130927830-2859bd7f-f5dd-4fe7-82f1-28fe949e1335.png" width="400" height="300">		


*`` grid-column: 1/-1;`` → start to **very end**
		
![image](https://user-images.githubusercontent.com/68550874/130942528-92279ea7-850e-4ee3-a5d1-3898512ae5e6.png )


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA0MTc4MjA5NywtMjg1Njg3MTEyLDMzNT
gwODU5Nyw0ODYxODg1MzAsLTM5NzQzMzMzMywtMTY3MzAwNzkx
Nyw1NTQ0Mzg2OTMsLTQ3MzUzMjYxOSwxMDk3NTY3OTAyLC04NT
c0ODEzNDBdfQ==
-->
