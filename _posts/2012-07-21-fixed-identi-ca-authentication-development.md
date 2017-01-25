---
layout: post
title: Fixed Identi.ca authentication (development)
published: true
author: satanas
comments: true
date: 2012-07-31 07:07:17
tags: [ ]
categories:
    - desarrollo-2
    - noticias
permalink: /2012/07/fixed-identi-ca-authentication-development
---
The [Identi.ca authentication issue][1] in Turpial 2.0 have been fixed. In order to fetch this changes from development branch you need to update both github repositories (turpial and libturpial) and then remove the **~/.config/turpial** folder. This procedure will erase your current settings and all registered accounts but is completely necessary, otherwise Turpial won't run after update because a conflict with the old configuration files.

 [1]: http://dev.turpial.org.ve/issues/550