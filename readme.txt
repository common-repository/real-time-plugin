=== Realtime Plugin  ===
Contributors: Realtime.co (http://www.realtime.co)
Tags: realtime web, real, time, real time posts, xrtml
Requires at least: 2.0.2
Tested up to: 3.4
Stable tag: 4.3

== Description ==

This plugin uses the xRTML tecnology to update the page where the posts, post list, latest posts and shoutbox, are being visualised without the need for the viewers to refresh the page.

Here is how it works:

Our plugin is "listening" to messages from the ORTC server and, as soon as a post or comment is made, the ORTC server broadcasts this information to all the users browsing the website. The pages being viewed are then updated, in real time, without the need to refresh the page or perform AJAX calls.

For the shoutbox, the plugin works basically the same way: the ORCT manages the message broadcasts for all the users.

How xRTML and ORTC works in the plugin:
For the plugin be able to work, it's necessary to have an Application key, an Authorization token and a Private Key.
You can apply for a FREE Developper Account at http://www.realtime.co.

If you decide to keep using the plugin, you must then apply for a Regular Account at the same website.
In the administration of the plugin insert the Application key, Authorization token and Private Key provided by Realtime.co.

The plugin administration then establishes a connection to the ORTC server to send data, everytime a user posts a message or a comment. The ORTC server then broadcasts the message to the other users.

== Installation ==

1. Install `realtime.zip` in the administration area
2. Enter your Application key, Authorization token and Private Key.
3. Indicate the CSS class containers for Posts, Coments, Latest Posts, Shoutbox and Video Chat
4. Enter the index of the plugin

NOTE: your server must have curl options on your server activated

== Frequently Asked Questions ==

= Is the Regular Account Free? =

No. You should contact us through the website http://www.realtime.co about this. We provide very affordable licenses for small websites.

== Screenshots ==
screenshot1.jpg
screenshot2.jpg
== Upgrade Notice ==

= 1.0 =
* First version

== Changelog ==

= 1.0 =
* First version
