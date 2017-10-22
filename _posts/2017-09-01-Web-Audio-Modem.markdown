---
layout: post
title: Web Audio Modem
source: https://martinmelhus.com/web-audio-modem/
category: HackerNews
description: SiteLog - How to build a modem in the browser using the  Web Audio API, allowing data transfer via audio.
numwords: 1274
hnscore: 
---

Lately, I've been working with a client where my development computer is not connected to the Internet. This is a huge inconvenience, as the unavailability of Google and Stack Overflow vastly impact my productivity. Only recently have I begun to grasp how much of my time is actually spent copy/pasting between Visual Studio and the browser.  My office also features an Internet connected laptop and my development computer expose 3,5 mm jack sockets for audio devices. And thus my problems can be solved! Here's how I made a modem for closing the gap with Web Audio.  PS If you just want to try the modem already, head over to the live demo. Also check out the source code on github.  Our modern era copy/paste implementation will be based on the Web Audio API which is supported by all major browsers. Most notably we'll leverage instances of OscillatorNode to encode data as an audio signal composed of sinusoids at preselected frequencies. The audio signal is decomposed using an AnalyserNode in ...

![](https://martinmelhus.com/content/images/2017/08/20170823-20170823_114735.jpg)
<!--description-->