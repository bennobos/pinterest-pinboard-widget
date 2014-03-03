# Pinterest Pinboard Widget

A simple must-have widget for the Pinterest addict! Displays thumbnails of your latest Pinterest pins on your website.

## Description

This plugin adds your favorite pins much like the pinboards on Pinterest. It uses the original thumbnails from Pinterest itself. The plugin aims to have the same look and feel as the pinboords on Pinterest. To improve your site's performance, the pins are cached every 15 minutes.

The Pinterest Pinboard can be used as a widget in your sidebar or on any page using the shortcode.

## Get Involved

* Development and pull requests [on GitHub](https://github.com/codefishnl/wordpress-pinterest-pinboard-widget)
* Bug reports and suggestions on [WordPress.org forums](http://wordpress.org/support/plugin/pinterest-pinboard-widget)

## Installation

1. Upload the folder pinterest-pinboard-widget and its contents to the /wp-content/plugins/ directory or use the wordpress plugin installer
1. Activate the plugin through the 'Plugins' menu in WordPress
1. A new "Pinterest Pinboard" widget will be available under Appearance > Widgets.
1. Add it to your sidebar and edit settings, or use the following shortcode on your page to display the pins `[pinterest_pinboard username="pinterest"]`.

## Frequently Asked Questions

### My latest pins are not showing on my website

The Pinterest Pinboard Widget caches the RSS feed from Pinterest itself every 15 minutes. This improves loading time of your website, but may show a new pin with a slight delay. A just added pin also takes some time to show up in Pinterest's RSS feed.

### Can I disable caching?

In the current version caching is always enabled (15 minutes). Future versions of the plugin will allow you to set the caching interval or disable caching completely.

### Can I add a Follow Me button?

The current version show a 'more pins' link only. Future versions of the plugin will have more choices of buttons provided by Pinterest.

### I want to add a Pinboard to a page. Is this possible?

Yes, since verson 1.0.5 the plugin support a shortcode `pinterest_pinboard`. The following argument can be supplied:

* username: The pinterest username to retrieve the pins for
* rows: Nr. of rows of pins to display
* cols: Nr. of columns of pins to display
* new_window: Either 0 (open url in same window) or 1 (open url in new window)

Some examples of the shortcode uses are below. Retrieve 9 pins for user pinterest:

`[pinterest_pinboard username="pinterest" rows=3 cols=3]`

Retrieve 30 pins for user pinterest and open links in a new window:

`[pinterest_pinboard username="pinterest" rows=3 cols=10 new_window=1]`

## Screenshots

1. Settings of the widget under: Appearance > Widgets !
[widget settings](https://github.com/codefishnl/wordpress-pinterest-pinboard-widget/blob/master/screenshot-1.jpg)

1. This is the Pinterest Pinboard widget in the sidebar of the Twenty Eleven WordPress theme
[widget preview](https://github.com/codefishnl/wordpress-pinterest-pinboard-widget/blob/master/screenshot-2.jpg)
