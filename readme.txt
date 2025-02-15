=== HelixWare - Video Hosting for WordPress ===
Author URL: https://blog.insideout.io/about-us
Plugin URL: https://helixware.tv

Contributors: insideout10, ziodave
Tags: video, streaming, ondemand, SEO, audio, media analysis, hd video, encoding, HLS, Flash, OTT, DASH, rtsp
Requires at least: 4.3
Tested up to: 4.3.1
Stable tag: 1.4.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

HelixWare turns WordPress into a Video Hosting platform, supports live and makes videos discoverable, searchable, and beautifully organised.

== Description ==

> #### HelixWare - Upload and play beautiful HD video right from your site.
> 

HelixWare is a WordPress plugin which integrates with the [HelixWare](http://helixware.tv) **video cloud platform**.

With this plugin, you can upload videos, organise them using the WordPress Media library and add a shortcode to display them on your site.

Installing and activating HelixWare turns WordPress into a **powerful integrated streaming platform** with the following features:

* Upload any video file via the familiar WordPress Media screen
* Videos take **zero space** and **zero CPU** on your WordPress hosting
* We automatically encode your videos to multiple bitrates and formats
* Stream to any device: PCs, Macs, Linux, iPhones, Androids

> #### HelixWare - Registration
> To use this plugin you need to register on [helixware.tv](https://helixware.tv/sign-up/) <br />
> get the application key and secret and add it to the configuration panel. 
> 

== Installation ==

To install:

1. Upload `helixware.zip` to the `/wp-content/plugins/` directory
2. Expand the file
3. Activate the file
4. Register on [helixware.tv](http://helixware.tv) to get an application key and secret
5. Activate the plugin and set the application key and secret in the configuration

== Frequently Asked Questions ==

If you have any question, send us an e-mail to info@helixware.tv

== Changelog ==

= 1.4.0 (2015-11-20) =
* Enhancement [#28](https://github.com/insideout10/helixware-plugin/issues/28): now that HelixWare is integrated with the WordPress Media Library we don't need to expose the "create post" row after an upload.
* Enhancement [#39](https://github.com/insideout10/helixware-plugin/issues/39): add the HelixWare embed shortcode in the video assets metadata.

= 1.3.7 (2015-11-20) =
* Fix [#36](https://github.com/insideout10/helixware-plugin/issues/36): helixware-admin.css not found.
* Fix [#37](https://github.com/insideout10/helixware-plugin/issues/37): cannot add custom fields using ACF Pro.

= 1.3.6 (2015-11-16) =
* Fix [#32](https://github.com/insideout10/helixware-plugin/issues/32): add media with assets other than HelixWare videos doesn't work.
* Fix [#33](https://github.com/insideout10/helixware-plugin/issues/33): incompatibility with ACF plugin.

= 1.3.5 (2015-11-16) =
* Fix: disable SSL communications to avoid issues with some hosts.

= 1.3.4 (2015-11-16) =
* Fix: rename hls redirector.

= 1.3.3 (2015-11-16) =
* Fix: support legacy JWPlayer 6 instances also when JWPlayer 7 is configured.

= 1.3.2 (2015-11-15) =
* update server certificates.

= 1.3.1 (2015-11-15) =

* fix server certificate.
* fix scripts for player shortcode.

= 1.3.0 (2015-11-02) =

* add the video preview of an on-demand asset in the Media Library [#29](https://github.com/insideout10/helixware-plugin/issues/29)
* add support for VideoJS - APL video player [#14](https://github.com/insideout10/helixware-plugin/issues/14)
* Media Library data is synchronized (two-ways) with HelixWare Server [#13](https://github.com/insideout10/helixware-plugin/issues/13)
* when an asset is deleted from the Media Library it is deleted in HelixWare Server as well [#12](https://github.com/insideout10/helixware-plugin/issues/12)

= 1.2.1 (2015-10-12) =

* move the MICO extensions to a separate plugin [#25](https://github.com/insideout10/helixware-plugin/issues/25)

= 1.2.0 (2015-10-11) =

* add support for JWPlayer 7; do not include non-GPL files with the plugin and use CDN for JWPlayer [#15](https://github.com/insideout10/helixware-plugin/issues/15)
* add support for MICO extensions, temporal video segmentation [#20](https://github.com/insideout10/helixware-plugin/issues/20)

= 1.1.0 (2015-10-04) =

* WordPress Media Library integration [#10](https://github.com/insideout10/helixware-plugin/issues/10)
* Media Library synchronization happens only when WP requests the list of attachments [#18](https://github.com/insideout10/helixware-plugin/issues/18)

= 1.0.0 =

* First release.
