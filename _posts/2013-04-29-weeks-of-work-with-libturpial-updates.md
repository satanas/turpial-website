---
layout: post
title: 'Weeks of work with libturpial: updates'
published: true
author: satanas
comments: true
date: 2013-04-29 06:04:37
tags: [ ]
categories:
    - desarrollo-2
    - noticias
    - oficial
permalink: /2013/04/weeks-of-work-with-libturpial-updates
---
The past weeks I have been working on new improvements for [libturpial][1] and one of the most important things that I accomplished is the isolation of modules. Well, that and the definitive fix for the memory leaks issue. The [http][2] module was migrated from [urllib][3] to [Requests][4], this solved the memory leaks issue and let me build a new structure for this module, now it only cares for GET and POST requests (as should be) and can be tested separately, outside a libturpial environment. After came the adaptation of [protocol][5] module, this means integration with the new http module and update the API version (v1.1) for the [Twitter implementation][6]. Finally, yesterday I was working with the [account][7] module, this integrates all the configuration part and now we can easily load the existing profiles of libturpial into a shell and make tweets, fetch the timeline, see our mentions and further. Modules that need to be improved yet are the [account manager][8] and the final integration into the [core][9]. With this I could make some unit test and start an official testing phase for a next stable release. That's all for now. EOF

 [1]: https://github.com/satanas/libturpial
 [2]: https://github.com/satanas/libturpial/blob/7bf609bc2ad104418bebe575c17f00f94a845437/libturpial/lib/http.py
 [3]: http://docs.python.org/2/library/urllib.html
 [4]: http://docs.python-requests.org/en/latest/
 [5]: https://github.com/satanas/libturpial/blob/7bf609bc2ad104418bebe575c17f00f94a845437/libturpial/lib/interfaces/protocol.py
 [6]: https://github.com/satanas/libturpial/blob/7bf609bc2ad104418bebe575c17f00f94a845437/libturpial/lib/protocols/twitter/twitter.py
 [7]: https://github.com/satanas/libturpial/blob/7bf609bc2ad104418bebe575c17f00f94a845437/libturpial/api/models/account.py
 [8]: https://github.com/satanas/libturpial/blob/7bf609bc2ad104418bebe575c17f00f94a845437/libturpial/api/managers/accountmanager.py
 [9]: https://github.com/satanas/libturpial/blob/7bf609bc2ad104418bebe575c17f00f94a845437/libturpial/api/core.py