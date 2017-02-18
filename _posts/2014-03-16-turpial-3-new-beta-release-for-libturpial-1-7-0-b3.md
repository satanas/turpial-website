---
layout: post
title: Upgrade libturpial to 1.5.9!
category:
    - Releases
tags:
    - Releases
    - libturpial
author: Satanas
published: true
image:
    thumb: software-bug-380.jpg
    feature: software-bug-450x283.jpg
    source: Featured image by (CC) guitavares / Flickr
disqus_identifier: '1442 http://turpial.org.ve/?p=1442'
---
Due to a bug in the [previous version of libturpial (1.1.16)](http://turpial.org.ve/2014/01/libturpial-1-1-16-a-new-maintenance-version/) I’ve released a new version with the proper fix and I encourage to everyone to upgrade as soon as possible. Previous version doesn’t work and will be deprecated, please don’t use it anymore. I apologize for all the inconveniences.

This time I’ve added more than fixes and this release includes:

* Support to upload images using pic.twitter.com
* Preview for Instagram pictures
* Fixed filters
* Parameter to enable/disable cache when getting profile image
* Implemented retweet count in statuses
* Possibility to fetch a single column or a single account
* Change profile image
* Support for trend locations and trending topics
* Fixed issue with previous version

You can check the [full ChangeLog](https://github.com/satanas/libturpial/blob/1.5.9/ChangeLog) for more information. This version is backward compatible and safe to use with your current Turpial installation.

libturpial 1.5.9 is available from our [files repository](https://github.com/satanas/libturpial/releases) and from [PyPI](https://pypi.python.org/pypi/libturpial). You can install it from sources or via pip using:

    pip install libturpial

This version should be available already in ArchLinux via AUR and our friends packagers will be working to make it available for Ubuntu, Debian and Fedora as soon as they can.

Thanks for your patience.