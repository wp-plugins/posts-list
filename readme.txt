=== Posts List ===
Contributors: wokamoto
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=9S8AJCY7XB8F4&lc=JP&item_name=WordPress%20Plugins&item_number=wp%2dplugins&currency_code=JPY&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted
Tags: archive, list, navigation, page, posts, short code
Requires at least: 3.0
Tested up to: 3.2.1
Stable tag: 0.4.1

Adds a posts (or pages) list of your blog pages (or posts) by entering the shortcode [posts-list].

== Description ==

Adds a posts (or pages) list of your blog pages (or posts) by entering the shortcode [posts-list].

First example shows how to add the posts list in its simplest form.
`[posts-list]`

Example shortcode will add a pages list to a page.
`[posts-list type=page]`

Example shortcode will add a posts list to a page displaying a year 2011 and 2010.
`[posts-list year="2011,2010"]`

Example shortcode will add a posts list to a page displaying a category id 10 and 11.
`[posts-list category="10,11"]`

Example display ONLY the title.
`[posts-list date_format=FALSE]`

== Installation ==

1. Upload the entire `posts-list` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Add the shortcode `[posts-list]` to the page(s) of your choice.

= options =

* type : post, page, attachment ( default : post )
* sort : desc or asc ( default : desc )
* style : ul, ol, dl, table, div p ( default : ul )
* date_format : see [PHP date format](http://jp.php.net/manual/en/function.date.php)
* year : filtering year
* month : filtering month
* category : filtering category id


== Changelog == 

**0.4.1 - Sep. 14, 2011**  
Added option, "display ONLY the title".

**0.4.0 - Jan. 14, 2011**  
Initial release.
