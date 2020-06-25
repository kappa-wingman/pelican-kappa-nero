pelican-kappa-nero
------------------

This theme is copied from pelican-bootstrap3-nero and pelican-bootstrap3 with lots of customization.

I could not update the related changes that should be made for translation (foreign languages).

Use it at your own risk.

- For this theme:

  - The changes and parameters are incompatible with
    the original pelican-bootstrap3 and pelican-bootstrap3-nero or pelican-bootstrap4-nero
  - The theme is customized to my preference

Changes, newer changes on top
-----------------------------

- Version 1.1.0

  - Not loading style.css in base.html template
    Moved part of the content from style.css to nero.css
  - Improved SEO
  - Added code block for meta tag robots and description so that
  they could be overwritten in the templates
  - Updated the url for og:description
  - Normal pages would load jquery-slim.js, execpt Tipusearch needs jquery.js

- Version 1.0.9

  - Update the screenshot
  - Only create breadcrumblist for category and article
  - Adding the canonical URL to base.html, so that it should 
    generate the URL for every page.
    Previously added the code to individual pages, now commented.
    Those commented codes may be removed after more testing.

- Version 1.0.8

  - Update layout 
  - JSON-LD: update on category url
  - Fixed archives button/icon in navbar
  - Added rel = prev/next for pagination links
  - Add canonical url to most of the templates
  - Add the current URL to most of the WebPage schema in JSON-LD

- Version 1.0.7

  - Update layout of tags.html
  - Update icons and minor layout update
  - Update docs-searchbar.js to 1.1.6
  - New options for setting meta tags for robot for some pages

- Version 1.0.6

  - Update layout
  - Update JSON-LD settings 

- Version 1.0.5

  - Update layout
  - Fix clicking anchor/links in main content using smartphones
  - Apply a newer version of tipueseach lite

- Version 1.0.4

  - Meilisearch as default search
  - Retains the old tipusearch in a separate page

- Version 1.0.3

  - Got a better fix for clicking anchors and scroll in an article

- Version 1.0.2

  - Fixed scrollspy
  - Include a KMP search javascript file for tipue

- Version 1.0.1
  
  - Update left sidebar and main content responsive design

- Version 1.0.0

  - Theme created based on pelican-bootstrap4-nero v1.0.1
  - Uses the base bootstrap.min theme instead of the slate theme
  - Not using Font Awesome 4.7. Change to use `Feather icons <https://github.com/feathericons/feather>`__
  - Removed files, fonts, theme and shariff that are not used by the theme
  - Fixed the pagination layout in neighbour posts
  - If tipue search plugin is enabled, uses jQuery, else uses jQuery slim
