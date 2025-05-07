---
layout: post
title: "Bluesky Integration"
categories:
  - feature
  - bluesky
  - integration
image: /assets/img/5249196432764824975.jpg
---

Awakari introduces the integration with Bluesky.
First, it started to consume posts being published by Bluesky via WebSocket.
So now public posts from Bluesky are also available for the filtering in Awakari.

Next, there's a new aggregator account: [@bluesky.awakari.com](https://bsky.app/profile/bluesky.awakari.com).
This account mirrors all Awakari public interests into Bluesky feeds.
So for any public interest the corresponding feed in Bluesky is available to follow.

![screenshot](/assets/img/5249196432764824976.jpg)

Previously public interests were available in Bluesky via [Bridgy Fed](https://fed.brid.gy/).
Example: [@OpenSource.activitypub.awakari.com.ap.brid.gy](https://bsky.app/profile/did:plc:yrsy5ti7krb6pbvrybo5qyoa).
These bridged accounts are deprecated and will stop working at some point in a future.
