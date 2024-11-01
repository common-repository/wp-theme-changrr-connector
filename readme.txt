=== WP Theme Changrr Connector ===
Contributors: dailyinvention
Donate link: 
Tags: theme, themes, changing, xmlrpc, mobile, android, connector, app, xml
Requires at least: 3.3
Tested up to: 3.5.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Change your WordPress theme with the click of a button on an Android device!

== Description ==

This plugin is a connector for the WP Theme Changrr Android app and is required to be activated on your site in order to enable theme switching. This plugin does not currently work with WordPress Multisite, although if there are enough requests, it may be developed.

The WP Theme Changrr Android app allows a user to quickly switch between their WordPress site themes.  The app can be downloaded from the Google Play store [here](http://bit.ly/13py3XF). You can also demo the app on the WP Theme Changrr promo site by downloading it to your mobile device and trying out the default blog loaded in the app. It will change the theme for [https://themechangrr.dailyinvention.com](https://themechangrr.dailyinvention.com).

This app is beneficial to WordPress site owners and Designer/Developers that want to access or give access to a user, so that they can easily switch their themes. An example would be a designer that has developed a Christmas theme for a client wants their client the ability to switch themes without too much hassle. They install the plugin on their WP installation, give their client an editor account, and give them the necessary credentials to connect. The client switches the theme come Christmas time with little fuss on their phone/tablet.

== Installation ==

1. Upload `wp-theme-changrr-connector.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently asked questions ==

= How do I connect my mobile app to my WordPress site? =

Upload and activate the plugin on your site.  Then, in the app, add the base WordPress URL (i.e. http://mysite.com) and the username and password of a user that can access Wordpress.

= Who can switch the themes? =

Any WordPress user that is either an Administrator or an Editor can switch themes.  If you do not have an Editor user, it is suggested to create one and use that account to connect.

= Where can I see an example of this? =

Go to [https://themechangrr.dailyinvention.com](https://themechangrr.dailyinvention.com) and test out the default blog that came with the app.  It will switch the themes.

= Does this plugin currently support Wordpress Multisite? =

No, but if there enough demand for it, something like that may be available in the future.


== Screenshots ==

1. This is the main page of WP Theme Changrr application, this is where you can switch themes or select different blogs.
2. This is the section of the app where you would enter the name, url, and login information of your Wordpress site.  You must have this connector activated on your site for switching to work.

== Changelog ==

= 1.0 =
* Added editor user privileges.
* Retrieves active theme.

== Upgrade notice ==

= 1.0 =
* Base version install.
