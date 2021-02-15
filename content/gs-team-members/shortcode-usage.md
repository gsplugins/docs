---
title: 'Shortcode Usage'
date: '2019-11-06T11:45:26+00:00'
weight: 20
---
##### GS Team Member’s shortcode usage

**Note** : *From Version 1.10.1 shortcode generator added with preview.
Select theme & other parameters. Shortcode will generate with id like [gsteam id=1]*

```
[gsteam id=1]
[gs_team theme="gs_tm_theme5"] (Old Style)
```

##### GS Team Member’s Shortcode attributes Usage

**Note** : *From Version 1.10.1 shortcode generator added with preview.
NO NEED to add attributes. After selecting options, Shortcode will generate with id like [gsteam id=#]*

```
[gsteam id=1]
[gs_team num="10" cols="3" theme="gs_tm_theme8" group="hr"] (Old Style)
```

##### Shortcode PHP Usage

*Template Usage – Add the shortcode anywhere you need to display GS Team Member in template files (header.php, front-page.php, etc.)*

```
<?php echo do_shortcode( '[gsteam id=1]' ); ?>
```

**Note** : Before Version 1.9.14 Shortcode attributes need to add & keeping for old users. <br>
From Version 1.10.1 NO NEED to add attributes & will delete the below table later.

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
			<td>By default it’ll display all the Team Members but you can control it by <i>num</i> attribute.</td>
		</tr>
		<tr>	
			<td>2</td>	
			<td>order</td>	
			<td>DESC</td>	
			<td>
				DESC
				ASC
			</td>
			<td>Normally Membersw will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter.
			</td>
		</tr>
		<tr>	
			<td>3</td>	
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
 		<tr>
 			<td>4</td>
 			<td>group</td>
 			<td>all</td>
 			<td>Team category slug, comma separated.</td>
 			<td>To get your category slug, go to GS Team -&gt; Team Group. Here you will find Team Groups &amp; all the slugs</td>
 		</tr>
 		<tr>
			<td>5</td>
			<td>theme</td>
			<td>gs_tm_theme1</td>
			<td>
				gs_tm_theme1 <br>  
				gs_tm_theme2 <br>
				gs_tm_theme3 <br>  
				gs_tm_theme4 <br>  
				gs_tm_theme5 <br>
				gs_tm_theme6 <br>  
				gs_tm_theme7 <br>  
				gs_tm_theme8 <br>  
				gs_tm_theme9 <br>  
				gs_tm_theme10 <br>  
				gs_tm_theme11 <br>  
				gs_tm_theme12 <br>  
				gs_tm_theme13 <br>  
				gs_tm_theme14 <br>  
				gs_tm_theme15 <br>  
				gs_tm_theme16 <br>  
				gs_tm_theme17 <br>  
				gs_tm_theme18   
				gs_tm_theme19   
				gs_tm_theme20   
				gs_tm_grid2   
				gs_tm_drawer2
			</td>
			<td>Select preferred theme to display Members</td>
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
	 		<td>If you display only one category’s data then no need to display category names for filtering, passing the <code>none</code> value will hide the filtering section. Applicable for <i>gs_tm_theme9</i></td>
	 	</tr>
	 	<tr>
	 		<td>8</td>
	 		<td>panel</td>
	 		<td>right</td>
	 		<td>
	 			right <br>  
	 			left <br>   
	 			center
	 		</td>
 			<td>If you wish to display Team Members by custom order use mentioned shortcode, for custom order <code>orderby=”menu_order”</code> is mandatory. <br>
 			<code>[gs_team cols="3" theme="gs_tm_theme1" orderby="menu_order"]</code>
			</td>
		</tr>
	</tbody>
</table>