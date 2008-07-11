=== Plugin Name: What they want === 
Stable tag:1.2
Contributors: Tomas.Zhu
Plugin URI: http://makefun.cn/what-they-want
Author URI: http://makefun.cn/
Donate link: http://makefun.cn/what-they-want
Tags:content,keywords,related,url,google,yahoo,baidu,search,posts,ajax,plugin,want
Requires at least: 2.2.3
Tested up to: 2.5.1



Copyright (c) 2008
Released under the GPL license
http://www.gnu.org/licenses/gpl.txt


== Description ==

Hello,It is difficult to find out what you want from huge internet,visitors are impatient to visit all of your site to find out what they really want.So,we should help visitors to find out what they want.

The plugin "What they want" will help you do it easier.
You can get newest version and support at here:
http://makefun.cn/what-they-want

If visitors find your site from a search engine,We can know what they want,for example:"joke"?,We cab help he find out something more about "joke" in our site.Now,the plugin can recognise 80 search engines.
You can get the demo here:
http://www.google.com/search?hl=en&newwindow=1&q=roboconvert+Your+BMW+into+a+robot&btnG=Search

== Installation ==

1:Upload the file whattheywant to the `/wp-content/plugins/` directory

2:Activate the plugin through the ¡®Plugins¡¯ menu in WordPress

== usage ==

There have two method it the plugin "what they want".

A:We just use google api,It will not occupy your hosting resource,But your visitor must use javascript.
What you need to do just copy these code to anywhere you want,I had wrote css in code:

<?php
if (function_exists(¡¯makefun_active¡¯)) whattheywantmore()
?>

(I recommend you copy it to single.php¡­.)

B:Find out what they want from your mysql database,what you need to do just copy these code to your page:

<?php
if (function_exists('makefun_active')) whattheywantmore_404()
?>

(I recommend you copy it to your 404.php,because It will occupy your hosting resource,you can just use it when something wrong happend in search engine)

For speed up query and reduce the press of your hosting,I had optimize the query by two method:
1:You can select "Create a fulltext index to speed up query performance" option in "setting" at "admin area" after active this plugin.(I recommend you backup your database first)

2:you can select "optimize your query performance?",It can optimize your query performance.
If you have any idea,tell me,thanks!

Best,

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