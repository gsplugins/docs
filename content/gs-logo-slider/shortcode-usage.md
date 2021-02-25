---
title: 'Shortcode Usage'
date: '2019-11-06T09:07:55+00:00'
weight: 17
---
**Basic Usage**

```
[gs_logo]
```

**Shortcode attributes Usage**

```
[gs_logo title="yes" posts="15" order="ASC" logo_cat="food" mode="vertical" speed="1000" inf_loop="0" ticker="1" logo_color="gray_to_def"]
```

<table class="table table-responsive table-bordered">
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
			<td>title</td>
			<td>no</td>
			<td>no / yes</td>
			<td>Display Logo including / excluding Title. Default OFF</td>
		</tr>
		<tr>
			<td>2</td>
			<td>posts</td>
			<td>-1</td>
			<td>-1 for all or any number</td>
			<td>By default it’ll show all the Logos but you can control it by posts attribute.</td>
		</tr>
		<tr>
			<td>3</td>
			<td>order</td>
			<td>DESC</td>
			<td>DESC / ASC</td>
			<td>Normally Logos will show by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter</td>
		</tr>
		<tr>
			<td>4</td>
			<td>orderby</td>
			<td>date</td>
			<td>ID / title / modified / rand / menu_order (Drag & drop custom order)</td>
			<td>Use preffered orderby attribute</td>
		</tr>
		<tr>
			<td>5</td>
			<td>logo_cat</td>
			<td>all</td>
			<td>Logo category slug, comma separated.</td>
			<td>To get your category slug, go to GS Logos -> Logo Category. Here you will find Logo category & all the slugs</td>
		</tr>
		<tr>
			<td>6</td>
			<td>mode</td>
			<td>horizontal</td>
			<td>horizontal / vertical</td>
			<td>Select Direction mode to slide Logos. Default horizontal</td>
		</tr>
		<tr>
			<td>7</td>
			<td>speed</td>
			<td>500</td>
			<td>Any number</td>
			<td>You can increase / decrease sliding speed. Set the speed in millisecond. Default 500. To disable autoplay just set the speed 0</td>
		</tr>
		<tr>
			<td>8</td>
			<td>inf_loop</td>
			<td>1</td>
			<td>0 / 1</td>
			<td>If ON, clicking “Next” while on the last slide will transition to the first slide and vice-versa. Default On (1)</td>
		</tr>
		<tr>
			<td>9</td>
			<td>ticker</td>
			<td>0</td>
			<td>0 / 1</td>
			<td>Slide Logos in ticker mode (similar to a news ticker). Default Off( 0 ). In order to make the ticker appear slower, the Speed value must be raised. <code>[gs_logo speed="20000" ticker="1" inf_loop="0"]</code>
			</td>
		</tr>
		<tr>
			<td>10</td>
			<td>logo_color</td>
			<td>Default</td>
			<td>gray / gray_to_def / def_to_gray</td>
			<td>Logo grayscale feature works only in modern browsers like Chrome, Firefox and Safari</td>
		</tr>
		<tr>
			<td>11</td>
			<td>theme</td>
			<td>slider1</td>
			<td>
				slider1 <br>
				ticker1 <br>  
				grid1 <br>  
				grid2 <br> 
				grid3 <br> 
				list1 <br> 
				list2 <br> 
				list3 <br> 
				table1 <br> 
				table2 <br> 
				table3 <br> 
				vslider1 <br>  
				filter1 <br> 
				filter2 <br> 
				filter3 <br> 
				filter-select <br>  
				filterlive1 <br> 
				filterlive2 <br> 
				filterlive3 <br> 
				slider_fullwidth <br>
				center <br>
				vwidth <br>  
				verticalcenter <br>
				verticalticker <br>  
				verticaltickerdown <br> 
				2rows
			</td>
			<td>Select preferred theme from 25 ready views</td>
		</tr>
		<tr>
			<td>12</td>
			<td>tooltip</td>
			<td>None</td>
			<td>tooltip</td>
			<td>Show / Hide Tooltip. Default : Off</td>
		</tr>
		<tr>
			<td>13</td>
			<td>max_logo</td>
			<td>5</td>
			<td>Any number</td>
			<td>Maximum number of Logos to display</td>
		</tr>
	</tbody>
</table>