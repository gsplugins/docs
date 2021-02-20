---
title: 'Shortcode Usage'
date: '2019-11-07T06:26:54+00:00'
weight: 7
---
##### GS YouTube Gallery’s shortcode usage

```
[gs_ytgal theme="gs_ytgal_grid"]
```

##### GS YouTube Gallery’s Shortcode attributes Usage

```
[gs_ytgal channel_id="UCANLZYMidaCbLQFWXBC95Jg" count="10" orderby="date" theme="gs_ytgal_grid" cols="6" video_height="350" title_limit="40" desc_limit="120"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_ytgal theme="gs_ytgal_grid"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS YouTube Gallery in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_ytgal channel_id="UCANLZYMidaCbLQFWXBC95Jg" count="10" orderby="date" theme="gs_ytgal_grid" cols="6" video_height="350" title_limit="40" desc_limit="120"]' ); ?>
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
			<td>channel_id</td>
			<td>None</td>
			<td>YouTube Channel ID</td>
			<td>Add your YouTube Channel ID. https://www.youtube.com/channel/UCB0SU0JDMMECS9BGJtD7lzg   
				Here <b>UCB0SU0JDMMECS9BGJtD7lzg</b> is the channel Id. 
				<b>Note</b> : If you add both Channel Id & Playlist Id at Settings then videos from Playlist will display.
			</td>
		</tr>
		<tr>
			<td>2</td>
			<td>count</td>
			<td>10</td>
			<td>50</td>
			<td>Set number of Videos to display. Default 10, max 50</td>
		</tr>
		<tr>
			<td>3</td>
			<td>orderby</td>
			<td>date</td>
			<td>
				date <br>  
				rating <br>
				title <br>  
				videoCount <br>   
				viewCount
			</td>
			<td>Select preferred orderby value to display Videos.</td>
		</tr>
		<tr>
			<td>4</td>
			<td>theme</td>
			<td>gs_ytgal_grid</td>
			<td>
				gs_ytgal_grid   
				gs_ytgal_grid_details 
				gs_ytgal_hoverpop   
				gs_ytgal_right_info   
				gs_ytgal_left_info   
				gs_ytgal_popup   
				gs_ytgal_slider_popup <br>
				gs_ytgal_slider
			</td>
			<td>Select preferred theme to display Videos</td>
		</tr>
		<tr>
			<td>5</td>
			<td>cols</td>
			<td>3(4 columns)</td>
			<td>
				6 (2 columns) <br>
				4 (3 columns) <br>
				3 (4 columns)
			</td>
			<td>Number of column/s to display videos. Columns are based on 12 grids Bootstarp, so follow columns value</td>
		</tr>
		<tr>
			<td>6</td>
			<td>video_height</td>
			<td>350</td>
			<td>Any numeric value you need.</td>
			<td>Sometimes video heighs are different & layout can be broken. In that case you can set video height.</td>
		</tr>
		<tr>
			<td>7</td>
			<td>title_limit</td>
			<td>40</td>
			<td>Any numeric value you need.</td>
			<td>Set maximum number of characters in Video Title. Default 40</td>
		</tr>
		<tr>
			<td>8</td>
			<td>desc_limit</td>
			<td>120</td>
			<td>Any numeric value you need.</td>
			<td>Set maximum number of characters in Video details. Default 120</td>
		</tr>
	</tbody>
</table>