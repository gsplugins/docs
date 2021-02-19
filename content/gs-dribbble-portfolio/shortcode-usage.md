---
title: 'Shortcode Usage'
date: '2019-11-06T12:13:30+00:00'
weight: 7
---
```
[gs_dribbble]
```

###### GS Dribbble Portfolio’s Shortcode attributes Usage

```
[gs_dribbble count="6" column="4" theme="gs_drib_theme1"]
```

###### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_dribbble]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Dribbble Portfolio in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_dribbble count="6" column="4" theme="gs_drib_theme1"]' ); ?>
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
			<td>count</td>
			<td>6</td>
			<td>Any number</td>
			<td>Set number of shots to display</td>
		</tr>
		<tr>
			<td>2</td>
			<td>column</td>
			<td>3(4 columns)</td>
			<td>
				6 (2 columns) <br>
				4 (3 columns) <br>
				3 (4 columns)
			</td>
			<td>Columns are based on 12 grids Bootstarp, so follow columns value</td>
		</tr>
		<tr>
			<td>3</td>
			<td>theme</td>
			<td>gs_drib_theme1</td>
			<td>
				gs_drib_theme1 <br>
				gs_drib_theme2 
				gs_drib_theme3 
				gs_drib_theme4 
				gs_drib_theme5
			</td>
			<td>Select preferred theme to display Shots</td>
		</tr>
	</tbody>
</table>