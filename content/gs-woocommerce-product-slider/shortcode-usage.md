---
title: 'Shortcode Usage'
date: '2019-11-06T10:49:27+00:00'
weight: 9
---
###### Generate Shortcode

GS WooCommerce Product Slider’s Generate Shortcode options available only at PRO version.

![WooCommerce Product Slider Generate Shortcode](../images/Woo_Product_generate_shortcode.png "WooCommerce Product Slider Generate Shortcode")

##### GS WooCommerce Product Slider’s shortcode usage

**Basic Usage**

```
[gs_wps]
```

**Shortcode attributes Usage**

```
[gs_wps id="" posts="5" order="ASC" product_cat="singles, albums" theme="gs-effect-2" columns="3" autoplay="true" pause="false" inf_loop="false" speed="1200" timeout="3000" nav_speed="1100" nav="none" dots_nav="false" prod_tit_limit="50"]
```

 Note : product_cat attribute will NOT work at PRO version, From Menu : GS Plugins &gt; Generate Shortcode, you can set your query then add the id attribute.

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
			<td>10</td>
			<td>Any Number</td>
			<td>By default it’ll display 10 Products as it is set total number of product in slider at Woo Product Settings but you can control by posts attribute.</td>
		</tr>
		<tr>
			<td>2</td>
			<td>order</td>
			<td>DESC</td>
			<td>DESC / ASC</td>
			<td>Normally Products will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass <code>order="ASC"</code> parameter</td>
		</tr>
		<tr>
			<td>3</td>
			<td>product_cat</td>
			<td>all</td>
			<td>Product category slug, comma separated.</td>
			<td>To get your category slug, go to Products -> Categories. Here you will find Product categories & all the slugs. Note : product_cat attribute will work only at lite version</td>
		</tr>
		<tr>
			<td>4</td>
			<td>id</td>
			<td>none</td>
			<td>Generate your query like all category products or selected category / exclude category, all products / featured / free & many more</td>
			<td>product_cat attribute will NOT work at PRO version, From Menu : GS Plugins > Generate Shortcode, you can set your query then add the id attribute</td>
		</tr>
		<tr>
			<td>5</td>
			<td>theme</td>
			<td>gs-effect-1</td>
			<td>
				gs-effect-1 <br>
				gs-effect-2 <br>
				gs-effect-3 <br>
				gs-effect-4 <br> 
				gs-effect-5 <br>
				gs-effect-6 <br> 
				gs-effect-7 <br> 
				gs-effect-8 <br> 
				gs-effect-9 <br>
				gs-effect-10
			</td>
			<td>Select preferred theme for hover effect</td></tr>
		<tr>
			<td>6</td>
			<td>columns</td>
			<td>4</td>
			<td>1 / 2 / 3 / 4 / 5 / 6</td>
			<td>Select number of Product columns, Default 4 columns</td>
		</tr>
		<tr>
			<td>7</td>
			<td>autoplay</td>
			<td>true</td>
			<td>true / false</td>
			<td>Enable / Disable Autoplay slider. Default On (true)</td>
		</tr>
		<tr>
			<td>8</td>
			<td>pause</td>
			<td>true</td>
			<td>true / false</td>
			<td>Enable / Disable, Stop on Hover slider. Default On (true)</td></tr>
		<tr>
			<td>9</td>
			<td>inf_loop</td>
			<td>true</td>
			<td>true / false</td>
			<td>Enable / Disable Inifnity loop. Duplicates last & first Product to get loop illusion. Default On (true)</td>
		</tr>
		<tr>
			<td>10</td>
			<td>speed</td>
			<td>1000</td>
			<td>Any Number</td>
			<td>Autoplay Speed in Millisecond. Default 1000</td>
		</tr>
		<tr>
			<td>11</td>
			<td>timeout</td>
			<td>2500</td>
			<td>Any Number</td>
			<td>Autoplay interval timeout in Millisecond. Default 2500</td>
		</tr>
		<tr>
			<td>12</td>
			<td>nav_speed</td>
			<td>1000</td>
			<td>Any Number</td>
			<td>Navigation speed in Millisecond. Default 1000</td>
		</tr>
		<tr>
			<td>13</td>
			<td>nav</td>
			<td>initial</td>
			<td>initial / none</td>
			<td>Enable / Disable Navigation (next / prev). Default On (initial)</td>
		</tr>
		<tr>
			<td>14</td>
			<td>dots_nav</td>
			<td>true</td>
			<td>true / false</td>
			<td>Enable / Disable Dots Navigation. Default On (true)</td>
		</tr>
		<tr>
			<td>15</td>
			<td>prod_tit_limit</td>
			<td>15</td>
			<td>Any Number</td>
			<td>Maximum number of characters in Product title. Default 15</td>
		</tr>
	</tbody>
</table>