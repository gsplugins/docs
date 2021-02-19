---
title: 'Shortcode Usage'
date: '2019-11-07T04:13:40+00:00'
weight: 7
---
##### GS Pinterest Portfolio’s shortcode usage

```
[gs_pinterest]
```

##### GS Pinterest Portfolio’s Shortcode attributes Usage

```
[gs_pinterest user="pinterest" board="breakfast-favorites" count="20" theme="gs_pin_theme5" cols="4"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_pinterest]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Pinterest Portfolio in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_pinterest user="pinterest" board="breakfast-favorites" count="20" theme="gs_pin_theme5" cols="4"]' ); ?>
```

<table class="table table-bordered">
	<tbody>
		<tr>
			<th>No.</th>
			<th>Attribute</th>
			<th>Default value</th>
			<th>options</th>
			<th>Description</th>
		</tr>
		<tr>
			<td>1</td>
			<td>user</td>
			<td>None</td>
			<td>Pinterest User</td>
			<td>Add your Pinterest User</td>
		</tr>
		<tr>
			<td>2</td>
			<td>board</td>
			<td>None</td>
			<td>Pinterest Board Name</td>
			<td>Add Pinterest Board Name to display pins from specific Board</td>
		</tr>
		<tr>
			<td>3</td>
			<td>count</td>
			<td>10</td>
			<td>25</td>
			<td>Set number of pins to display. Default 10, max 25</td>
		</tr>
		<tr>
			<td>4</td>
			<td>theme</td>
			<td>gs_pin_theme1</td>
			<td>
				gs_pin_theme1 <br> 
				gs_pin_theme2 <br>
				gs_pin_theme3   
				gs_pin_theme4   
				gs_pin_theme5
			</td>
			<td>Select preferred theme to display Pins</td>
		</tr>
		<tr>
			<td>5</td>
			<td>cols</td>
			<td>4</td>
			<td>3 <br> 4 <br> 5 <br> 6</td>
			<td>Number of column/s to display pins</td>
		</tr>
	</tbody>
</table>