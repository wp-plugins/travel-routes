=== Travel Routes ===
Contributors: WebMaestro.Fr
Donate link: http://webmaestro.fr/blog/2012/travel-routes-wordpress-plugin/
Tags: travel, route, location, customizable, map
Requires at least: 3.4
Tested up to: 3.4.1
Stable tag: 1.0
License: GPLv2

(BETA) Display your travels on customizable maps !

== Description ==

Easily add geographical tags on a map when you write a post, and it will automatically create new countries and localities terms. You can also order those locations randomly or by date to define your routes.

Use the map as a widget, and pick your own colors to customize it. It is a SVG map that react to users actions (mouse over posts and terms links, click on route line...).

<a class="btn btn-info" href="http://webmaestro.fr/blog/travels/">See the demo</a> !

<div class="alert alert-info">This plugin is in <strong>BETA</strong>, I published it for tests, <a href="https://github.com/WebMaestroFr/Travel-Routes-Wordpress-Plugin" title="Github">contributions</a> and feedback.</div>

== Installation ==

1. Upload "travel-routes" directory to your "/wp-content/plugins/" directory
2. Activate the plugin through the "Plugins" menu in WordPress
3. Start attaching locations to your posts
4. Add the widget (the map) anywhere on your blog
5. Tell me what you think about it

== Frequently Asked Questions ==


== Screenshots ==

1. Easily add geographical tags on a map when you write a post, and it will automatically create new countries and localities terms. You can also order those locations randomly or by date to define your routes.
2. Use the map as a widget, and pick your own colors to customize it. It is a SVG map that react to users actions (mouse over posts and terms links, click on route line...).</a>.

== Changelog ==

= 0.2 =
* Fixed the JS bug on empty maps.

= 0.2 =
* Wrapping it with nice paper.
* Sharing it with you guys, but still some bugs to fix !

= 0.1 =
* First draft.

== Upgrade Notice ==

= 0.2 =
Give me feedback fellows !

= 0.3 =
Fixed the JS bug on empty maps.

== Known issues ==

An <code>OVER_QUERY_LIMIT</code> error from the <a href="https://developers.google.com/maps/documentation/geocoding/">Google Geocoding API</a> is showing up way too often. If any contributor could <a href="https://github.com/WebMaestroFr/Travel-Routes-Wordpress-Plugin/blob/master/admin.php#LC138">take a look at the insert_term() function</a>, that would be awesome.

`<?php code(); ?>`