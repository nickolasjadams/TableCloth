# TableCloth v1.0.0
``` 
Copyright (c) 2018 Nick Adams
Licenced under the MIT license.
A tiny front-end framework for attractive tables out of the box
```

## Setting Up
Place the tablecloth css file in the head of your webpage


<a href="https://github.com/nickolasjadams/TableCloth/" target="blank">TableCloth Styles</a>



### Classes
TableCloth is meant to do all the repetitive table styling for you.  We keep our code native except a few classes.
```
ratetable
    twoCol, threeCol, fourCol
inception, 
hr
```

### Using Classes
All tables get the class "ratetable"


Tables can be assigned a class of "twoCol, threeCol, and fourCol".  These classes adjust aligment.

The inception class is assigned to tables that are within tables

the 'hr' class is assigned to rows.  It adds a bottom border.  
## Examples
```
<table class="ratetable twoCol">
	<caption>Caption</caption>
	<tr>
		<th>Heading</th>
		<th>Heading</th>
	</tr>
	<tr>
		<td>Cell</td>
		<td>Cell</td>
	</tr>
	<tr>
		<td>Cell</td>
		<td>Cell</td>
	</tr>
	<tr>
		<td>Cell</td>
		<td>Cell</td>
	</tr>
	<tr>
		<th>Heading</th>
		<th>Heading</th>
	</tr>
	<tr>
		<td>Cell</td>
		<td>Cell</td>
	</tr>
	<tr class="hr">
		<td>Cell</td>
		<td>Cell</td>
	</tr>
	<tr class="hr">
		<td>Cell</td>
		<td>Cell</td>
	</tr>
</table>
```
![Simple Table](https://raw.githubusercontent.com/nickolasjadams/TableCloth/master/example-images/simple_table.jpg?raw=true)