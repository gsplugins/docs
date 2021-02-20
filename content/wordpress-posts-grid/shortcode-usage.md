---
title: 'Shortcode usage'
date: '2019-11-07T06:49:40+00:00'
weight: 9
---
**How to use shortcode inside page templates?**  
WordPress has a great function, do_shortcode(), that will allow you to use shortcodes inside your theme files. For example, to output Posts in a Theme file, you would do this: 
```
<?php echo do_shortcode('[gs_wpposts theme="gs_wppost_grid_1"]'); ?>
```

##### GS Posts Grid’s shortcode usage

```
[gs_wpposts theme="gs_wppost_grid_1"]
```

##### GS Posts Grid’s Shortcode attributes Usage

```
[gs_wpposts theme="gs_wppost_grid_1" cols="4" num="9" desc_limit="250" group="" order"DESC" orderby="date"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_wpposts theme="gs_wppost_grid_1"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Posts Grid in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_wpposts theme="gs_wppost_grid_1" cols="4" num="9" desc_limit="250" group="" order"DESC" orderby="date"]' ); ?>
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
		<td>num</td>
		<td>-1</td>
		<td>-1 for all or any number</td>
		<td>By default it’ll display all the Latest Posts but you can control it by <i>num</i> attribute.</td>
	</tr>
	<tr>
		<td>2</td>
		<td>theme</td>
		<td>gs_wppost_grid_1</td>
		<td>
			gs_wppost_grid_1 <br>
			gs_wppost_grid_2 <br>
			gs_wppost_grid_3 <br>  
			gs_wppost_horizontal_1   
			gs_wppost_horizontal_2   
			gs_wppost_horizontal_3   
			gs_wppost_horizontal_4   
			gs_wppost_horizontal_5   
			gs_wppost_horizontal_6   
			gs_wppost_list_1 <br>  
			gs_wppost_list_2 <br>  
			gs_wppost_list_3 <br>  
			gs_wppost_list_4 <br>  
			gs_wppost_card_1 <br>  
			gs_wppost_card_2 <br>  
			gs_wppost_table_1 <br>  
			gs_wppost_table_2 <br>  
			gs_wppost_table_3 <br>  
			gs_wppost_grey_1   
			gs_wppost_grey_2   
			gs_wppost_slider_1   
			gs_wppost_slider_2   
			gs_wppost_slider_3   
			gs_wppost_popup_1   
			gs_wppost_popup_2   
			gs_wppost_filter_1   
			gs_wppost_filter_2   
			gs_wppost_masonry1   
			gs_wppost_masonry2   
			gs_wppost_masonry3   
			gs_wppost_justified1
		</td>
		<td>Select preferred theme to display Posts</td>
	</tr>
	<tr>
		<td>3</td>
		<td>cols</td>
		<td>3(4 columns)</td>
		<td>
			6 (2 Columns) <br>  
			4 (3 columns) <br> 
			3 (4 columns)
		</td>
		<td>Number of column/s to display Posts. Columns are based on 12 grids Bootstarp, so follow columns value</td>
	</tr>
	<tr>
		<td>4</td>
		<td>group</td>
		<td>all</td>
		<td>Post category slug, comma separated.</td>
		<td>To get your category slug, go to Posts > Categorirs. Here you will find Categorirs & all the slugs</td>
	</tr>
	<tr>
		<td>5</td>
		<td>desc_limit</td>
		<td>100</td>
		<td>Any Number</td>
		<td>Set maximum number of characters in Post details. Default 100</td>
	</tr>
	<tr>
		<td>6</td>
		<td>order</td>
		<td>DESC</td>
		<td>DESC <br> ASC</td>
		<td>Normally Posts will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter.</td>
	</tr>
	<tr>
		<td>7</td>
		<td>orderby</td>
		<td>date</td>
		<td>ID <br> title <br> modified <br> rand</td>
		<td>Use preffered orderby attribute</td>
	</tr>
</tbody>
</table>