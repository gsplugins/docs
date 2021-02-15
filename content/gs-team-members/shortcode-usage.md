---
title: 'Shortcode Usage'
date: '2019-11-06T11:45:26+00:00'
weight: 20
---
##### GS Team Member’s shortcode usage

```
<span>[gs_team theme="gs_tm_theme5"]</span>
```

##### GS Team Member’s Shortcode attributes Usage

```
<span>[gs_team num="10" cols="3" theme="gs_tm_theme8" group="hr"]</span>
```

Shortcode PHP Usage

```
```

Template Usage – Add the shortcode anywhere you need to display GS Team Member in template files (header.php, front-page.php, etc.)

```
```

<div class="table-responsive"><table class="table table-bordered"><tbody><tr><th>No.</th><th>Attribute</th><th>Default value</th><th>options</th><th>Description</th></tr><tr><td>1</td><td>num</td><td>-1</td><td>-1 for all or any number</td><td>By default it’ll display all the Team Members but you can control it by *num* attribute.</td></tr><tr><td>2</td><td>order</td><td>DESC</td><td>DESC   
 ASC</td><td>Normally Membersw will display by descending order, latest will show first. But if you wish to display ascending order, oldest at first then pass ```
order="ASC"
```

parameter

</td></tr><tr><td>3</td><td>orderby</td><td>date</td><td> ID   
 title   
 modified   
 rand</td><td>Use preffered orderby attribute</td></tr><tr><td>4</td><td>group</td><td>all</td><td>Team category slug, comma separated.</td><td>To get your category slug, go to GS Team -&gt; Team Group. Here you will find Team Groups &amp; all the slugs</td></tr><tr><td>5</td><td>theme</td><td>gs\_tm\_theme1</td><td>gs\_tm\_theme1   
 gs\_tm\_theme2   
 gs\_tm\_theme3   
 gs\_tm\_theme4   
 gs\_tm\_theme5   
 gs\_tm\_theme6   
 gs\_tm\_theme7   
 gs\_tm\_theme8   
 gs\_tm\_theme9   
 gs\_tm\_theme10   
 gs\_tm\_theme11   
 gs\_tm\_theme12   
 gs\_tm\_theme13   
 gs\_tm\_theme14   
 gs\_tm\_theme15   
 gs\_tm\_theme16   
 gs\_tm\_theme17   
 gs\_tm\_theme18   
 gs\_tm\_theme19   
 gs\_tm\_theme20   
 gs\_tm\_grid2   
 gs\_tm\_drawer2 </td><td>Select preferred theme to display Members</td></tr><tr><td>6</td><td>cols</td><td>3(4 columns)</td><td>6 (2 columns)   
 4 (3 columns)   
 3 (4 columns)</td><td>Columns are based on 12 grids Bootstarp, so follow columns value</td></tr><tr><td>7</td><td>cats\_name</td><td>intitial</td><td>none</td><td>If you display only one category’s data then no need to display category names for filtering, passing the ‘none’ value will hide the filtering section. Applicable for *gs\_tm\_theme9*</td></tr><tr><td>8</td><td>panel</td><td>right</td><td>right   
 left   
 center</td><td>If you wish to display Team Members by custom order use mentioned shortcode, for custom order *orderby=”menu\_order”* is mandatory. ```
[gs_team cols="3" theme="gs_tm_theme1" orderby="menu_order"]
```

</td></tr></tbody></table>

</div>