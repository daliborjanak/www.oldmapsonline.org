---
author: Petr Pridal
blogger_id: tag:blogger.com,1999:blog-6689009.post-8230454622435766297
blogger_orig_url: http://blog.klokantech.com/2014/10/iiif-for-images-in-culture-heritage.html
date: '2014-10-20T10:58:00.000+02:00'
layout: post
modified_time: '2014-10-31T09:35:06.981+01:00'
tags:
- osgeo
- open-source
- iipimage
thumbnail: /media/2014-10-20-iiif-for-images-in-culture-heritage_1.png
title: IIIF for images in cultural heritage
---

Online scans of culture heritage documents, such as old maps, books, photographs, etc. are being published by the galleries, libraries, archives and museums.  Until now there was no official standardisation activity in this area. This is now changing with the International Image Interoperability Framework IIIF (<a href="http://iiif.io/">http://iiif.io/</a>), which enables easy access to large raster images across institutions.

<b>We are happy to announce a new Open Source IIIF viewer, with several useful features: </b>

- Rotation on client side  - pinch with fingers, Alt-Shift drag with the mouse- Drawing tools - polygons, lines, markers - used to annotate parts of the pictures- Color adjustments - saturation, lightness, etc


<iframe allowfullscreen="" frameborder="0" height="315" src="https://www.youtube.com/embed/5860HWRu0Lk?rel=0" width="420"></iframe>Demo available at: <a href="http://klokantech.github.io/iiifviewer/" style="text-align: left;">http://klokantech.github.io/iiifviewer/</a>

The viewer is pure Java Script, mobile optimised with almost native feeling for zoom and powered by OpenLayers V3 open-source project, where we are co-developers (see <a href="" target="_blank">blog post</a>).

Feel free to try at: <a href="http://klokantech.github.io/iiifviewer/">http://klokantech.github.io/iiifviewer/</a>

Source codes are available on GitHub: <a href="https://github.com/klokantech/iiifviewer/">https://github.com/klokantech/iiifviewer/</a>

This viewer is another important part of the mosaic of open source tools for publishing of large images and maps. Together with high-performance open-source JPEG2000 image server can be used to serve thousands of users in a very fast and efficient way.

The mentioned server providing IIIF endpoint for the JPEG2000 images was developed and released by Klokan Technologies in cooperation with the National Library of Austria and their Google Books scanning project, the <a href="{{ site.baseurl }}{% post_url 2013-11-11-the-austrian-national-library-first %}" target="_blank">Austrian Books in 2013</a>. The documentation is available at: <a href="https://github.com/klokantech/iiifserver/">https://github.com/klokantech/iiifserver/</a>
Server software runs under Linux, Mac OS X as well as Windows. There is even an easy to use <a href="https://github.com/klokantech/iiifserver/releases" target="_blank">installer</a>.  It is powered by IIPImage server and our code has been recently refactored and merged back to the main IIPImage repository.

Support and maintenance for installation of this open-source software can be provided by Klokan as well as the access to JPEG2000 Kakadu license.

The documentation is available at: <a href="https://github.com/klokantech/iiifserver/">https://github.com/klokantech/iiifserver/</a>
