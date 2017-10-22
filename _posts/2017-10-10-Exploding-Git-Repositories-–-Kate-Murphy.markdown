---
layout: post
title: Exploding Git Repositories – Kate Murphy
source: https://kate.io/blog/git-bomb/
category: HackerNews
description: SiteLog - Exploding Git Repositories – Kate Murphy
numwords: 429
hnscore: 
---

If you are an adventurous sort (and can handle a potential reboot) I invite you to clone this tiny repo:  Were you able to clone it? Unless you have quite a lot of memory (both RAM and storage) git was killed, ran out of memory, or you had to reboot. Why is this? It is a perfectly formed repo made of only 12 objects.  How does a tiny repo cause git to run out of memory? The secret is that git de-duplicates “blobs” (which are used to store files) to make repositories smaller and allow using the same blob when a file remains unchanged between commits. Git also allows de-duplication of “tree” objects (which define the directory structure in a repository). git-bomb tries to make a billion files, however it only has 10 references to the file blob and only has 10 tree objects in all.  This is extremely similar to the “billion laughs” (aka “XML bomb”) hence the name “git bomb”.  At the bottom there is a file blob containing “one laugh”:  There is one tree object that refers to this blob 10 ti...

![](https://kate.io/images/posts/git-bomb.png)
<!--description-->