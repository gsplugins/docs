---
title: 'Shortcode Usage'
date: '2019-11-07T07:59:20+00:00'
weight: 8
---
##### GS Woocommerce Brands Shortcode Usage

**Basic Usage**

```
[brands_carousal]
```

```
[brands_products brand_id="brand id"]
```

```
[product_brand id="product id"]
```

**Shortcode attributes Usage**

```
[brands_carousal theme="slider3" name="off" image="on" description="off" col="3"]
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
			<td>theme</td>
			<td>slider2</td>
			<td>
				slider1 <br> 
				slider2 <br>
				slider3 <br>  
				ticker <br>  
				ticker-rtl <br>  
				filtera-z <br>  
				filter-list <br>  
				grid <br>
				grid-masonary <br>   
				data-table
			</td>
			<td>Select your preferred theme to display Brands.</td>
		</tr>
		<tr>
			<td>2</td>
			<td>name</td>
			<td>on</td>
			<td>on / off</td>
			<td>Choose to show / hide Brand Name</td>
		</tr>
		<tr>
			<td>3</td>
			<td>image</td>
			<td>on</td>
			<td>on / off</td>
			<td>Choose to show / hide Brand Image</td>
		</tr>
		<tr>
			<td>4</td>
			<td>col</td>
			<td>3</td>
			<td>3 / 4/ 2 </td>
			<td>Set columns. Applicable for few themes like Grid, Masonry, filter (A-Z)</td>
		</tr>
		<tr>
			<td>5</td>
			<td>description</td>
			<td>off</td>
			<td>on / off</td>
			<td>Choose to show / hide Brand Description. Applicable only for theme *filter-list*</td>
		</tr>
	</tbody>
</table>

```
[brands_products brand_id="45" columns="3" orderby="title" order="asc"]
```

<table class="table table-bordered"><tbody>
		<tr><th>No.
			</th><th>Attribute
			</th><th>Default value
			</th><th>options
			</th><th>Description
			</th>
		</tr>
		<tr>
			<td>1</td>
			<td>brand_id</td>
			<td>null</td>
			<td>45</td>
			<td>Set Brand ID to display Products from the specific Brand.</td>
		</tr>
		<tr>
			<td>2</td>
			<td>columns</td>
			<td>4</td>
			<td>4 / 3 / 2 / 6</td>
			<td>Set preferred column.</td>
		</tr>
		<tr>
			<td>3</td>
			<td>orderby</td>
			<td>title</td>
			<td>title / name / date / modified / rand</td>
			<td>Use preferred orderby attribute</td>
		</tr>
		<tr>
			<td>4</td>
			<td>order</td>
			<td>DESC</td>
			<td>DESC / ASC</td>
			<td>Normally Brands will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass order=”ASC” parameter</td>
		</tr>
	</tbody>
</table>

```
[product_brand id="398" width="100px"]
```

<table class="table table-bordered">
	<tbody>
		<tr><th>No.
			</th><th>Attribute
			</th><th>Default value
			</th><th>options
			</th><th>Description
			</th>
	</tr>
		<tr>
			<td>1</td>
			<td>id</td>
			<td>null</td>
			<td>642</td>
			<td>Set Product ID to display Brand List of Single Product.</td>
	</tr>
		<tr>
			<td>2</td>
			<td>width</td>
			<td>64px</td>
			<td>Any pixel like (148px)</td>
			<td>Set Brand image width.</td>
	</tr>
	</tbody>
</table>