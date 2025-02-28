=== ThemeLoom Widgets ===
Contributors: livinogs
Donate link: http://livingos.com/
Tags: widgets, posts, pages, query, responsive, twitter, flickr, facebook
Requires at least: 4.2
Tested up to: 4.9.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A set of useful widgets created for adding more fluid content to any theme. Includes widgets for showing posts, pages, as well as Facebook and Twitter feeds.

== Description ==

A set of useful widgets created for adding more fluid content to any theme. Especially designed for responsive themes. Also has a very useful shortcode for using some of the functionality inside a post or page. The plugin adds a set of new widgets, including:

*	Show Posts Widget - for showing posts excerpts, thumbs and post formats.
*	Show Pages Widget" - Shows thumbs/excerpts of child pages of defined parent page.
*	flickr Widget - Show flickr thumbs
*	Twitter Widget - show your latest tweets
*	Facebook Widget - show your facebook page feed without slowing your site down and in a responsive way!

And also adds a powerful shortcode for using the show posts/pages functionality in a post or page.

e.g.

[los_showposts post_type="posts" columns="3" content="true" heading="true" cat_id="" num_posts="3" ]

= Shortcode Parameters =

* Attribute - Description	Values
* post_type	- Type of query	"pages" or "posts"
* cat_id - Category ID for posts	e.g. "23"
* exclude_cats - post categories ids to exclude	e.g. "23,170,9"
* num_posts	- Number of items to show	e.g. "5?
* columns - Number of columns to layout	"1", "2", "3" or "4"
* heading - Show headings	"true" or "false"
* author - Show author link	"true" or "false"
* tags - Show tags	"true" or "false"
* categories - Show categories	"true" or "false"
* thumbs - Show Post thumbnails	"true" or "false"
* dates - Show Post Dates	"true" or "false"
* content - Show post/page excerpt	"true" or "false"
* parent_id - When showing pages, show children of this parent page.	e.g. "34"
* thumbsize - Image size to use	use "widget" or "gallery"
* entrytag - Heading tag for each item	e.g. "h3"
* post_formats - Show post format icons	"true" or "false"
* post_class - CSS class string to use for each item	default is "los-custom-post"
* show_sticky - Set to "1" to enable sticky posts function, "0" is deafult (i.e. sticky is ignored)

= More Information =

For further information see [ThemeLoom](http://themeloom.com/ "The ThemeLoom")

= Thanks =
* to Andrew Kurtis for Spanish language files

== Installation ==


1. Upload the contents of zip file to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. The new set of widgets will be available in Appearance->Widgets


== Frequently Asked Questions ==

for further information see [ThemeLoom](http://themeloom.com/ "The ThemeLoom")

== Screenshots ==

1. The Show Posts widget options.
2. Facebook widget options.
3. Example facebook front end.

== Changelog ==

= 1.8.5 =
* fixed facebook like count not showing

= 1.8.4 =
* fixed for new facebook api version

= 1.8.3 =
* updated deprecated functions
* fixed margin on mobile columns

= 1.8.2 =
* fixed links in fb feed

= 1.8.1 =
* fixed missing fields in fb feed

= 1.8 =
* fixed issue with api 2.4

= 1.7 =
* Updated to latest facebook api

= 1.6 =
* Added page feed option to show all or only Page's posts in feed
* Now clears cache on widget save
* Cache expire period now editable in widget

= 1.5 =
* Added Spanish language files (thanks to Andrew Kurtis)

= 1.4 =
* Small fix for Facebook widget

= 1.3 =
* Added option to exclude post categories and a exclude_cats shortcode parameter.

= 1.2 =
* Added a Facebook widget using Graph API

= 1.1 =
* Switched Twitter widget to use new API. Now requires api keys.

= 1.0 =
* First release.

== Upgrade Notice ==

= 1.0 =
Use it!