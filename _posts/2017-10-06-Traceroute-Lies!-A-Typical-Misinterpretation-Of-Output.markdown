---
layout: post
title: Traceroute Lies! A Typical Misinterpretation Of Output
source: http://movingpackets.net/2017/10/06/misinterpreting-traceroute/
category: HackerNews
description: SiteLog - Traceroute can points to a link having terrible latency, but despite what it appears, it's easy to misread the output and jump to the wrong conclusion.
numwords: 662
hnscore: 
---

Sometimes a user with performance issues will proudly present me with a traceroute and point to a particular hop in the network and accuse it of being the problem because of high latency on the link. About 1 time in 1000 they are correct and the link is totally saturated. The other 999 times, well, let me explain.  Here’s a typical traceroute I might be sent by a user (IPs and hostnames are altered to protect the innocent):  the user cries, The link from atl-edge to ga-core is clearly all messed up because the latency goes from 20ms to 106ms!  Isn’t it amazing that the link in question apparently adds 90ms of latency, yet the link between hops 6 and 7 (the jump from east coast USA to the United Kingdom) appears to show no latency increase at all? In fact, isn’t it odd that the latency for every hop from 3 onwards is about the same?  I know that many people reading this will already know why this is, but for those who do not (and there’s no shame in that), this is indicative of there be...

![](http://static.movingpackets.net/2017/10/mp_traceroute_header_featured.jpg)
<!--description-->