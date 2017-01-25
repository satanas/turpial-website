---
layout: post
title: >
    Why Turpial 1.6.9 is not working and why I decided to
    continue with the project
published: true
author: satanas
comments: true
date: 2013-06-21 03:06:53
tags: [ ]
categories:
    - desarrollo-2
    - oficial
permalink: /2013/06/why-turpial-169-is-not-working
---
First, I want to thank to all the people who took the time to report the issues with Turpial 1.6.9 and even tried to find a fix. Now I'm gonna clarify a little bit the current situation. Turpial 1.6.9 is no working anymore because of the new Twitter API version. I should implement support for the API 1.1 but honestly I don't want to do it on top of 1.6.9 (in fact, I don't want to support that version anymore). Probably you are wondering "Why?". Well, because of the greater things that can be achieved with libturpial. Ok but, where is this amazing library and why it has been taking so long to see the light? I've been working with libturpial for the last 6 months to make some cool refactors and add support for Twitter API 1.1 but I got lot of problems. Among them, a very annoying memory leak that took me more than two months to fix and when I thought I was done I started to have issues with OAuth. I wrote on Twitter forum [1] to see if I got some answer but got nothing. It was a very frustrating situation (I even thought in give up) but before taking any action I decided to give it one more shot. So, I tested a couple of days ago in another machine and everything worked like a charm. After digging a while I realized that there was something wrong with my OAuth library. Shit happens. Finally, I've decided to continue with the project. Now you must be wondering "Dude, but if you have had so much trouble with libturpial why you don't just use an existing library for twitter?" The answer: Because since the beginning of the times, libturpial has been designed to support multiple accounts, multiple protocols, multiple columns and a lot of more features that make the programmers life better and there is no library that let you do such things at the moment. Maybe it was a very ambitious concept and probably I'm failing on the same errors than the GNU Hurd kernel but well, nobody said it would be easy. So, taking this decision let me just a short period of time to develop a new version of Turpial that fixes the API support issue and implement more functionalities so it would be nice to get some help. Any help will be really appreciated, this will be my last try to rescue Turpial and if I can't make it I'll give up. What needs to be done? * Tinker with [libturpial][1], understand it and use it. * Build a Qt interface with multiple columns and multiple account support for [Turpial][2] on top of libturpial. * Enjoy of fortune and fame. Actually, no fortune. Emm... Neither fame. Well just enjoy of building something for the people :P I'm creating [issues on github][3] to track pending tasks and I'll do my best to deliver (finally) a new release of Turpial. If you want to collaborate and have doubts, just ask, I'll answer any doubt gladly. Post a thread in the [mailing list][4], send me a mail, talk to me on Twitter or whatever you want. Thanks for your attention and your support

 [1]: https://github.com/satanas/libturpial
 [2]: https://github.com/satanas/turpial
 [3]: https://github.com/satanas/libturpial/issues?state=open
 [4]: https://groups.google.com/forum/#!forum/turpial-dev