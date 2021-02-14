---
title: 'Shortcode Usage'
date: '2019-11-07T04:33:13+00:00'
weight: 12
---
##### GS Book Showcase’s shortcode usage

```
[gs_book_showcase theme="gs_book_theme1"]
```

##### GS Book Showcase’s Shortcode attributes Usage

```
[gs_book_showcase num="10" theme="gs_book_theme1" cols="4" group="cookbook,fiction" cats_name="" desc_limit="100" order="DESC" orderby="date"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_book_showcase theme="gs_book_theme7"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Book Showcase in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_book_showcase num="10" theme="gs_book_theme1" cols="4" group="cookbook,fiction" cats_name="" desc_limit="100" order="DESC" orderby="date"]' ); ?>
```


<table class="table table-bordered">
	<tbody>
		<tr>
			<th>No.</th>
			<th>Attribute</th>
			<th>Default value</th>
			<th>options</th>
			<th>Description</th></tr>
		<tr>
			<td>1</td>
			<td>num</td>
			<td>-1</td>
			<td>-1 for all or any number</td>
			<td>By default it’ll display all the Books but you can control it by <b>num</b> attribute.</td>
		</tr>
		<tr>
			<td>2</td>
			<td>order</td>
			<td>DESC</td>
			<td>
				DESC <br>
				ASC
			</td>
 			<td>Normally Books will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter.
 			</td>
		</tr>
		<tr>
			<td>3</td>
			<td>orderby</td>
			<td>date</td>
			<td>ID <br> title <br> modified <br> rand</td>
	 		<td>Use preffered orderby attribute</td>
	 	</tr>
		<tr>
			<td>4</td>
	 		<td>group</td>
	 		<td>all</td>
	 		<td>Book Showcase category slug, comma separated.</td>
	 		<td>To get your category slug, go to GS Book Showcase -&gt; Book Showcase Group. Here you will find Book Showcase Groups &amp; all the slugs</td>
	 	</tr>
	 	<tr>
			<td>5</td>
	 		<td>theme</td>
	 		<td>gs_book_theme1</td>
	 		<td>
				gs_book_theme1   
				gs_book_theme2   
				gs_book_theme3   
				gs_book_theme4   
				gs_book_theme7   
				gs_book_theme7_1   
				gs_book_theme8   
				gs_book_theme9   
				gs_book_theme10   
				gs_book_theme11
			</td>
	 		<td>Select preferred theme to display Books</td>
	 	</tr>
			<tr>
 			<td>6</td>
			<td>cols</td>
			<td>3(4 columns)</td>
			<td>
				6 (2 columns) <br>  
				4 (3 columns) <br>
				3 (4 columns)
			</td>
			<td>Columns are based on 12 grids Bootstarp, so follow columns value</td>
		</tr>
	 	<tr>
	 		<td>7</td>
	 		<td>cats_name</td>
	 		<td>intitial</td>
	 		<td>none</td>
	 		<td>If you display only one category’s data then no need to display category names for filtering, passing the ‘none’ value will hide the filtering section. Applicable for <i>gs_book_theme9</i></td>
	 	</tr>
	 	<tr>
			<td>8</td>
	 		<td>desc_limit</td>
	 		<td>100</td>
	 		<td>Any Number</td>
	 		<td>Set maximum number of characters in Book details. Default 100</td>
		</tr>
 	</tbody>
</table>