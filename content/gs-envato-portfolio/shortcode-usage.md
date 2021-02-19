---
title: 'Shortcode Usage'
date: '2019-11-07T06:12:27+00:00'
weight: 8
---
##### GS Envato Portfolio’s shortcode usage

```
[gs_envato theme="gs_envato_theme1"]
```

##### GS Envato Portfolio’s Shortcode attributes Usage

```
[gs_envato userid="themeum" market="themeforest" theme="gs_envato_theme1" cols="3" referral_user="gsplugins" count="10"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_envato theme="gs_envato_theme1"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Envato Portfolio in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_envato userid="themeum" market="themeforest" theme="gs_envato_theme1" cols="3" referral_user="gsplugins" count="10"]' ); ?>
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
			<td>themeum</td>
			<td>Envato User</td>
			<td>Add your Envato User</td>
		</tr>
		<tr>
			<td>2</td>
			<td>market</td>
			<td>themeforest</td>
			<td>themeforest <br>codecanyon</td>
			<td>Select your Marketplace</td>
		</tr>
		<tr>
			<td>3</td>
			<td>theme</td>
			<td>gs_envato_theme1</td>
			<td>
				gs_envato_theme1 <br>
				gs_envato_theme2 <br>
				gs_envato_theme3   
				gs_envato_theme4   
				gs_envato_theme5   
				gs_envato_theme6   
				gs_envato_theme7   
				gs_envato_theme8   
				gs_envato_theme9   
				gs_envato_theme10
			</td>
			<td>Select preferred theme to display Items</td>
		</tr>
		<tr>
			<td>4</td>
			<td>cols</td>
			<td>3(4 columns)</td>
			<td>
				6 (2 columns) <br> 
				4 (3 columns) <br> 
				3 (4 columns)
			</td>
			<td>Number of column/s to display items. Columns are based on 12 grids Bootstarp, so follow columns value</td>
		</tr>
		<tr>
			<td>5</td>
			<td>referral_user</td>
			<td>None</td>
			<td>Envato Ref ID</td>
			<td>Add your referral id for affiliate program</td>
		</tr>
		<tr>
			<td>6</td>
			<td>count</td>
			<td>10</td>
			<td>50</td>
			<td>Set number of Envato items to display. Default 10, max 50</td>
		</tr>
	</tbody>
</table>