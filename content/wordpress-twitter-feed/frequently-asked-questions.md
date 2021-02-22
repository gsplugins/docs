---
title: 'Frequently Asked Questions'
date: '2019-11-07T07:16:02+00:00'
weight: 8
---
**How can I get Twitter Application API Key, API Secret, Account Access Token &amp; Account Access Token Secret?**  
Please sign in with your account and create an app on Twitter through this link: <https://dev.twitter.com/apps> and get your own Keys to add.

  
**How to use shortcode inside page templates?**  
WordPress has a great function, <code>do_shortcode()</code>, that will allow you to use shortcodes inside your theme files. For example, to output Tweets in a Theme file, you would do this: 

```
<?php echo do_shortcode('[gs_tweet username="wordpress" theme="gstf_theme1"]'); >
```