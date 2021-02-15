---
title: 'Shortcode Usage'
date: '2019-11-07T05:53:50+00:00'
weight: 8
---

#### Basic Usage

```
[gs_portfolio]
```

#### Shortcode attributes Usage

```
gs_portfolio posts="10" order="ASC" hover_effect="effect-zoe" popup_effect="mfp-newspaper"]
```

<!-- <div class="table-responsive"> -->
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
			<td>posts</td>
			<td>-1</td>
			<td>-1 for all or any number</td>
			<td>By default it’ll show all the Portfolios but you can control it by posts attribute.</td>
		</tr>
		<tr>
			<td>2</td>
			<td>order</td>
			<td>DESC</td>
			<td>
				DESC <br>
				ASC
			</td>
			<td>Normally Portfolios will show by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter.</td>
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
			<td>hover_effect</td>
			<td>effect-sadie</td>
			<td>
				effect-sadie <br>
				effect-julia <br>
				effect-kira <br>
				effect-winston <br>
				effect-zoe <br>
				effect_horizontal_1 <br>
				effect_horizontal_2 <br>
				effect_horizontal_3 <br>
				effect_horizontal_4 <br>
				effect-hexgrid <br>
				effect-slider <br>
				effect-masonary <br>
				filter-effect-sadie <br>
				filter-effect-julia <br>
				filter-effect-kira <br>
				filter-effect-winston <br>
				filter-effect-zoe <br>
				filter-selected-cats  
				effect-grid-slide <br>
				effect-column-animated <br>
				effect-column-3d <br>
				effect-timeline
			</td>
			<td>Use preferred hover effect attribute from 22 available <i>themes</i></td>
		</tr>
		<tr>
			<td>5</td>
			<td>popup_effect</td>
			<td>mfp-move-horizontal</td>
			<td>
				mfp-move-horizontal <br> 
				mfp-move-from-top 
				mfp-newspaper 
				mfp-3d-unfold  
				mfp-zoom-in  
				mfp-zoom-out
			</td>
			<td>Use preffered popup effect attribute</td>
		</tr>
		<tr>
			<td>6</td>
			<td>portfolio_cat</td>
			<td>all</td>
			<td>Portfolio Category Slug</td>
			<td>To get your Portfolio category slug, go to GS Portfolios -&gt; Portfolio Category. Here you will find Portfolio category &amp; all the slugs</td>
		</tr>
		<tr>
			<td>7</td>
			<td>port_cols_val</td>
			<td>4 (3 columns)</td>
			<td>
				6 (2 columns) <br>
				4 (3 columns) <br>
				3 (4 columns)
			</td>
			<td>Columns are based on 12 grids Bootstarp, so follow columns value</td>
		</tr>
		<tr>
			<td>8</td>
			<td>cats_name</td>
			<td>intitial</td>
			<td>none</td>
			<td>If you display only one category’s data then no need to display category names for filtering, passing the <code>none</code> value will hide the filtering section</td>
		</tr>
	</tbody>
</table>