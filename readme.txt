=== Is user premium ===
Contributors: Vesuvium, Ariacorporate
Tags: PayPal, subscription, custom user meta
Requires at least: 4.0
Tested up to: 4.0
Stable tag: 0.3.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Is user premium is a small plugin that implements PayPal subscribtions management through user meta.

== Description ==

Is user premium adds:

* A user custom meta that keeps track of the subscription expiration
* A shortcode that displays the plugin output
* A settings/documentation page

All the configuration is done through the shortcode parameters.


The shortcode will display either:

* A 'please login' message to anonimous users
* A subscribe button to registered users
* A subscribed message for subscribed users
* A 'you were subscribe until' for expired subscription
Depending on the user. The outputted messages are customizable.

For the PayPal button:
Some currencies (usd, eur, jpy, cad, aud) are supported.
Various languages are supported and most buttons are supported.

Note that the shortcode will require some parameters, such as the merchant email, in order
to work properly (see the plugin settings page).

Simply put the shortcode, with the desired parameters, in the page that you want to use as subscription
page.

You can see (and edit) the subscriptions expirations in the users management page.

== Installation ==

Upload the zip file using the Wordpress plugin installer or by uploading the zipped plugin.
No other configuration is required.


== Frequently Asked Questions ==

= Is it possible to display more buttons in a page? =

Yes, it is. You can add more buttons, but the plugin only register the expiration date for
one item, so in case of a double subscription to different services, you will get problems.


== Screenshots ==

1. Settings page (first part)
2. Settings page (second part)
3. The button displayed to a logged-in user


== Changelog ==

= 0.3.3 =

* Added support for danish, russian and portoguese buttons
* Added support for british pound, russian rubles and danish crown.

= 0.3.2 =

* Fixed an error with currency codes

= 0.3.1 =

* Fixed shortcodes not working

= 0.3 =

* Added support for more languages and buttons type, for the paypal button

= 0.2 =

* Renamed 0.1.1 to 0.2

= 0.1.1 =

* Fixed broken paypal image
* Added screenshots
* Improved readme.txt

= 0.1 =

* Initial version
