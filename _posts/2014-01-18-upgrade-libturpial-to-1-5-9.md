---
layout: post
title: 'New beta release for libturpial: 1.7.0-b3'
date: 2014-03-16 10:10:19
category:
    - Releases
tags:
    - Releases
    - libturpial
author: Satanas
published: true
image:
    thumb: 20140316-fixing-libturpial-380.png
    feature: 20140316-fixing-libturpial.png
    source: Featured image by (CC) kodomut / Flickr
disqus_identifier: '1477 http://turpial.org.ve/?p=1477'
---
As part of the testing process a new beta has arrived with lots of issues fixed. Most important are:

* Fixed minor style issues
* Fixed issue when registering new config options
* Fixed filters
* Fixed several config methods
* Set pic.twitter.com as default service to upload images
* Fixed support for list names with hyphens
* Fixed POST requests to be RESTful compliant

This beta is backward compatible, so you can test it safely with the stable version of Turpial (3.0) or with the development branch but consider that it will enable pic.twitter.com as default service for upload images and it WON’T WORK in Turpial 3.0. If you find anything else not working properly, [register the issue](https://github.com/satanas/libturpial/issues) or just let me know and I will fix it.

Tarball with source code of 1.7.0-b3 is available in our [files repository](https://github.com/satanas/Turpial/releases), there is a [tag in the github repo](https://github.com/satanas/libturpial/tree/1.7.0-b3) and it is available in PyPI. Documentation for libturpial can be found at [libturpial.readthedocs.org](http://libturpial.readthedocs.org/en/latest/).

Beta period will now be extended until March 21th, if no more issues are detected by the date a release candidate will be published.

Thanks to all the people helping to test.