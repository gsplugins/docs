---
title: 'Shortcode Usage'
date: '2019-11-07T05:54:40+00:00'
weight: 12
---

##### GS Coach’s shortcode usage

```
[gs_coaches theme="gs_coach_grid_1"]
```

##### GS Coach’s Shortcode attributes Usage

```
[gs_coaches num="6" theme="gs_coach_grid_1" cols="6" group="web-development" cats_name="none" desc_limit="100" order="DESC" orderby="date"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_coaches theme="gs_coach_grid_1"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Coaches in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_coaches num="6" theme="gs_coach_grid_1" cols="6" group="web-development" cats_name="none" desc_limit="100" order="DESC" orderby="date"]' ); ?>
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
				<td>By default it’ll display all the Coaches but you can control it by <code>num</code> attribute.</td>
			</tr>
			<tr>
				<td>2</td>
				<td>theme</td>
				<td>gs_coach_grid_1</td>
				<td>
					gs_coach_grid_1 <br>  
					gs_coach_grid_2 <br>
					gs_coach_grid_3 <br>
					gs_coach_circle_1 <br>
					gs_coach_circle_2 <br>
					gs_coach_circle_3 <br>  
					gs_coach_circle_4 <br>  
					gs_coach_horizontal_1 <br>  
					gs_coach_horizontal_2 <br>
					gs_coach_horizontal_3 <br>
					gs_coach_horizontal_4 <br>
					gs_coach_horizontal_5 <br>
					gs_coach_horizontal_6 <br>
					gs_coach_list_1 <br>
					gs_coach_list_2 <br>
					gs_coach_list_3 <br>
					gs_coach_list_4 <br>
					gs_coach_card_1 <br>
					gs_coach_card_2 <br>
					gs_coach_table_1 <br>
					gs_coach_table_2 <br>
					gs_coach_table_3
					gs_coach_grey_1   
					gs_coach_grey_2   
					gs_coach_slider_1   
					gs_coach_slider_2   
					gs_coach_slider_3   
					gs_coach_popup_1   
					gs_coach_filter_1
				</td>
 				<td>Select preferred theme to display Coaches</td>
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
				<td>Number of column/s to display coaches. Columns are based on 12 grids Bootstarp, so follow columns value</td>
			</tr>
			<tr>
				<td>4</td>
				<td>group</td>
				<td>all</td>
				<td>Coach category slug, comma separated.</td>
				<td>To get your category slug, go to GS Coach -&gt; Coach Group. Here you will find Coach Groups &amp; all the slugs</td>
			</tr>
			<tr>
				<td>5</td>
				<td>cats_name</td>
				<td>intitial</td>
				<td>none</td>
				<td>If you display only one category’s data then no need to display category names for filtering, passing the <code>none</code> value will hide the filtering section. Applicable for <i>gs_coach_filter_1</i></td>
			</tr>
			<tr>
				<td>6</td>
				<td>desc_limit</td>
				<td>100</td>
				<td>Any Number</td>
				<td>Set maximum number of characters in Coach details. Default 100</td>
			</tr>
			<tr>
				<td>7</td>
				<td>order</td>
				<td>DESC</td>
				<td>
					DESC <br>
					ASC
				</td>
				<td>Normally Coaches will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>
				order="ASC"</code> parameter.
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