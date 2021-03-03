---
title: 'Shortcode Usage'
date: '2019-01-01T12:29:59+00:00'
weight: 10
---
**Basic Usage**

```
[gs_testimonial]
```

**Shortcode attributes Usage**

```
[gs_testimonial posts="20" order="DESC" orderby="rand" cat_name="ceo" transition="carousel" theme="gs_style1" img="gs_circle"]
```

<table class="table table-bordered">
	<tbody>
		<tr>
			<th>No.</th>
			<th>Attribute</th>
			<th>Default value</th>
			<th>Options</th>
			<th>Description</th>
		</tr>
		<tr>
			<td>1</td>
			<td>posts</td>
			<td>-1</td>
			<td>-1 for all or any number</td>
			<td>By default it’ll show all the Testimonials but you can control it by posts attribute.</td>
		</tr>
		<tr>
			<td>2</td>
			<td>order</td>
			<td>DESC</td>
			<td>
				DESC <br>  
				ASC
			</td>
			<td>Normally Testimonials will show by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter</td>
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
			<td>cat_name</td>
			<td>all</td>
			<td>Testimonial Category Slug</td>
			<td>To get your Testimonial category slug, go to GS Testimonials -> Testimonial Category. Here you will find Testimonial category & all the slugs</td>
		</tr>
		<tr>
			<td>5</td>
			<td>transition</td>
			<td>carousel</td>
			<td>
				carousel <br> 
				fade <br> 
				fadeout <br> 
				scrollHorz <br> 
				scrollVert <br> 
				flipHorz <br> 
				flipVert <br>  
				shuffle <br> 
				tileSlide
			</td>
			<td>Use preffered transition effect attribute from 9 different Transitions</td>
		</tr>
		<tr>
			<td>6</td>
			<td>theme</td>
			<td>default</td>
			<td>
				gs_style1 <br>
				gs_style2 <br>
				gs_style3 <br> 
				gs_style4 <br> 
				gs_style5 <br>
				gs_style6 <br> 
				gs_style7 <br> 
				gs_style8 <br>
				gs_style9 <br> 
				none <br> 
				gs_style11 <br> 
				gs_style12 <br> 
				gs_style13 <br> 
				gs_style14 <br> 
				gs_style15 <br> 
				gs_style16 <br> 
				gs_style17
		</td>
			<td>Use preffered theme attribute from 20 different Themes / Styles</td>
		</tr>
	<tr>
			<td>7</td>
		<td>img</td>
		<td>default</td>
		<td>gs_square  
gs_circle  
gs_radius  
gs_square_shadow  
gs_circle_shadow  
gs_radius_shadow</td>
	<td>Use preffered Image thumb attribute from 6 Different Author thumb styles</td>
	</tr>
	<tr>
			<td>8</td>
		<td>readmore_link</td>
		<td>None</td>
		<td>Number Value</td>
		<td>Applicable for Column Slider (gs_style11) to control number of characters expand &amp; hide.</td>
		</tr>
	</tbody>
</table>