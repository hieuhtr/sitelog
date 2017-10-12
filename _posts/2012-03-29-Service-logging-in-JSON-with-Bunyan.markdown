---
layout: post
title: Service logging in JSON with Bunyan
source: https://nodejs.org/en/blog/module/service-logging-in-json-with-bunyan
category: HackerNews
description: SiteLog - Service logging in JSON with Bunyan
numwords: 2023
---

Service logs are gold, if you can mine them. We scan them for occasional debugging. Perhaps we grep them looking for errors or warnings, or setup an occasional nagios log regex monitor. If that. This is a waste of the best channel for data about a service.

"Log. (Huh) What is it good for. Absolutely ..."

These are what logs are good for. The current state of logging is barely adequate for the first of these. Doing reliable analysis, and even monitoring, of varied "printf-style" logs is a grueling or hacky task that most either don't bother with, fallback to paying someone else to do (viz. Splunk's great successes), or, for web sites, punt and use the plethora of JavaScript-based web analytics tools.

Let's log in JSON. Let's format log records with a filter outside the app. Let's put more info in log records by not shoehorning into a printf-message. Debuggability can be improved. Monitoring and analysis can definitely be improved. Let's not write another regex-based parser, and use t...

![](/static/images/logo-hexagon.png)
<!--description-->