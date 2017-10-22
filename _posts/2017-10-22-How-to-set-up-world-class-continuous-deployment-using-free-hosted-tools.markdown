---
layout: post
title: How to set up world-class continuous deployment using free hosted tools
source: https://simonwillison.net/2017/Oct/17/free-continuous-deployment/
category: HackerNews
description: SiteLog - I’m going to describe a way to put together a world-class continuous deployment infrastructure for your side-project without spending any money. With continuous
numwords: 1047
hnscore: 
---

I’m going to describe a way to put together a world-class continuous deployment infrastructure for your side-project without spending any money.  With continuous deployment every code commit is tested against an automated test suite. If the tests pass it gets deployed directly to the production environment! How’s that for an incentive to write comprehensive tests?  Each of the tools I’m using offers a free tier which is easily enough to handle most side-projects. And once you outgrow those free plans, you can solve those limitations in exchange for money!  I’ll be using the code for my blog as an example. It’s a classic Django application, with a small (OK, tiny) suite of unit tests. The tests are run using the standard Django ./manage.py test command.  Writing a Django application with tests is outside the scope of this article. Thankfully the official Django tutorial covers testing in some detail.  Travis CI is an outstanding hosted platform for continuous integration. Given a small ...

![](https://avatars0.githubusercontent.com/u/9599?v=4&s=200)
<!--description-->