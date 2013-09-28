---
layout: post
title: "Request Access to Embedly's Realtime Data Stream"
author: Phil Leggetter
twitter: "@leggetter"
gplus: 115842503466861231289
categories: [realtime, data, api]
excerpt: "There aren't all that many sources of realtime data available, which is why most the realtime demos you'll see involve Twitter. So, it's great to see Embedly open up a new API that exposes a stream of anonymous Embeds."
tweetText: "See what others are Embeding right now with @Embedly's Stream API"
altTweetText: "A new source of realtime data: @Embedly's Stream by @leggetter"
---

There aren't all that many sources of realtime data available which is why most the realtime demos you'll see involve Twitter data. So, it's great to see [Embedly](http://embed.ly) open up a new API that exposes a stream of anonymous Embeds.

Embedly have built a demo to show off their new API - a realtime stream of image thumbnails called [Thumbnail River](http://dabble.embed.ly/thumbnail-river).

![Embedly Thumbnail River](/blog/img/embedly-thumbnail-river.png)

Embedly have used (*IMO, the slightly out-of-favor*) [SocketIO](http://socket.io) to push realtime data from their servers to the browser. The Embedly Stream API appears to be an HTTP streaming API since their demo [server code](https://github.com/whichlight/embedly-thumbnail-river/blob/966aa1b2f2e65fdd84a6cb3e423c1caebf81e7c6/server.js#L30) uses [hyperrequest](https://github.com/substack/hyperquest) to interact with it.

### Get Access

To get access to this new realtime data API you need to fill out [a form](http://embed.ly/stream#contact) and somebody from Embedly will get in touch. Looking at the source the form has an ID of `enterpriseForm`, but hopefully that doesn't mean access is restricted to potential enterprise customers as there are lots of great hacks that you could put together with this data.

If you get access to this realtime data source, and build anything, **please [get in touch](/contact)**.