---
layout: post
title: First stable release of libturpial
published: true
author: satanas
comments: true
date: 2012-03-17 06:03:01
tags: [ ]
categories:
    - noticias
    - oficial
permalink: /2012/03/first-stable-release-of-libturpial
---
[][1] From branch 2.x, all Turpial backend relies on a single library that handles multiple microblogging protocols, multiple accounts, configurations and a lot of features of each protocol. The library we are talking about is **libturpial** and today, as part of the alpha release of Turpial, we proudly present the first stable release in it version 0.8.5. Development of this library started on March 2011 and now is ready to be used, not just for Turpial 2.x else for general purpose too. Main features of this library include: 

  * OAuth support for Twitter
  * Handle accounts and columns
  * Fetch timeline, replies, directs, sents, lists and favorites
  * Fetch public timeline
  * Fetch friends
  * Fetch conversations
  * Update, destroy, repeat statuses
  * Handle direct messages
  * Mark/unmark favorites
  * Handle relationship (follow, unfollow, block, unblock, report as spam)
  * Perform searchs
  * Fetch trends
  * Handle services for short URLs
  * Handle highlighted reources as entities
  * Handle configuration stuffs
  * Fetch followers and friends
  * Support for undo retweet
  * Implemented filtering by words/expressions
  * Open media module to handle embedded resources (images, videos, etc)
  * Improved security using HTTPS on Identi.ca and working with SSL certificates for all services Source code can be downloaded in our 

[files repository][2] and the package should be available soon in most popular GNU/Linux distributions. More info in the [official announcement][3] of the Turpial mailing list. I want to extend my thanks to all people that have been working hard day after day to make this release possible, great job guys! Let's keep working. And for all the people that would like to contribute or help the project but are not developers remember, click the advertising or donate is a great way to contribute too. Thanks!

 [1]: http://turpial.org.ve/wp-content/uploads/2012/03/building-blocks.jpg
 [2]: http://files.turpial.org.ve/sources/stable/
 [3]: http://groups.google.com/group/turpial-dev/browse_thread/thread/420afda8d001c379