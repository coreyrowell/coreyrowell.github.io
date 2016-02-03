---
layout: post
title:  "Client Side EXIF Data Remover"
date:   2016-02-1 02:12:57 +0000
categories: exif
---
Client side EXIF data remover: [http://ec2-52-88-126-197.us-west-2.compute.amazonaws.com/exif/](http://ec2-52-88-126-197.us-west-2.compute.amazonaws.com/exif/)

Or if you prefer DNS: [removeexifdata.com](http://removeexifdata.com/)

I wrote this web tool to strip EXIF data from images in bulk because I didn't want to download a 3rd party tool, the only web tools I could find accepted a single image, who knows what they do with my data, Windows sometimes leaves GPS data behind, I'd never tried to do it on a Unix system and a 30 second Google search how to do it on OSX  pointed me right back to my original issue.

Turning off location data for the camera was too hard... (that's not actually true, but I do want/need that data!)

This runs purely client side, absolutely nothing is uploaded to a server!