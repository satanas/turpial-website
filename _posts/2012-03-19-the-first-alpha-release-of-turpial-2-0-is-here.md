---
layout: post
title: The first alpha release of Turpial 2.0 is here!
published: true
author: satanas
comments: true
date: 2012-03-19 02:03:41
tags: [ ]
categories:
    - noticias
    - packages
permalink: /2012/03/the-first-alpha-release-of-turpial-2-0-is-here
image:
    feature: alpha-release.png
---
[][1] 
  
As we [planned][2], the first alpha release of Turpial 2.0 is here and it rocks! It formal version number is 1.7.6 and it brings a lot of fresh new features. Among all the cool features we can highlight: 

  * Improved URL detection
  * Embedded profiles and images visualization
  * Advanced options in preferences dialog
  * Improved look & feel (using Webkit)
  * Broadcasting messages
  * Dialog to send DMs
  * Undo feature support (ctlr + z)
  * Show profile image at real size when you click it from a tweet/dent
  * Branded new dialog for username autocomplete
  * Handle so much columns as the user wants
  * Ubuntu integration
  * Support for public timeline as column
  * Undo retweet
  * Implemented block and report as spam features
  * Evolved mute/unmute feature to filtering (based on expressions) We did a brief resume the past month of this features and how they look/work in 

[this post][3]. There are more feature but we want to let you some homework. However, as you might know, this is a working-in-progress version so you must expect issues, breaks or even the lack of functionalities. This version is **NOT** intented for production purposes and we **DON'T** want bug reports about it. Bug reports will be welcome on the beta phase. You can check the [TO-DO list][4] to be aware of the non-finished features and here is a list of the known issues so far: 

  * Notifications preferences still not working
  * Proxy support not implemented yet
  * After creating an account the updatebox doesn't show the new account (you need to restart)
  * Column autoresize not implemented
  * Main window sometimes flicker when resizing
  * More resource consumption (around 50MB of RAM more than Turpial 1.6.9)
  * Every time you start the application you need to load your friends
  * Account dialog needs a extreme makeover
  * There is no way to follow users except through their profiles As usual, you can find the source package in our 

[files repository][5] and the source code in the [github repository][6]. Package maintainers will be working to make available this release on official repositories of most popular GNU/Linux distros. Thanks to all people that support the project and please, give us your feedback, you can help to the development process just commenting out your impressions. Enjoy!

 [1]: http://turpial.org.ve/wp-content/uploads/2012/03/alpha-release.png
 [2]: http://turpial.org.ve/2012/03/alpha-release-delayed-for-2-0/
 [3]: http://turpial.org.ve/2012/02/turpial-2-0-whats-new/
 [4]: http://dev.turpial.org.ve/projects/turpial/issues?set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&v%5Bstatus_id%5D%5B%5D=1&f%5B%5D=fixed_version_id&op%5Bfixed_version_id%5D=%3D&v%5Bfixed_version_id%5D%5B%5D=4&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=author&c%5B%5D=fixed_version&c%5B%5D=start_date&group_by=
 [5]: http://files.turpial.org.ve/sources/development/
 [6]: https://github.com/satanas/Turpial