Corporate KISS
==============

Corporate KISS is a simple clean theme that is meant to look nice for business
or corporate web sites.  It is written in nothing but pure CSS, with no
template files.  It fully relies on Backdrop's core layout system for layout.

It is written with the philosophy of **K**eep **I**t **S**imple, **S**tupid.
It's about as light weight as it can get for a theme.  It is flexible and fully
responsive for all screen sizes, as all themes in Backdrop should be due to the
core layout system.  It is also designed to utilize wide screens well.  Out of
the box, the content area expands up to 1500 pixels, which can easily be
changed.  See the comments in **css/style.css**.

To customize, it is recommended that you either create the file,
**css/local.css**, in the theme directory and add custom CSS there, or use the
[CSS Injector](https://backdropcms.org/project/css_injector) module.  You can
copy styles from any of the other CSS files in this theme and edit to suit.

The local.css file does not exist in the package so that it can be upgraded
without overwriting local customizations.  However, if you delete the old theme
files prior to installing a new version, you will need to backup **css/local.css**
first, then restore it after upgrading.

Of course, like with any other Backdrop theme, you can also create your own
custom theme as a [sub-theme](https://api.backdropcms.org/documentation/creating-sub-themes)
of Corporate KISS, that only contains your custom changes.

Installation
------------

- Install this theme using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/themes

- There are no theme settings for this theme.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/corporate_kiss/issues

Current Maintainers
-------------------

- Vincent Stemen (https://github.com/vstemen).

Credits
-------

- Written by Vincent Stemen (https://github.com/vstemen).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

