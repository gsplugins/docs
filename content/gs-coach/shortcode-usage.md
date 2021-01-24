---
title: 'Shortcode usage'
date: '2019-11-07T05:54:40+00:00'
weight: 11
---

##### GS Coach’s shortcode usage

```
<span>[gs_coaches theme="gs_coach_grid_1"]</span>
```

##### GS Coach’s Shortcode attributes Usage

```
<span>[gs_coaches num="6" theme="gs_coach_grid_1" cols="6" group="web-development" cats_name="none" desc_limit="100" order="DESC" orderby="date"]</span>
```

Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_coaches theme="gs_coach_grid_1"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Coaches in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_coaches num="6" theme="gs_coach_grid_1" cols="6" group="web-development" cats_name="none" desc_limit="100" order="DESC" orderby="date"]' ); ?>
```

<div class="table-responsive"><table class="table table-bordered"><tbody><tr><th>No.</th><th>Attribute</th><th>Default value</th><th>options</th><th>Description</th></tr><tr><td>1</td><td>num</td><td>-1</td><td>-1 for all or any number</td><td>By default it’ll display all the Coaches but you can control it by *num* attribute.</td></tr><tr><td>2</td><td>theme</td><td>gs\_coach\_grid\_1</td><td>gs\_coach\_grid\_1   
 gs\_coach\_grid\_2   
 gs\_coach\_grid\_3   
 gs\_coach\_circle\_1   
 gs\_coach\_circle\_2   
 gs\_coach\_circle\_3   
 gs\_coach\_circle\_4   
 gs\_coach\_horizontal\_1   
 gs\_coach\_horizontal\_2   
 gs\_coach\_horizontal\_3   
 gs\_coach\_horizontal\_4   
 gs\_coach\_horizontal\_5   
 gs\_coach\_horizontal\_6   
 gs\_coach\_list\_1   
 gs\_coach\_list\_2   
 gs\_coach\_list\_3   
 gs\_coach\_list\_4   
 gs\_coach\_card\_1   
 gs\_coach\_card\_2   
 gs\_coach\_table\_1   
 gs\_coach\_table\_2   
 gs\_coach\_table\_3   
 gs\_coach\_grey\_1   
 gs\_coach\_grey\_2   
 gs\_coach\_slider\_1   
 gs\_coach\_slider\_2   
 gs\_coach\_slider\_3   
 gs\_coach\_popup\_1   
 gs\_coach\_filter\_1</td><td>Select preferred theme to display Coaches</td></tr><tr><td>3</td><td>cols</td><td>3(4 columns)</td><td>6 (2 Columns)   
4 (3 columns)  
3 (4 columns)</td><td>Number of column/s to display coaches. Columns are based on 12 grids Bootstarp, so follow columns value</td></tr><tr><td>4</td><td>group</td><td>all</td><td>Coach category slug, comma separated.</td><td>To get your category slug, go to GS Coach -&gt; Coach Group. Here you will find Coach Groups &amp; all the slugs</td></tr><tr><td>5</td><td>cats\_name</td><td>intitial</td><td>none</td><td>If you display only one category’s data then no need to display category names for filtering, passing the ‘none’ value will hide the filtering section. Applicable for *gs\_coach\_filter\_1*</td></tr><tr><td>6</td><td>desc\_limit</td><td>100</td><td>Any Number</td><td>Set maximum number of characters in Coach details. Default 100</td></tr><tr><td>7</td><td>order</td><td>DESC</td><td>DESC  
ASC</td><td>Normally Coaches will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass ```
order="ASC"
```

 parameter

</td></tr><tr><td>8</td><td>orderby</td><td>date</td><td>ID   
 title   
 modified   
 rand</td><td>Use preffered orderby attribute</td></tr></tbody></table>

</div>