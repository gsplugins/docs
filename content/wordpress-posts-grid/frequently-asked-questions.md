---
title: 'Frequently Asked Questions'
date: '2019-11-07T06:49:30+00:00'
weight: 8
---
**What will be Posts Feature image dimension?**  
Recommended image size larger than 420px for perfect view on various devices.

**Do I need to regenerate thumbnail images of existing posts?**  
Yes. But it is optional. You can use *Force Regenerate Thumbnails* plugin or any other plugin of your choice.

**How to use shortcode inside page templates?**
WordPress has a great function, do_shortcode(), that will allow you to use shortcodes inside your theme files. For example, to output Courses in a Theme file, you would do this: 
```
<?php echo do_shortcode('[gs_wpposts theme="gs_wppost_grid_1"]'); ?>
```