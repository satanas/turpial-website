---
layout: post
title: libturpial 1.0 released
published: true
author: satanas
comments: true
date: 2013-07-14 11:07:42
tags: [ ]
categories:
    - noticias
    - oficial
    - release
permalink: /2013/07/libturpial-1-0-released
---
[][1] After months of heavy development I'm glad to finally announce the official release libturpial 1.0. libturpial is the backend of the next Turpial version, it handles multiple microblogging protocols (Twitter and Identi.ca at the moment) and has support for multiple accounts and multiple columns. It is a great tool to develop automated Python scripts that need to handle the Twitter API or even to develop a microblogging client on top of it. Most important features of the final release include: 

  * Support for Twitter API v1.1
  * Fixed memory leak
  * Migrated code from urllib2 to [Requests][2]
  * Restructured Core
  * Eased the OAuth process
  * Enhanced documentation
  * Raising exceptions for error situations
  * Developed accounts manager and columns manager
  * Improved string representation of most commonly used models
  * Added a minimal unit test script libturpial is now available from our 

[files repository][3] and from [PyPI][4]. You can install it from sources or via pip using: 

    pip install libturpial Do you want to test libturpial? Take a look at our 

[Quickstart Guide][5] or follow the [instructions to generate the documentation][6] of libturpial for a full API reference. If you find any issue please report it on [Github][7] or in our [mailing-list][8]. Thanks to the all the people that showed us their support and contributed to achieve this big step.

 [1]: http://turpial.org.ve/wp-content/uploads/2013/07/libturpial-package.png
 [2]: http://docs.python-requests.org/en/latest/
 [3]: http://files.turpial.org.ve/sources/stable
 [4]: https://pypi.python.org/pypi/libturpial
 [5]: https://github.com/Turpial/libturpial/blob/development/docs/quickstart.rst
 [6]: https://github.com/Turpial/libturpial#documentation
 [7]: https://github.com/Turpial/libturpial/issues
 [8]: https://groups.google.com/forum/#!forum/turpial-dev