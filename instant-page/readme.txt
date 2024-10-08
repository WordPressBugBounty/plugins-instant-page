﻿=== instant.page ===
Contributors: instantpage
Tags: instant, performance, flying pages
Requires at least: 4.7
Tested up to: 6.3
Stable tag: 5.7.0
Requires PHP: 5.2.4
License: MIT
License URI: https://instant.page/license

Make your site’s pages instant in 1 minute.

== Description ==

Make your site’s pages instant in 1 minute and improve your conversion rate noticeably. More info on [https://instant.page/](https://instant.page/).


== Changelog ==

= 5.7.0 =

instant.page script v5.2:

* Preload with high priority (fetchPriority=high) on mouse/touch interactions.
* Fix cross-origin preloading in Chromium (using the non-standard as=document, which might eventually disappear from Chromium).
* Disable (non-working) cross-origin on non-Chromium browsers.

= 5.6.1 =

instant.page script v5.1.1: Fix the error “event.target.closest is not a function” that would sometimes trigger in the mouseover event

= 5.6.0 =

Bug fix: Load the script correctly (as a module) with themes using the HTML5 syntax.

instant.page's script version remains the same (5.1.0). This is a new versioning scheme, decoupled from instant.page's script version.
