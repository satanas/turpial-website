---
layout: post
title: first-release-candidate-for-libturpial-1-7-0
category:
    - Releases
tags:
    - Releases
    - libturpial
author: Satanas
published: true
image:
    featured: lab-tests-380.jpg
    featured_big: lab-tests.jpg
    source: Featured image by (CC) gravitywave / Flickr
---

In March 6th, libturpial passed from heavy development to beta status. [Three betas](/2014/03/new-beta-release-for-libturpial-1-7-0-b3/) have been released since then, [lot of tests](http://turpial.org.ve/2014/03/first-beta-for-libturpial-1-7-0/) have been performed and everything seems to indicate that libturpial is in a very good shape. That’s why today I’m pleased to announce the first release candidate of libturpial 1.7.0.

This release has **no new features** but confirms that no new bugs have been detected. It includes all the changes and fixes from previous betas, so in this version you should expect: backward compatibility, working filters, an improved configuration module, lot of test cases and other minor fixes.

We need your help to find bugs and improve the library, so please try it. The only known issue so far is that this version of the library will enable pic.twitter.com as service for upload images and it **WON’T WORK** with Turpial 3.0 (the current stable version) but it should work fine with the development version of Turpial. If you find anything else not working properly, [register the issue](https://github.com/satanas/libturpial/issues) or just let me know.

Tarball for this release candidate is available in our [files repository](https://github.com/satanas/libturpial/releases), there is a [tag in the github repo](https://github.com/satanas/libturpial/tree/1.7.0-rc1) and it is available in [PyPI](https://pypi.python.org/pypi/libturpial/1.7.0-rc1). Latest documentation for libturpial can be found at [libturpial.readthedocs.org](http://libturpial.readthedocs.org/en/latest/).

Test period for this release candidate will be until April 2nd and if no critical issues are discovered by the date, the final version will be published. I hope this final version has a really long lifetime.

Thanks for your support.