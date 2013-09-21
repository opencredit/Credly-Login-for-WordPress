=== Credly Login ===
Contributors: credly, lomteslie
Tags: credly, login, badgeos, badges, openbadges, BadgeOS, open badges, single sign on, SSO
Requires at least: 3.0.1
Tested up to: 3.6.1
Stable tag: 1.0.0
License: GNU AGPLv3
License URI: http://www.gnu.org/licenses/agpl-3.0.html

Log in to a WordPress site using your Credly account without having to manually create an additional account.

== Description ==

Once Credly login is installed, it will create an option to log in to your site through /wp-admin with your Credly credentials.

When logging in with Credly Login, a new WordPress user account will automatically be generated and associated with your Credly account for future logins.

Plugin comes with a sidebar widget allowing users to embed a WordPress/Credly user login form on the frontend of their site.

**Automatically integrates with BuddyPress sidebar login.**

== Installation ==

1. Upload `credly-login` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

= What if I already have a WordPress account? =

Credly Login will look for a WordPress user that has your Credly email associated with it. If one is found, your Credly
account will then be used to log in with that user account.

= Why don't I have any permissions once I log in? =

New accounts are created without permissions. They must be set by an Admin after your account has been created.

== Screenshots ==

1. A new button is created for the login screen.
2. A modal appears allowing you to log in with your Credly creds.

== Changelog ==

= 1.0.0 =
* Inital creation.

`<?php code(); // goes in backticks ?>`
