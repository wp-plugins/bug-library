=== Bug Library ===
Contributors: jackdewey
Donate link: http://yannickcorner.nayanna.biz/wordpress-plugins/bug-library
Tags: bug, issue, tracker, manager, enhancement, feature, request, page, feature, custom, posts, type
Requires at least: 3.0
Tested up to: 3.2
Stable tag: trunk

This plugin provides an easy way to incorporate a bug/enhancement tracking system to a WordPress site. By adding a shortcode to a page, users will be able to display a bug list and allow visitors to submit new bugs / enhancements. The plugin will also provide search and sorting capabilities. A captcha and approval mechanism will allow the site admin to avoid spam. 

== Description ==

This plugin provides an easy way to incorporate a bug/enhancement tracking system to a WordPress site. By adding a shortcode to a page, users will be able to display a bug list and allow visitors to submit new bugs / enhancements. The plugin will also provide search and sorting capabilities. A captcha and approval mechanism will allow the site admin to avoid spam. 

* [Changelog](http://wordpress.org/extend/plugins/bug-library/other_notes/)
* [Support Forum](http://wordpress.org/tags/bug-library)

== Installation ==

1. Download the plugin
1. Upload the extracted folder to the /wp-content/plugins/ directory
1. Activate the plugin in the Wordpress Admin
1. To get a basic Bug Library list showing on one of your Wordpress pages, create a new page and type the following text: [bug-library]
1. Configure the Bug Library General Options section for more control over the plugin functionality.
1. Copy the file single-bug-library-bugs.php from the bug-library plugin directory to your theme directory to display all information related to your bugs. You might have to edit this file a bit and compare it to single.php to get the proper layout to show up on your web site.

== Changelog ==

= 1.0.2 =
* Corrected variable with bad name

= 1.0.1 =
* Added filters in admin bug list page to filters bugs by type, status and product
* Corrected problem with product, status and type getting deleted if you quick edited a bug

= 1.0 =
* First release of Bug Library

== Frequently Asked Questions ==

None at this time

== Screenshots ==

1. Bug Listing
2. Form to report new issues