---
layout: post
title: Turpial is not dead
published: true
author: satanas
comments: true
date: 2013-02-06 03:02:03
tags: [ ]
categories:
    - noticias
    - oficial
permalink: /2013/02/turpial-is-not-dead
image:
    thumb: working.png
    feature: working.png
    source: N/A
disqus_identifier: '1268 http://turpial.org.ve/?p=1268'
---


People have been wondering if Turpial is dead. The short answer is: **No**.

Now let's go with the long anwser.

I've been working on the [migration of Turpial from Webkit to Gtk 3][2] and it hasn't been easy, a lot of work trying to implement the same we got with HTML and sadly our friends [Carlos Guerrero][3] and [Andrea Stagi][4] have been really busy lately so they haven't had a chance to collaborate as they wanted.

![Webkit Interfase](/img/posts/Turpial-Tweet-Box-257x300.png "Webkit Interfase")


  
Technically speaking, Gtk 3 has almost the same limitations than Gtk 2. Gtk.Treeview is still based on Cairo so you can't render clickable elements (as consequence there are no links, hashtags, mentions, etc), neither draw little clickable icons on top of tweets and no fancy stuffs like we did on Webkit. This made the migration much harder. It took me a lot of time to hack some widgets or create custom ones in order to get the same look & feel, and this brought a side effect: memory leaks.

Yes, memory leaks. Again. Fortunately not so critical as in Webkit but as harmful as any memory leak, hitting our performance like a big and heavy rock.

![Gtk 3 interface](/img/posts/2012-11-13-010352_1366x768_scrot-300x168.png "Gtk 3 interface")

  
Basically that was what I've been doing so far, struggling with Gtk 3 and trying to get a really nice and light interface. However, nothing is perfect. GNOME has taken some decisions about the future of their platform, talking about it as the "brand" and making things hard for developers, all that sh*t and the proper limitations of Gtk 3 made me step aside. That's it Gtk. Welcome Qt. Now I'm studying about Qt and QML to see if I finally can build the interface that I always have wanted for Turpial.

I have no plans of keeping Turpial 1.6 until I finish this research, Turpial 1.6 has been on service for a long time and it's time to give it the rest it deserves. Instead I'm going to take advantage of all the progress I did with Gtk 3 and I will release a Gtk 3 version with all the limitations that I talked before but on top of libturpial, this mean the same interface than 1.6 but with multi-account, multi-protocol and multi-column support. It won't be so bad anyway.

This limited version will be the 2.0 (as planned) and then I will keep working on Qt version to make the 2.5 (or 3.0) version with all the desired features. I hope to solve lots of issues with this decision and provide a decent update of our beloved bird.

That's all for now.

EOF

 [2]: http://turpial.org.ve/2012/10/post-mortem-note-about-webkit-in-turpial/
 [3]: https://twitter.com/guerrerocarlos
 [4]: https://twitter.com/4ndreaSt4gi
 [6]: http://turpial.org.ve/wp-content/uploads/2013/02/2012-11-13-010352_1366x768_scrot.png