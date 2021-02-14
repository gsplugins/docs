---
title: 'Shortcode Usage'
date: '2019-11-06T12:31:22+00:00'
weight: 7
---

##### GS Behance Portfolio’s shortcode usage

```
[gs_behance]
```

##### GS Behance Portfolio’s Shortcode attributes Usage

```
[gs_behance userid="creativemints" count="6" column="4" theme="gs_beh_theme1" field="branding"]
```

##### Shortcode PHP Usage

Template Usage – Add the shortcode anywhere you need to display GS Behance Portfolio in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_behance userid="creativemints" count="6" column="4" theme="gs_beh_theme1" field="Branding"]' ); ?>
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
			<td>userid</td>
			<td>None</td>
			<td>Behance User ID</td>
			<td>Add your Behance User ID</td>
		</tr>
		<tr>
			<td>2</td>
			<td>count</td>
			<td>6</td>
			<td>Any number</td>
			<td>Set number of projects to display.</td>
		</tr>
		<tr>
			<td>3</td>
			<td>column</td>
			<td>3(4 columns)</td>
			<td>
				4 (3 columns) <br>
				3 (4 columns)
			</td>
		 	<td>Columns are based on 12 grids Bootstarp, so follow columns value</td>
		</tr>
		<tr>
			<td>4</td>
		 	<td>theme</td>
		 	<td>gs_beh_theme1</td>
		 	<td>
				gs_beh_theme1  
				gs_beh_theme2  
				gs_beh_theme3  
				gs_beh_theme4  
				gs_beh_theme5  
				gs_beh_theme6  
				gs_beh_theme7
			</td>
			<td>Select preferred theme to display Projects</td>
		</tr>
		<tr>
			<td>5</td>
			<td>field</td>
			<td>None</td>
			<td>
				Art Direction <br> 
				Branding <br>
				Web Design <br>
				Illustration <br>
				UI/UX
			</td>
			<td>Select preferred field to display Projects. Go to Behance.net &amp; click on Search icon to see all Creative Fields.
			<b>field</b> parameter case &amp; space sensitive.</td>
		</tr>
	</tbody>
</table>