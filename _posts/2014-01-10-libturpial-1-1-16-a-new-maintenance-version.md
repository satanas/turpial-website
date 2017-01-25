---
layout: post
title: 'libturpial 1.1.16: A new maintenance version'
published: true
author: satanas
comments: true
date: 2014-01-10 02:01:07
tags: [ ]
categories:
    - oficial
    - release
    - actualizaciones-2
permalink: /2014/01/libturpial-1-1-16-a-new-maintenance-version
image: 
  thumb: libturpial-1.1.16-380.png
  feature: libturpial-1.1.16.png
---


 As part of the improvement process and to anticipate to the [

 As part of the improvement process and to anticipate to the][1] on January 14th, 2014, I've released a new libturpial version. This maintenance version includes the following changes: 

  * Method to handle socket timeout
  * Proxy configuration handled via model
  * Fixed cache calculation
  * Refactored and fixed configuration module
  * Fixed list support
  * Added/removed friends to local list after follow, unfollow, block and report as spam
  * Fixed broadcast when passing no arguments
  * Profile model now indicates if the user is following you or not
  * New fields to status model libturpial 1.1.16 is now available from our 

[files repository][2] and from [PyPI][3]. You can install it from sources or via pip using: 

    pip install libturpial Take a look at our 

[Quickstart Guide][4] to test libturpial or follow the [instructions to generate the documentation][5] for a full API reference. This version is compatible with the previous version and you should **upgrade as soon as possible**, otherwise Turpial (and libturpial) will stop working by January 14th, 2014. If you find any issue please report it on [Github][6] or in our [mailing-list][7].

 [1]: https://dev.twitter.com/discussions/24239
 [2]: http://files.turpial.org.ve/sources/stable
 [3]: https://pypi.python.org/pypi/libturpial
 [4]: https://github.com/Turpial/libturpial/blob/development/docs/quickstart.rst
 [5]: https://github.com/Turpial/libturpial#documentation
 [6]: https://github.com/Turpial/libturpial/issues
 [7]: https://groups.google.com/forum/#!forum/turpial-dev
