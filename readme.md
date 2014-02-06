<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# Stream

![Banner](assets/banner-1544x500.png)
Stream tracks logged-in user activity so you can monitor every change made on your WordPress site in beautifully organized detail.

**Contributors:** [x-team](http://profiles.wordpress.org/x-team), [shadyvb](http://profiles.wordpress.org/shadyvb), [fjarrett](http://profiles.wordpress.org/fjarrett), [jonathanbardo](http://profiles.wordpress.org/jonathanbardo), [johnregan3](http://profiles.wordpress.org/johnregan3), [akeda](http://profiles.wordpress.org/akeda), [kucrut](http://profiles.wordpress.org/kucrut), [topher1kenobe](http://profiles.wordpress.org/topher1kenobe), [powelski](http://profiles.wordpress.org/powelski)  
**Tags:** [actions](http://wordpress.org/plugins/tags/actions), [activity](http://wordpress.org/plugins/tags/activity), [admin](http://wordpress.org/plugins/tags/admin), [analytics](http://wordpress.org/plugins/tags/analytics), [dashboard](http://wordpress.org/plugins/tags/dashboard), [log](http://wordpress.org/plugins/tags/log), [notification](http://wordpress.org/plugins/tags/notification), [stream](http://wordpress.org/plugins/tags/stream), [users](http://wordpress.org/plugins/tags/users)  
**Requires at least:** 3.6  
**Tested up to:** 3.8.1  
**Stable tag:** trunk (master)  
**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)  

## Description ##

[![Play video on YouTube](http://i1.ytimg.com/vi/H9TnZMUE_Y8/hqdefault.jpg)](http://www.youtube.com/watch?v=H9TnZMUE_Y8)

**Note: This plugin requires PHP 5.3 or higher to be activated.**

Never be in the dark about WP Admin activity again. Stream allows you to know exactly when changes to your site have been made, and more importantly, who did them.

Every logged-in user action is logged in a user activity stream and organized for easy filtering by connector, context, action and IP address.

Built with performance in mind, Stream won't pollute your default posts table with records or slow down content querying on your site.

Stream is built to extend, allowing developers to easily build their own connectors to track any type of action in the activity stream (developer documentation coming soon).

**Recorded activity:**

 * Posts
 * Pages
 * Custom Post Types
 * Users
 * Themes
 * Plugins
 * Tags
 * Categories
 * Custom Taxonomies
 * Settings
 * Menus
 * Media Library
 * Widgets
 * Comments
 * WordPress Core Updates

**Noteworthy features:**

 * Dashboard widget of most recent user activity
 * Specify which roles should have their activity logged
 * Limit who can view user activity records by user role
 * Live update of user activity records in the Stream
 * Private RSS feeds of user activity records
 * Private JSON feeds of user activity records
 * Set how long records should live before being purged automatically
 * Option to manually purge all user activity records from the database

**Extension plugins:**

 * [Cherry-Pick](http://wordpress.org/plugins/stream-cherry-pick/): Allow Administrators to delete records from the Stream individually or in bulk.

**Languages:**

 * English
 * French
 * German
 * Spanish
 * Polish

**Coming soon:**

 * Multisite view of all activity records on a network
 * Support for IPv6 addresses
 * Language support for Arabic (RTL), Czech, Slovak and Indonesian

**See room for improvement?**

Great! There are several ways you can get involved to help make Stream better:

1. **Report Bugs:** If you find a bug, error or other problem, please report it! You can do this by [creating a new topic](http://wordpress.org/support/plugin/stream) in the plugin forum. Once a developer can verify the bug by reproducing it, they will create an official bug report in GitHub where the bug will be worked on.
2. **Suggest New Features:** Have an awesome idea? Please share it! Simply [create a new topic](http://wordpress.org/support/plugin/stream) in the plugin forum to express your thoughts on why the feature should be included and get a discussion going around your idea.
3. **Issue Pull Requests:** If you're a developer, the easiest way to get involved is to help out on [issues already reported](https://github.com/x-team/wp-stream/issues) in GitHub. Be sure to check out the [contributing guide](https://github.com/x-team/wp-stream/blob/master/contributing.md) for developers.

Thank you for wanting to make Stream better for everyone! We salute you.

[![Build Status](https://travis-ci.org/x-team/wp-stream.png?branch=master)](https://travis-ci.org/x-team/wp-stream)

## Screenshots ##

### Every logged-in user action is logged in the activity stream and organized for easy filtering and searching.

![Every logged-in user action is logged in the activity stream and organized for easy filtering and searching.](assets/screenshot-1.png)

### Enable live updates in Screen Options to watch your site activity flow into the Stream in real-time.

![Enable live updates in Screen Options to watch your site activity flow into the Stream in real-time.](assets/screenshot-2.png)

### Control which user roles have their activity tracked and which user roles can access Stream.

![Control which user roles have their activity tracked and which user roles can access Stream.](assets/screenshot-3.png)

### Enable private feed access for your activity Stream, determine how long records should live before being purged, or purge them from the database manually at any time.

![Enable private feed access for your activity Stream, determine how long records should live before being purged, or purge them from the database manually at any time.](assets/screenshot-4.png)

## Changelog ##

### 1.1.6 ###
**2014/02/06** - Small sortable columns bug fix on the records screen. Props [powelski](http://profiles.wordpress.org/powelski/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 1.1.5 ###
**2014/02/05** - Fixed a class scope bug [reported in the support forum](http://wordpress.org/support/topic/temporary-fatal-error-after-upgrade-113) that was causing a fatal error on some installs. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 1.1.4 ###
**2014/02/05** - Highlight changed settings field feature. DB upgrade routine for proper utf-8 charset. Various bug fixes. Props [powelski](http://profiles.wordpress.org/powelski/), [johnregan3](http://profiles.wordpress.org/johnregan3/), [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 1.1.3 ###
**2014/02/04** - Upgrade routine for IP column in DB. Serialized option parsing for Stream Settings records. Purge records immediately when TTL is set backwards in Stream Settings. Various bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [powelski](http://profiles.wordpress.org/powelski/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 1.1.2 ###
**2014/02/02** - Bug fix for list table notice on new installations. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 1.1 ###
**2014/01/31** - Disable terms in dropdown filters for which records do not exist. Props [johnregan3](http://profiles.wordpress.org/johnregan3/)

### 1.0.9 ###
**2014/01/31** - Several important bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 1.0.8 ###
**2014/01/30** - Bug fix for sites using BuddyPress. Props [johnregan3](http://profiles.wordpress.org/johnregan3/)

### 1.0.7 ###
**2014/01/29** - Code efficiency improvements when fetching admin area URLs. Props [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 1.0.6 ###
**2014/01/28** - Query improvements, default connector interface, hook added for general settings fields. Bug fixes. Props [dero](https://github.com/dero), [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 1.0.5 ###
**2014/01/27** - Bug fix for live updates breaking columns when some are hidden via Screen Options. Props [johnregan3](http://profiles.wordpress.org/johnregan3/)

### 1.0.4 ###
**2014/01/23** - Language pack for Polish. Bug fixes. Props [powelski](http://profiles.wordpress.org/powelski/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [johnregan3](http://profiles.wordpress.org/johnregan3/), [kucrut](http://profiles.wordpress.org/kucrut/)

### 1.0.3 ###
**2014/01/19** - Language pack for Spanish. Bug fixes. Props [omniwired](https://github.com/omniwired), [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 1.0.2 ###
**2014/01/15** - Ensure the dashboard widget repects the Role Access setting. Props [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 1.0.1 ###
**2014/01/15** - Require nonce for generating a new user feed key. Props [johnregan3](http://profiles.wordpress.org/johnregan3/)

### 1.0 ###
**2014/01/13** - Allow list table to be exensible. Hook added to prevent tables from being created, if desired. Props [johnregan3](http://profiles.wordpress.org/johnregan3/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/)

### 0.9.9 ###
**2014/01/08** - Updated screenshot assets and descriptions. Props [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.9.8 ###
**2014/01/01** - Support for live updates in the Stream. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [johnregan3](http://profiles.wordpress.org/johnregan3/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.9.7 ###
**2013/12/29** - Plugin version available as a constant. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.9.6 ###
**2013/12/29** - Use menu name as context in Menus connector. Warning if required DB tables are missing. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [topher1kenobe](http://profiles.wordpress.org/topher1kenobe/)

### 0.9.5 ###
**2013/12/22** - WordPress context added to Installer connector for core updates. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 0.9.3 ###
**2013/12/22** - Replacing Chosen library with Select2. Bug fixes. Props [kucrut](http://profiles.wordpress.org/kucrut/), [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.9.2 ###
**2013/12/22** - Added support for private feeds in JSON format. Flush rewrite rules automatically for feeds when enabled/disabled. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.9.1 ###
**2013/12/21** - Specify which roles should have their activity logged. Delete all options on uninstall. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.9 ###
**2013/12/20** - Added connector for Comments. Stream activity dashboard widget. UI enhancements. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [shadyvb](http://profiles.wordpress.org/shadyvb/), [topher1kenobe](http://profiles.wordpress.org/topher1kenobe/)

### 0.8.2 ###
**2013/12/19** - Language packs for French and German. Option to uninstall database tables. Bug fixes. Props [jonathanbardo](http://profiles.wordpress.org/jonathanbardo/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [topher1kenobe](http://profiles.wordpress.org/topher1kenobe/), [pascalklaeres](http://profiles.wordpress.org/pascalklaeres/)

### 0.8.1 ###
**2013/12/18** - Setting to enable/disable private feeds functionality. Additional record logged when a user's role is changed. Bug fixes. Props [fjarrett](http://profiles.wordpress.org/fjarrett/), [kucrut](http://profiles.wordpress.org/kucrut/), [topher1kenobe](http://profiles.wordpress.org/topher1kenobe/), [justinsainton](http://profiles.wordpress.org/justinsainton/)

### 0.8 ###
**2013/12/16** - Ability to query Stream records in a private RSS feed. Bug fixes. Props [fjarrett](http://profiles.wordpress.org/fjarrett/), [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 0.7.3 ###
**2013/12/13** - Bug fix for Role Access option. Props [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.7.2 ###
**2013/12/12** - Bug fixes for the Installer connector. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 0.7.1 ###
**2013/12/12** - Hotfix to remove PHP 5.4-only syntax. Role Access option added to Settings. Props [kucrut](http://profiles.wordpress.org/kucrut/)

### 0.7 ###
**2013/12/11** - Added connectors for Taxonomies and Settings. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.6 ###
**2013/12/09** - UX improvements to manual DB purge. Cron event for user-defined TTL of records. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.5 ###
**2013/12/08** - Require PHP 5.3 to activate plugin. Provide action links for records when applicable. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.4 ###
**2013/12/08** - Improved support for pages and custom post types. Chosen for filter dropdowns. Pagination support in screen options. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.3 ###
**2013/12/07** - Improved actions for Users context. Action for edited images in Media context. Bug fixes in Menus context. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [akeda](http://profiles.wordpress.org/akeda/)

### 0.2 ###
**2013/12/06** - Second iteration build using custom tables data model. First public release. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.1 ###
Initial concept built using custom post type/taxonomies as the data model. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)


