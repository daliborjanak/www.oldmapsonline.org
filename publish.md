---
layout: page
section: page
permalink: publish/
title: Publish
description: Publish
keywords: publish, map, oldmap
---

#Publish
If you have images of scanned maps on your computer and you would like to publish them online in a zoomable viewer on your own websites you can follow one of these tutorials:

- Publishing with pre-rendered .jpg tiles (Zoomify)
- Publishing with image server (IIPImage)

##Online map publishing with Zoomify step-by-step

Any standard web hosting, where you can host simple HTML files and images, can host also the zoomable maps without any extra configuration.
1. Download and run Zoomify Express from the Zoomify.com website to your desktop - use either the "Download Win" or "Download Mac" button. A free alternative is the OpenTiler.
2. As soon as you start the Zoomifyer or OpenTiler application, it will ask you for an image file to process (tiff or jpeg files). Then it generates a folder full of image tiles.
3. You should place a simple web viewer into the produced directory. Easiest is to copy our prepared template: the index.html file and the ZoomifyViewer.swf (use right click and "Save As" to save those linked files to your computer). These two files should be in the directory with the rendered tiles - exactly in the same place where the ImageProperties.xml file is. OpenTiler generates the HTML viewer directly. 
4. Upload the whole directory tree to the web (for example with any FTP client). Point your web browser to the index.html on your hosting. Done!

##Online map publishing with an image server step-by-step

You need a web-hosting which allows installation of a custom software (typically a virtual server), or your computer must be permanently connected to the network and configured to provide public webpages to the Internet.

Advantage of this approach is that you can have one JPEG2000 file per map, and this file can be have lossless encoding - so it can be used as the main archival copy. The software will make available such files to the online visitors for preview in a lower quality and even protected with watermark.

Download the installer from: http://code.google.com/p/oldmapsonline/downloads/list

We recommend to use the Linux64 bit Debian server in production environment, but an easy-to-use installer for Windows for trying this software on a desktop computer is available as well. More details about this software are at: http://help.oldmapsonline.org/jpeg2000/