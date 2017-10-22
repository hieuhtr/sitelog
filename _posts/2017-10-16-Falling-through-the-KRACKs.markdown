---
layout: post
title: Falling through the KRACKs
source: https://blog.cryptographyengineering.com/2017/10/16/falling-through-the-kracks/
category: HackerNews
description: SiteLog - The big news in crypto today is the KRACK attack on WPA2 protected WiFi networks. Discovered by Mathy Vanhoef and Frank Piessens at KU Leuven, KRACK (Key Reinst
numwords: 1243
hnscore: 
---

The big news in crypto today is the KRACK attack on WPA2 protected WiFi networks. Discovered by Mathy Vanhoef and Frank Piessens at KU Leuven, KRACK (Key Reinstallation Attack) leverages a vulnerability in the 802.11i four-way handshake in order to facilitate decryption and forgery attacks on encrypted WiFi traffic.  The paper is here. It’s pretty easy to read, and you should.  I don’t want to spend much time talking about KRACK itself, because the vulnerability is pretty straightforward. Instead, I want to talk about why this vulnerability continues to exist so many years after WPA was standardized. And separately, to answer a question: how did this attack slip through, despite the fact that the 802.11i handshake was formally proven secure?  For a detailed description of the attack, see the KRACK website or the paper itself. Here I’ll just give a brief, high level description.  The 802.11i protocol (also known as WPA2) includes two separate mechanisms to ensure the confidentiality and...

![](https://matthewdgreen.files.wordpress.com/2017/10/393px-4-way-handshake-svg.png)
<!--description-->