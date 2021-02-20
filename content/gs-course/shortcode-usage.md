---
title: 'Shortcode Usage'
date: '2019-11-07T06:36:15+00:00'
weight: 11
---
##### GS Course’s shortcode usage

```
[gs_courses theme="gs_course_grid_1"]
```

##### GS Course’s Shortcode attributes Usage

```
[gs_courses num="6" theme="gs_course_grid_1" cols="3" group="" cats_name="none" desc_limit="" order="DESC" orderby="date"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_courses theme="gs_course_grid_1"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Course in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_courses num="6" theme="gs_course_grid_1" cols="3" group="" cats_name="none" desc_limit="" order="DESC" orderby="date"]' ); ?>
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
		<td>By default it’ll display all the Courses but you can control it by <b>num</b> attribute.</td>
	</tr>
	<tr>
		<td>2</td>
		<td>theme</td>
		<td>gs_course_grid_1</td>
		<td>
			gs_course_grid_1   
			gs_course_horizontal_1   
			gs_course_horizontal_2   
			gs_course_list_1   
			gs_course_list_2   
			gs_course_card_1   
			gs_course_slider_1   
			gs_course_popup_1   
			gs_course_filter_1
		</td>
		<td>Select preferred theme to display Courses</td>
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
		<td>Number of column/s to display courses. Columns are based on 12 grids Bootstarp, so follow columns value</td>
	</tr>
	<tr>
		<td>4</td>
		<td>group</td>
		<td>all</td>
		<td>Course category slug, comma separated.</td>
		<td>To get your category slug, go to GS Course > Course Group. Here you will find Course Groups & all the slugs</td>
	</tr>
	<tr>
		<td>5</td>
		<td>cats_name</td>
		<td>intitial</td>
		<td>none</td>
		<td>If you display only one category’s data then no need to display category names for filtering, passing the ‘none’ value will hide the filtering section. Applicable for <i>gs_course_filter_1</i></td>
	</tr>
	<tr>
		<td>6</td>
		<td>desc_limit</td>
		<td>100</td>
		<td>Any Number</td>
		<td>Set maximum number of characters in Course details. Default 100</td>
	</tr>
	<tr>
		<td>7</td>
		<td>order</td>
		<td>DESC</td>
		<td>
			DESC <br>  
			ASC
		</td>
		<td>Normally Courses will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter.
		</td>
	</tr>
	<tr>
		<td>8</td>
		<td>orderby</td>
		<td>date</td>
		<td>
			ID <br>  
			title <br> 
			modified <br> 
			rand
		</td>
		<td>Use preffered orderby attribute</td>
	</tr>
</tbody>
</table>