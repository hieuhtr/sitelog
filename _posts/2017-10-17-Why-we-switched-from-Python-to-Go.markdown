---
layout: post
title: Why we switched from Python to Go
source: https://getstream.io/blog/switched-python-go/
category: HackerNews
description: SiteLog - Switching to a new language is always a big step, especially when only one of your team members has prior experience with that language. Early this year, we swi
numwords: 2251
hnscore: 
---

Switching to a new language is always a big step, especially when only one of your team members has prior experience with that language. Early this year, we switched Stream’s primary programming language from Python to Go. This post will explain some of the reasons why we decided to leave Python behind and make the switch to Go.  Go is extremely fast. The performance is similar to that of Java or C++. For our use case, Go is typically 30 times faster than Python. Here’s a small benchmark game comparing Go vs Java.  For many applications, the programming language is simply the glue between the app and the database. The performance of the language itself usually doesn’t matter much.  Stream, however, is an API provider powering the feed infrastructure for 500 companies and more than 200 million end users. We’ve been optimizing Cassandra, PostgreSQL, Redis, etc. for years, but eventually, you reach the limits of the language you’re using.  Python is a great language but its performance is...

![](https://getstream-blog.imgix.net/blog/wp-content/uploads/2017/10/image2.png)
<!--description-->