
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

* green{grid-column: 1/4; <p>
	(where it start) / (where it end)
	<div>
	<img src="https://user-images.githubusercontent.com/68550874/130927830-2859bd7f-f5dd-4fe7-82f1-28fe949e1335.png" width="300" height="200"/>
	</div>

<p><p>

* `` grid-column: 1/-1;`` → start to **very end**

	<div>
	<img src="https://user-images.githubusercontent.com/68550874/130942528-92279ea7-850e-4ee3-a5d1-3898512ae5e6.png" width="300" height="150"/>
	</div>
 
<p><p>

* ` .green{grid-column: span 3;}`
	
	<div>
	<img src="https://user-images.githubusercontent.com/68550874/130947619-6ce4ee06-c14d-4ac4-b192-0df5abf55de9.png" width="300" height="150"/>
	</div>

* .green{grid-column: span 2; grid-row: 1/3;}

	<div>
	<img src="https://user-images.githubusercontent.com/68550874/130948215-5c06a12e-de6b-4162-b3a5-960e5cbbc723.png" width="400" height="150"/>
	</div>








> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMzU4MjQ2NCwtMTk1OTY3ODAwOSw3OT
U4ODQ4ODcsMjA0MTc4MjA5NywtMjg1Njg3MTEyLDMzNTgwODU5
Nyw0ODYxODg1MzAsLTM5NzQzMzMzMywtMTY3MzAwNzkxNyw1NT
Q0Mzg2OTMsLTQ3MzUzMjYxOSwxMDk3NTY3OTAyLC04NTc0ODEz
NDBdfQ==
-->
