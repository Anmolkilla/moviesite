---
title: "Pegasus : Google Explains How Pegasus Spy On Iphones"
filetitle: pegasus-spyware
author: Anmol
category: news
date: 2021-12-23T16:35:35.628Z
tags:
  - posts
  - news
  - technology
image: /assets/blog/pegasus-spyware-01.jpeg
imageAlt: Pegasus Spyware
---
Earlier this year, it was reported that Israel-based firm 

NSO Group

 was engaged by governments to target activists, politicians and journalists. NSO Group is notorious for selling hacking solutions to high-profile clients. The firm used 



![Pegasus Spyware](/assets/blog/pegasus-spyware-02.jpeg "Pegasus Spyware")



## Pegasus — a spyware package — to hack smartphones, including iPhones

. Since the report has come to light the US has banned companies from doing any business with NSO Group, whereas 

Apple has sued the firm as well. Now,Google has detailed in a blog how Pegasus was used to hack iPhones. 

## How does the hacking begin

In the blog post, Google explained that NSO offers zero-click exploitation technology. In a zero-click attack, the hacker doesn’t send phishing messages or suspicious links as it works quietly in the background. “Short of not using a device, there is no way to prevent exploitation by a zero-click exploit; it's a weapon against which there is no defence,” said Google's Project Zero team that analyses and researches cybersecurity threats. On iPhones, Google said, the initial entry point for Pegasus is iMessage. So if the attacker has an AppleID username or phone number, they can target a victim.

## Using the fake GIF trick

The victim would get a GIF file but in reality, while the filename has .gif at the end, it really isn’t a GIF file. “Using this "fake gif" trick, over 20 image codecs are suddenly part of the iMessage zero-click attack surface, including some very obscure and complex formats, remotely exposing probably hundreds of thousands of lines of code,” Google explained. Apple, as per Google, has completely removed the GIF codepath that could lead to such attacks with iOS 15 in September 2021.

Using Extreme Compressions 

Gone are the days when bandwidth or storage is a big issue as it used to be. However, compression techniques were used in the 90s and are still being used. Google says that in the 90s, an image codec called JBIG2 was used to compress images where pixels can only be black or white. A lot of PDF files a few years ago were PDF likely had a JBIG2 stream in it. There are a lot of old algorithms that are still being used, which are exploited for attacks like Pegasus.

In an interview with Wired, Project Zero's Ian Beer and Samuel Groß said that the hacking is on par with elite natio-level spying. “This is on par with serious nation-state capabilities,” he says. “It's really sophisticated stuff, and when it's wielded by an all-gas, no-brakes autocrat, it's totally terrifying. And it just makes you wonder what else is out there being used right now that is just waiting to be discovered. If this is the kind of threat civil society is facing, it is truly an emergency.”