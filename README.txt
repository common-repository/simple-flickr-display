=== Simple Flickr Display ===
Contributors: wolfpaw
Donate link: https://davidwolfpaw.com/
Tags: flickr, images
Requires at least: 3.1
Tested up to: 5.8.0
Stable tag: 1.4
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

Display recent photos from your Flickr feed in your sidebar.

== Description ==

This widget uses the Flickr API to pull the most recent images that a user has uploaded. Simply type the Flickr username and number of photos that you would like to display and the plugin does the rest!

= Options that can be set: =
* Widget Title
* Flickr User
* Number of Photos to display
* Size of Photos to display

== Installation ==

1. Upload the files to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place `Flickr Display` onto a sidebar on the Appearance->Widgets page
4. Input your Flickr username and the number of photos that you would like to display

== Frequently Asked Questions ==

= Can I choose a specific photoset or gallery? =

Not currently. This plugin pulls the most recent uploads that the chosen user has made to Flickr only.


== Changelog ==

= 1.4 =
* adds small/large square size selector
* adds translation file

= 1.3 =
* updates `widget_init` for PHP v7.0+
* Cleans code syntax for WPCS
* Adds proper `rel` tag for links
* Updates CSS for theme defaults

= 1.2 =
* Display formatting with flexbox
* Fixed PHP error thrown for incorrect username
* Title attribute added to images

= 1.1 =
* Clarification on public user profiles
* Formatting of widget inputs updated

= 1.0 =
* First Version
