---
title: 'Shortcode Usage'
date: '2019-11-07T07:16:12+00:00'
weight: 9
---
##### GS Twitter Feed’s shortcode usage

```
[gs_tweet username="wordpress" theme="gstf_theme1"]
```

##### GS Twitter Feed’s Shortcode attributes Usage

```
[gs_tweet username="wordpress" tweet_number="10" theme="gstf_theme1" link="_blank"]
```

##### Shortcode PHP Usage

```
<?php echo do_shortcode( '[gs_tweet username="wordpress" theme="gstf_theme1"]' ); ?>
```

Template Usage – Add the shortcode anywhere you need to display GS Twitter Feed in template files (header.php, front-page.php, etc.)

```
<?php echo do_shortcode( '[gs_tweet username="wordpress" tweet_number="10" theme="gstf_theme1" link="_blank"]' ); ?>
```