=== Storefront Homepage Contact 7 Section - SHC7S ===
Contributors: WPDevHQ
Tags: woocommerce, ecommerce, storefront, contact, form, map, email, address
Requires at least: 3.5
Tested up to: 4.5
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Credits: woothemes, tiagonoronha
Attribution: Forked from [Storefront Homepage Contact Section] (https://wordpress.org/plugins/storefront-homepage-contact-section/)

The underlying code of this plugin is the same as attributed plugin above with modifications to suite the purpose.
Modifications done by Zulfikar Nore of @WPDevHQ

Add a "Contact Form 7" section to the Storefront homepage.

== Description ==

A simple plugin that adds custom "Contact Form 7" homepage section to Storefront. Customise the display by adding your contact details via the Customizer and a widget for extra info.

This plugin requires the Storefront theme to be installed. Contact Form 7 is required for the contact form.

== Installation ==

1. Upload `storefront-homepage-contact7-section` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Configure the display in the Customizer (look for the 'Homepage Contact' section).
4. Expand the panel, add your Contact Form 7 ID and title and save
5. Done!

== Frequently Asked Questions ==

= I installed the plugin but cannot see the "Contact" section =

This plugin will only work with the [Storefront](http://wordpress.org/themes/storefront/) theme.

= I can't see the contact form =

This plugin requires the [Contact Form 7](https://wordpress.org/plugins/contact-form-7/) plugin for the contact form to work.

= I can't see the Contact section on the front end =

If you are using the [Homepage Control] (https://wordpress.org/plugins/homepage-control/) plugin you may need to visit the Homepage Control section in the customizer and make sure the "Storefront Homepage Contact7 Section" is enabled.

== Screenshots ==

1. The Homepage Contact Section

2. Customizer enable section via Homepage Control panel.

== Changelog ==

= 1.0.1 =
Added check for "is_active_sidebar( 'shc7s-1' )" to render the left pane of the contact us section.

= 1.0.0 =
Initial release.