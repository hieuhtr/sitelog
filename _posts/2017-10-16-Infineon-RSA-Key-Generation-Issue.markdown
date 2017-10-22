---
layout: post
title: Infineon RSA Key Generation Issue
source: https://www.yubico.com/2017/10/infineon-rsa-key-generation-issue/
category: HackerNews
description: SiteLog - We are committed to always improving how we protect our customers, and continuously invest in making our products even more secure.
numwords: 206
hnscore: 
---

Infineon Technologies, one of Yubico’s secure element vendors, has informed us of a security issue in their cryptographic firmware library. The issue affects TPMs in millions of computers, and multiple smart card and security token vendors.  For Yubico, the issue weakens the strength of on-chip RSA key generation, and affects some use cases for the PIV smart card and OpenPGP functionality of the YubiKey 4 platform. We’ve issued a security advisory on this issue.  FIDO U2F, OTP, and OATH functions of the YubiKey 4 platform are not affected. The YubiKey NEO, FIDO U2F Security Key and YubiHSM are not impacted, nor are the deprecated products YubiKey Standard and YubiKey Edge. Externally generated RSA keys are not affected.  Yubico estimates that approximately 2% of YubiKey customers utilize the functionality affected by this issue. We have addressed this issue in all shipments of YubiKey 4, YubiKey 4 Nano, and YubiKey 4C, since June 6, 2017.  At this time, we are not aware of any security...

![](https://www.yubico.com/wp-content/uploads/2017/10/crypto_600x300_FINAL.jpg)
<!--description-->