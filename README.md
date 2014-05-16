#Flexo

Flexo is a tiny css library to build responsive fluid grids. It's basically a shorthand to make build grids as easy as building tables.

###Example
```html
<div class="flexo">
	<div class="row">
		<div class="box stack">
			<div class="box">
				Box 1
			</div>
			
			<div class="box">
				Box 2
			</div>
		</div>
		
		<div class="box">
			Box 3
		</div>
	</div>
	
	<div class="row">
		<div class="box">
			Box 4
		</div>
		
		<div class="box stack">
			<div class="box">
				Box 5
			</div>
			
			<div class="row">
				<div class="box">
					Box 6
				</div>
				
				<div class="box">
					Box 7
				</div>
			</div>
		</div>
	</div>
</div>
```
###Classes

* ```.flexo```: Just a namespace. Put it on your root element.
* ```.row```: A row where you can add boxes from left to right.
* ```.box```: A box where you can put your content.
* ```.box.stack```: A box where you can add more boxes inside from top to bottom.
* ```.grow-1, .grow-2, ..., .grow-10```: Just sets the ```flex-grow``` value.