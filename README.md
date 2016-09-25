# lektor-foundation

Lektor-foundation is a Zurb Foundation 6 (http://foundation.zurb.com/sites/docs/) starter theme for Lektor, a static content management system (http://getlektor.com). To get started, download the theme, navigate to the location where you downloaded it, and run "lektor server" for a preview.

Demo: http://joyyy.xyz/foundation

![Screenshot](https://raw.githubusercontent.com/joyhchen/lektor-foundation/master/assets/screenshot.png)

### Getting Started

If you use this theme, you don't have to run "lektor quickstart" because this theme is already a Lektor project itself (as Lektor does not yet have support for themes). Head into the "site.lektorproject" file and make sure you change the name of the project. You can also choose to change the "site.lektorproject" file name to something like "mysite.lektorproject" as long as you keep the ".lektorproject" ending.

### Plugins

This theme comes with two plugins out of the box: lektor-htmlmin (HTML minification) and lektor-embed-x (for embedding media such as tweets). To remove these plugins, head into "site.lektorproject" and delete the plugin names under "[packages]" (this is also where you can specify any packages you would like to add).

### Templates

The theme comes with a basic page template, a blog, and a kitchen sink page to showcase the various components included out of the box. For more information on how to build templates, refer to the [Lektor documentation on templates](https://www.getlektor.com/docs/templates/).

### Components

The theme currently has the following components implemented through flow blocks:

- Accordion
- Callout
- Modal
- Slider
- Table
- Tabs
- etc.

More information on the theme and components can be found in the [wiki](https://github.com/joyhchen/lektor-foundation/wiki).
