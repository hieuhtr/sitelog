---
layout: post
title: Reverse Engineering an Eclipse Plugin
source: https://0x10f8.wordpress.com/2017/08/07/reverse-engineering-an-eclipse-plugin/
category: HackerNews
description: SiteLog - Introduction Firstly I want to note I’m not a security researcher, ethical hacker or at all competent at reverse engineering. I’m currently working as a Java de
numwords: 1900
hnscore: 
---

Firstly I want to note I’m not a security researcher, ethical hacker or at all competent at reverse engineering. I’m currently working as a Java developer but I’ve always had an hobby interest in computer security.  Recently I’ve been ever more interested in the security side of things and have been studying various topics, from binary exploitation, reverse engineering to WPA cracking. I decided I would start writing blogs on my learning; and the application of that learning. Even if nobody reads it at least I will have notes on previous projects, and I find that writing things down always commits my thoughts more thoroughly.  Today I had quite a bit of free time so I decided I would try my hand at reverse engineering. My experience with Java is sound having programmed commercially with it for a number of years, and Java decompilers can normally provide the exact source code (providing no obfuscation was undertaken), so reverse engineering something written in Java seemed like the best...

![](https://0x10f8.files.wordpress.com/2017/08/0-the-target-eclipse-class-decompiler.png?w=1200)
<!--description-->