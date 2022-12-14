=== Foodie Pro 4.0.0 Genesis Child Theme ===

Set up tutorials can be found at https://feastdesignco.com/how-to


=== Installation Instructions ===

1. Upload the Foodie Pro theme by navigating to Admin > Appearance > Themes > Add New > Upload Theme > Choose File (Note: the Genesis parent theme needs to be uploaded first as well - but don't activate it.)
2. Go to your WordPress dashboard and select Appearance.
3. Activate the Foodie Pro theme.
4. Inside your WordPress dashboard, go to Genesis > Theme Settings and configure them to your liking.


=== Theme Support ===

Please visit https://feastdesignco.com/support/ or https://my.studiopress.com/support for theme support.


=== Changelog ===


= 4.0.0 = 

* Added PHP version check for PHP5.6 end-of-life notification
* Updated font-size to bring in-line with modern web standards
* Removed defined height from add_image_size()
* Theme width set to 720 px for consistency
* Thumbnail sizes set to 360 px and 720 px width – height changed to “9999 px” so that all images will resize to width dimensions
* Updated search function
* Woocommerce styling removed due to low usage – can be found here
* Fix: added min-height:52px; for the mobile menu items to resolve clickable elements warning
* Updated styling to accommodate block editor (Gutenberg) elements
* Added styling for WP Rocket image lazyloading


= 3.2.0 = 

* Updated dashboard for consistency across themes
* Updated header whitespace to be smaller, so that more content displays above-the-fold
* Updated <figure> styling

= 3.1.7 = 

* Minor bug fixes

= 3.1.6 =

* Updated footer function for ease of editing (we now recommend the "Genesis Simple Edits" plugin as well)
* Updated header to use <img> rather than background-image, with site title in its proper place (alt tag)
* Header will now display at whatever resolution it's uploaded at - no coding changes required
* Updated CSS to fix search-engine-unfriendly hidden-text (text-indent:-9999px;)
* Updated <pre> style to more closely resemble gist/github

= 3.1.4 =

* Renamed recipes-top to recipe-index-search
* Renamed recipes-bottom to recipe-index-featured-posts
* Updated aligncenter images CSS
* Added more descriptive content to widget areas

= 3.1.1 =

* Fixed a bug in the widget read more text which caused the widget to not save correctly in some environments
* Fixed a bug with first grid item width on smaller screens
* Removed a deprecated Genesis function for getting image sizes
* Removed some unused legacy styles

= 3.1.0 =

* Added a helpful theme dashboard
* Improved mobile menu debounce method to reduce conflicts with plugins
* Improved mobile menu hidden check to reduce conflicts with plugins
* Fixed a conflict with the Headline Optimizer Plugin
* Changed after-entry widget area to use the built-in Genesis after-entry widget area
* Replaced Customizer Library with FeastCo Customizer Library
* Modernized customizer options to make changing colors and typography less overwhelming
* Restructured code for better consistency across all Feast themes

= 3.0.0 =

* Overhauled theme styles
* Removed TGMPA script
* Various code improvements

= 2.1.9 =

* Fixed a potential JS error when no menus have been defined
* Updated TGMPA to 2.6.1
* Included better translations for TGMPA

= 2.1.8 =

* Fixed an issue with the menu drop-down styling
* Updated TGMPA to 2.5.2

= 2.1.7 =

* Fixed an issue with Genesis eNews on mobile devices.

= 2.1.6 =

* Improved mobile menu JS.
* Improved menu accessibility.
* Updated normalize.css to the latest version.
* Allowed lato to use the latin-ext subset.

= 2.1.3 =

* Updated TGMPA to the latest development version for security reasons.

= 2.1.1 =

* Removed Before Header widget area from landing page template.

= 2.1.0 =

* Added WPML compatibility for the Foodie Pro Featured Posts widget.
* Updated textdomain to match directory name.
* Updated vendor file textdomains to match the foodiepro theme textdomain.
* Updated Customizer Library to the latest version.
* Added a default .pot file.
* Added a Grunt config to make language translation easier.

= 2.0.7 =

* Updated CSS to allow for full-width posts with left-aligned thumbnails and excerpts on the content archives.
* Updated CSS to allow for .clear div class.
* Changed name of Top Ad widget area to Before Header to avoid ad-blockers from hiding the widget area in the dashboard.
* Updated broken landing page template.
* Adjusted how the post titles appear on the content archives so that it matches the recipe index.

= 2.0.5 =

* Fixed title size on search pages.

= 2.0.4 =

* Added search archives to the foodie_pro_is_blog() function so they are handled the same as other archives.
* Minor PHP code refactoring and cleanup.
* Updated Customizer Library to the latest version.

= 2.0.3 =

= 2.0.2 =

* Fixed a bug that allowed grid settings to bleed into widget areas on full-width pages.

= 2.0.1 =

* Added foodie_pro_disable_google_fonts filter to allow users and developers to disable the Google Fonts customizer output.
