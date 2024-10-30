=== Plugin Name ===
Contributors: London Drum
Tags: london,event,events,listing,listings,plugin,widget,whatson,uk,theatre,music,art,exhibitions,gigs,concerts,shows
Requires at least: 2.8
Tested up to: 3.1.3
Stable tag: 3.0

Displays a constantly updating list of London events. There are 5 categories... everything from art exhibitions and concerts to theatre shows.

== Description ==

The 'London Events Guide' plugin will display a constantly updating list of events on whichever page you like. It has also been widgetized for drag-and-drop use on your sidebar.

There are five different categories of events to choose from: 'Art/Museum exhibitions', 'Classical music', 'Pick of the best', 'Rock and pop concerts' and 'Theatre shows'.

The listing can be styled to match your site using the CSS box that we have supplied in the admin section.

The listing will include a title, description and date for each event, alongside a picture for the venue. There are options to amend the date format, number of items displayed, and all of the CSS styles.

== Installation ==

1. Upload the `london-events-guide` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu
3. Navigate to 'Settings > London Events Guide' to configure the plugin
4. You can either drag the `London Events Guide` widget straight onto your sidebar, or you can place `<?php if (function_exists('london_events')) { london_events(); } ?>` into your template where you'd like the events to appear

== Upgrade ==

1. Delete the old `london-events-guide` folder
2. Upload the new `london-events-guide` folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu
4. Navigate to 'Settings > London Events Guide' to configure the plugin

== Frequently Asked Questions ==

= Where are the events taken from? =

The events are continually updated at the London Drum website -- http://www.londondrum.com/events/
We also have an application for Facebook users -- http://apps.facebook.com/london-events-guide/

= How do I uninstall the plugin? =

Simply delete the old `london-events-guide` folder, and remove the `<?php if (function_exists('london_events')) { london_events(); } ?>` line from your template file.

== Screenshots ==

1. This shows some of the events from an unstyled listing. You can amend the styles to match your site using the CSS box that we have supplied in the admin section. The list is fully customisable, as we have included options that allow changes to be made to the images, description and date format.
