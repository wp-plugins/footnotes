=== Plugin Name ===
Contributors: Aricura, mark.cheret
Tags: footnote, footnotes, bibliography, formatting, notes, Post, posts, reference, referencing
Requires at least: 3.9
Tested up to: 3.9.1
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html
Stable Tag: 1.2.0

== Description ==

**footnotes** aims to be the all-in-one solution for displaying an automatically generated list of references on your Page or Post. The Plugin ships with a set of sane defaults but also gives the user control over how their footnotes are being displayed.
**footnotes** gives you the ability to display decently-formated footnotes on your WordPress Pages or Posts (those footnotes we know from offline publishing).

= Main Features =
- Fully customizable **footnotes** shortcode
- Decide, where your **footnotes** are displayed (position of the *Reference Container*)
- Responsive *Reference Container*
- Mouse-Over Box with clickable links displays your **footnotes** text
- Automatic numbering of your **footnotes**
- Choose from a list of symbols to represent your **footnotes**
- Display the **footnotes** *Reference Container* inside a Widget
- Button in both the Visual and the Text editor
  - Add **footnotes** into your Page / Post with ease of use by selecting your text and clicking the button
  
= Example Usage =
This is an example. Please note, that you can customize the shortcode you want to use.

1. Your awesome text((with an awesome footnote))
2. Your awesome text[ref]with an awesome footnote[/ref]
3. Your awesome text`<fn>`with an awesome footnote`</fn>`
4. Your awesome text `custom-shortcode` with an awesome footnote `custom-shortcode`

The current version is available on wordpress.org:
http://downloads.wordpress.org/plugin/footnotes.zip

Development of the plugin is an open process. Latest code is available on wordpress.org, please report feature requests and bugs on GitHub:
https://github.com/media-competence-institute/footnotes

== Frequently Asked Questions ==

= Is your Plugin a copy of footnotes x? =

No, this Plugin has been written from scratch. Of course some inspirations on how to do or how to not do things were taken from other plugins.

== Installation ==
- Visit your WordPress Admin area
- Navigate to `Plugins\Add`
- Search for **footnotes** and find this Plugin among others
- Install the latest version of the **footnotes** Plugin from WordPress.org
- Activate the Plugin

== Screenshots ==
1. Find the footnotes plugin in the Settings Menu
2. Settings for the *References Container*
3. Settings for **footnotes** styling
4. Settings for **footnotes** love
5. Other Settings
6. The HowTo section in the **footnotes** settings
7. Here you can see the **footnotes** Plugin at work. Isn't that plain beautiful?

== Changelog ==

= 1.2.1 =
- Bugfix: HowTo example will be displayed correctly if a user defined short code is set

= 1.2.0 =
- Feature: New button in the WYSIWYG editor and in the plain text editor to easily implement the footnotes tag
- Feature: Icon for the WYSIWYG-editor button
- Feature: Pre defined footnote short codes
- Experimental: User defined short code for defining footnotes
- Experimental: Plugin Widget to define where the reference container should appear when set to "widget area"
- Update: Moved footnotes 'love' settings to a separate container
- Update: Translation for new settings and for the Widget description
- Bugfix: Setting for the position of the "reference container" works for the options "footer", "end of post" and "widget area"

= 1.1.1 =
- Feature: Short code to not display the 'love me' slug on specific pages ( short code = [[no footnotes: love]] )
- Update: Setting where the reference container appears on public pages can also be set to the widget area
- Add: Link to the wordpress.org support page in the plugin main page
- Update: Changed plugin URL from GitHub to WordPress
- Bugfix: Uninstall function to really remove all settings done in the settings page
- Bugfix: Load default settings after plugin is installed
- Update: Translation for support link and new setting option
- Add: Label to display the user the short code to not display the 'love me' slug

= 1.1.0 =
- Update: Global styling for the public plugin name
- Update: Easier usage of the public plugin name in translations
- Update: New Layout for the settings page to group similar settings to get a better overview
- Update: Display settings submit button only if there is at least 1 editable setting in the current tab
- Add: Setting where the reference container appears on public pages (needs some corrections!)
- Bugfix: Displays only one reference container in front of the footer on category pages

= 1.0.6 =
- Bugfix: Uninstall function to delete all plugin settings
- Bugfix: Counter style internal name in the reference container to correctly link to the right footnote on the page above
- Bugfix: Footnote hover box styling to not wrap the footnote text on mouse over
- Update: 'footnotes love' text in the page footer if the admin accepts it and set its default value to 'no'

= 1.0.5 =
- The Plugin has been submitted to wordpress.org for review and (hopefully) publication.
- Update: Plugin description for public directories (WordPress.org and GitHub)
- Feature: the footnotes WordPress Plugin now has its very own CI
  - Update: Styling
  - Update: Settings to support the styling
- Add: Inspirational Screenshots for further development
- Add: Settings screenshot
- Update: i18n fine-tuning

= 1.0.4 =
- Update: replacing function when footnote is a link (bugfix)
- Footnote hover box remains until cursor leaves footnote or hover box
- Links in the footnote hover box are click able
- Add: setting to allow footnotes on Summarized Posts
- Add: setting to tell the world you're using footnotes plugin
- Add: setting for the counter style of the footnote index
  - Arabic Numbers (1, 2, 3, 4, 5, ...)
  - Arabic Numbers leading 0 (01, 02, 03, 04, 05, ...)
  - Latin Characters lower-case (a, b, c, d, e, ...)
  - Latin Characters upper-case (A, B, C, D, E, ...)
  - Roman Numerals (I, II, III, IV, V, ...)
- Add: a link to the WordPress plugin in the footer if the WP-admin accepts it
- Update: translations for the new settings
- Switch back the version numbering scheme to have 3 digits

= 1.0.3 =
- Add: setting to use personal starting and ending tag for the footnotes
- Update: translations for the new setting
- Update: reading settings and fallback to default values (bugfix)

= 1.0.2 =
- Add: setting to collapse the reference container by default
- Add: link behind the footnotes to automatically jump to the reference container
- Add: function to easy output input fields for the settings page
- Update: translation for the new setting

= 1.0.1 =
- Separated functions in different files for a better overview
- Add: a version control to each file / class / function / variable
- Add: layout for the settings menu, settings split in tabs and not a list-view
- Update: Replacing footnotes in widget texts will show the reference container at the end of the page (bugfix)
- Update: translations for EN and DE
- Changed version number from 3 digits to 2 digits

= 1.0.0 =
- First development Version of the Plugin

== Upgrade Notice ==
to upgrade our plugin is simple. Just update the plugin within your WordPress installation.
To cross-upgrade from other footnotes plugins, there will be a migration assistant in the future
