=== Plugin Name: What they want === 
Stable tag:3.0
Contributors: Tomas.Zhu
Plugin URI: http://makefun.cn/what-they-want
Author URI: http://makefun.cn/
Donate link: http://makefun.cn/what-they-want
Tags:content,keywords,related,url,google,yahoo,baidu,search,posts,ajax,plugin,want,
Requires at least: 2.2.3
Tested up to: 3.0



Copyright (c) 2008
Released under the GPL license
http://www.gnu.org/licenses/gpl.txt


== Description ==

This plugin will show all related posts / pages/ archive which match your clients' search keyword. It can also show related posts for your regular client.
When your visitor come from search engine and read your posts, maybe it is not what they really want. In general, there are some related post plugin can help your client, but most of these related post plugin are not designed for visitor come from search engine and can not match the keyword which your client really want. So I write this plugin: "what they want" to help webmaster and their readers.

And you can test the demo here:
http://www.google.com/search?hl=en&newwindow=1&q=roboconvert+Your+BMW+into+a+robot&btnG=Search
(the first record should be makefun.cn/....)

You can get newest version and support at here:
http://makefun.cn/what-they-want

If visitors find your site from a search engine, We can know what they want, for example:"joke", We can help them find out something more about "joke" in our site. In the current, this plugin can recognise 80 search engines and we are working for supporting more search engines, also in night version, I am re-writing this plugin to support search box in your wordpress, actaully it should can search everything in your database.


== Installation ==

1: Upload the file whattheywant to the `/wp-content/plugins/` directory

2: Activate the plugin through the 'Plugins' menu in WordPress

== usage ==

There are two ways to use the plugin "what they want".

A: We will not search your database, we use google api to search your content from google, it would not occupy your hosting resource, But your visitor must use javascript. What you need do is just to copy these code to anywhere in your themes: 

<?php
if (function_exists('makefun_active')) whattheywantmore();
?>

In the current, I wrote css in plugin code, but I am re-writeing it into a single css file, so you can customize your style.

B: Find out "what they want" from your mysql database, what you need do is just to copy these code to your page: 

<?php
if (function_exists('makefun_active')) whattheywantmore_404();
?>

For speed up query and reduce the pressure of your hosting, I had added some options in plugin which will optimize the query by two method:
1: You can select "Create a fulltext index to speed up query performance" option in "setting" at "admin area" after active this plugin.

2: you can select "optimize your query performance?" option, It can optimize your query performance.
If you have any idea, tell me please, I'd like realize any of your requirement, thanks :)

Best Regars,

Tomas.zhu

plugin download:
whattheywant-1-2.txt

== Screenshots == 
in whatthey.zip 
or http://makefun.cn/what-they-want/

== Frequently Asked Questions ==
http://makefun.cn/what-they-want/

Demo:

http://www.google.com/search?hl=en&newwindow=1&q=roboconvert+Your+BMW+into+a+robot&btnG=Search