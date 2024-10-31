=== No Skim ===
Contributors: dartiss
Tags: skimlinks, stop, suppress
Requires at least: 4.6
Tested up to: 4.9
Requires PHP: 5.3
Stable tag: 1.1.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Suppress Skimlinks on post or pages, whether the whole content or just a portion.

== Description ==

Skimlinks is a great way to easily monetize content by converting product links in your post into their equivalent affiliate links on-the-fly. Indeed, Skimlinks does a lot more than this. If you're not already signed up, [sign up here](http://go.skimlinks.com/?id=15437X720702&xs=1&url=http://skimlinks.com "Skimlinks")!

You can add Skimlink functionality to your site via code that they provide or  [their official plugin](https://wordpress.org/plugins/skimlinks/ "Skimlinks WordPress Plugin"). However, you may find that in some circumstances (e.g. a sponsored post) you may be asked to suppress any such advertising. Although Skimlinks provides a means to do this the functionality is not included in their plugin. Et voilà, this plugin does just that - where you need it to, it will suppress any Skimlink output on a page or post basis.

To use - and this is where it couldn't get simpler - just add the shortcode [noskim] around the content. For example...

`[noskim]Post or page contents where I don't want Skimlinks advertising[/noskim]`

Simple, eh?

Alternatively, if you wish to switch off Skimlinks for the entire post or page in one swift stroke, then look for the meta box within the editor screen named 'No Skim' and tick the option within it. Can't find the box? Read the FAQ for details.

Technical specification...

* Licensed under [GPLv2 (or later)](http://wordpress.org/about/gpl/ "GNU General Public License")
* Designed for both single and multi-site installations
* PHP7 compatible
* Fully internationalized, ready for translations. **If you would like to add a translation to this plugin then please head to our [Translating WordPress](https://translate.wordpress.org/projects/wp-plugins/[plugin folder] "Translating WordPress") page**
* WCAG 2.0 Compliant at AA level

Please visit the [Github page](https://github.com/dartiss/no-skim "Github") for the latest code development, planned enhancements and known issues.

== Installation ==

No Skim can be found and installed via the Plugin menu within WordPress administration (Plugins -> Add New). Alternatively, it can be downloaded from WordPress.org and installed manually...

1. Upload the entire `no-skim` folder to your `wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress administration.

Voila! It's ready to go.

== Frequently Asked Questions ==

= Can I use other shortcodes within the noskim shortcodes? =

Yep.

= Is this an official plugin from Skimlinks? =

No. I'm not affiliated with Skimlinks at all, just happy a happy user!

= Where do I find the No Skim box in the editor? =

Ok, assuming you're in the post or page editor then where it is depends on how you have the screen configured - it could be anywhere, to be honest, but usually appears somewhere beneath the main editor screen.

If you still can't find it, click on the "Screen options" tab in the top, right hand corner and ensure the "Code Embed" box is ticked - once it is, it will definitely be somewhere on your screen.

== Changelog ==

[Learn more about my version numbering methodology](https://artiss.blog/2016/09/wordpress-plugin-versioning/ "WordPress Plugin Versioning")

= 1.1.7 =
* Maintenance: Added Github links to plugin meta

= 1.1.6 =
* Maintenance: Minor tweaks to the README
* Maintenance: Removed donation links

= 1.1.5 =
* Maintenance: Minimum requirement for this plugin is now WP 4.6, so made changes to accommodate that
* Maintenance: Corrected links to my site
* Maintenance: Removed language files and options, due to new minimum requirements
* Maintenance: Updated this README to accommodate new plugin directory structure
* Enhancement: Now use Yoda conditions throughout the code

= 1.1.4 =
* Enhancement: After WP 4.6 you no longer need to load the text domains, so I don't!

= 1.1.3 =
* Maintenance: Updated branding, inc. adding donation links

= 1.1.2 =
* Maintenance: Updated the branding

= 1.1.1 =
* Maintenance: Added text domain and path

= 1.1 =
* Enhancement: A box has been added to the editor screen to allow you to simply suppress Skimlinks for the whole post/page via a single click. Good, eh?
* Enhancement: Added internationalization for our foreign usership (is that a word?)

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.1.7 =
* Added Github links