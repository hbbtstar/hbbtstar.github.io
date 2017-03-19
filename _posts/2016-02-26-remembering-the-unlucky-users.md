---
layout: post
title: Remembering the Unlucky Users
---

I was working on a fairly vexing bug a couple of weeks ago that I had kind of been avoiding. The details of the bug, as it happens, are mostly unimportant: what is important is that it affected almost nobody. The bug only presented itself to a few users, but for those users it made the data exceedingly unreliable and made a lot of the reporting they were doing useless.

The interesting thing is that the total affected events were so small that it was almost reporting noise: the events had gone unnoticed by any monitoring due to it, and had it not been for these few unlucky users we probably wouldn't have caught it.

This coincided with hearing about a service called [Rollbar](http://rollbar.com), a service that seems to really emphasize a user's individual experience (you can see a history of your users and the exceptions they're seeing). I haven't used it, but it got me thinking about the whole idea of user experience and error reporting. It's not something I had heard much about before, but I think it's a great idea: all too often we find ourselves as developers unaware of just how much our bugs are impacting things. A bug that only affects a couple of users (like the one above) might slip by monitors, or get dismissed as unimportant in favor of other bugs. In the meantime, however, what is otherwise a seemingly minor error in the grand scheme of the app is causing actual, sometimes job-wrecking distress to users who would otherwise be quite happy with it.

Normally, these users write in (as the ones in this case did) if that's the case, but often users suffer in silence (or don't know who to reach out to, if it's a large organization that's using your app or service) and while you're fixing what appears to be a more important bug you have users who are effectively 

As it happens, I think that it's a great idea: as developers, we should be 