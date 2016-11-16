---
layout: post
title: libturpial 1.7.0 is now stable
category:
    - Releases
tags:
    - Releases
    - libturpial
author: Satanas
published: true
image:
    featured: building-blocks-380.png
    featured_big: building-blocks.png
    source: Featured image by (CC) antpaniagua / Flickr
---

Today, I’m announcing the next stable release for the library that serves as base for Turpial. I’m happy to say that libturpial has reached it version 1.7.0!

## But why is this so important? ##

Well, libturpial is the Python library that lets Turpial interact with the Twitter API and handle complex stuff like multi-accounts or multi-columns with just a couple lines of code (yes, it’s that awesome). libturpial is the foundation behind Turpial 3.0 and this new version will become in the major stable version so far because has been developed thinking in the long term.

There are no fancy-new features compared to the previous version but it has lot of fixes and a test cases that will help to guarantee it quality. Right now, most critical modules are covered by the tests and the overall coverage is of at least 93%.

## Ok, What can I do with libturpial? ##

So far with libturpial you can:

* Get tweets from timeline, mentions, favorites, lists, etc
* Upload images and short URLs with a bunch of services (including with pic.twitter.com)
* Filter tweets
* Update your user profile
* Handle relationship (follow, unfollow, block, unblock, report as spam)
* Broadcast messages
* Manage multiple accounts
* Reach Twitter through a Proxy
* Preview images
* Get trending topics by location
* Interact with tweets (reply, mark as favorite, retweet, send messages, etc)
* Manage any kind of custom user configuration
* Do a lot of other crazy stuff

For more information about the features you can check the [latest documentation](http://libturpial.readthedocs.io/en/latest/). Remember that libturpial is JUST the library (not the whole client), and as library can be used for scripts or any other purpose that implies to interact with Twitter. If you want to play with the code take a look to the [Quickstart Guide](http://libturpial.readthedocs.io/en/latest/quickstart.html), that’s the best place to start. Soon we will be posting a brief tutorial of how to use libturpial to play with the Twitter API.

## Show me the code! ##

Source code of libturpial 1.7.0 is available in our [files repository](https://github.com/satanas/libturpial/releases) as a [tarball file](https://github.com/satanas/libturpial/archive/1.7.0.tar.gz) and as a [tag in the github repo](https://github.com/satanas/libturpial/tree/1.7.0).

## Installation ##

    sudo python setup.py install
    
libturpial is also available from [PyPI](https://pypi.python.org/pypi/libturpial/1.7.0), so you can install it using:

    pip install libturpial

## Running the tests ##

To run the tests you must go to the libturpial folder and execute:

    py.test --cov libturpial --cov-config .coveragerc tests/
    
Note that you will need to have [py.test](http://pytest.org/latest/) installed in order to run the test cases.

## What’s next? ##

This version is compatible with the previous version and packages for Ubuntu, Debian, Fedora, Arch and other distros will be available soon.

I’ll appreciate any help finding bugs or improving the library, so if you find anything not working properly register the issue in github or just let me know. The only known issue so far is that this version will enable pic.twitter.com as service for upload images and it **WON’T WORK** with Turpial 3.0 but it should work fine with the development version or any latest.

That’s all folks. Thanks for your support.