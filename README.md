=== PDF Embedder - Scrollable ===
Tags: pdf, embed, scrollable, document viewer, pdf.js
Requires at least: 5.0
Tested up to: 6.6
Stable tag: 1.1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A WordPress plugin to embed scrollable PDFs with customizable scales.

== Description ==

PDF Embedder - Scrollable allows you to easily embed PDF files into your WordPress site with a scrollable viewer. Customize the scale of each PDF viewer and provide a seamless experience for your users.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/pdf-embedder-scrollable` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Use the shortcode `[pes_pdf_scrollable_embed url="your-pdf-url"]` to embed PDFs in your posts or pages.

== Frequently Asked Questions ==

= How do I embed a PDF? =

Use the shortcode `[pes_pdf_scrollable_embed url="your-pdf-url" scale="1.5" width="100%" height="100%" max-width="800px" max-height="90vh"]`.

== Screenshots ==

1. Example of embedded PDF with scrollable functionality.

== Changelog ==

= 1.1.0 =
* Fixed various security issues.
* Improved handling of relative URLs in shortcode.

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 1.1.0 =
* Important security updates and bug fixes. Please update to ensure compatibility with the latest WordPress version.

= 1.0 =
* Initial release of the plugin.

== License ==

This plugin is licensed under GPL-3.0.

== Source Code ==

The minified JavaScript libraries used in this plugin are compressed for performance. The original, human-readable source code for these libraries can be found at the following locations:

- **pdf.js**: [GitHub Repository - Mozilla pdf.js](https://github.com/mozilla/pdf.js)
- **pdf.worker.js**: [GitHub Repository - Mozilla pdf.worker.js](https://github.com/mozilla/pdf.js)

If you would like to review or contribute to the development of these libraries, please refer to the repositories above. Any modifications made to these libraries in this plugin will be documented in future versions of the plugin.

Additionally, the source code for the plugin itself is available on our GitHub repository at:
- **Plugin Source Code**: [GitHub - Aurorbyte PDF Embedder](https://github.com/aurorbyte/pdf-embedder-scrollable)

We welcome contributions and feedback from the community. Please submit any pull requests or issues directly to the GitHub repository above.
