---
layout: post
title:  "Raspberry Pi 2 Autonomous Car"
date:   2016-01-09 22:52:27 +0000
categories: raspberry-pi autonomous-car
---
![Lane Detecting]({{ site.baseurl }}/assets/detected-lanes.png)

Inspired by reading [this article](http://www.businessinsider.com.au/the-guy-who-first-hacked-the-iphone-is-now-making-a-tesla-beater-2015-12), I want to see how far I can get with my own homemade autonomous car using mostly stuff I had lying around. Mainly, a couple Raspberry Pi's (models B+ & 2) and an Arduino. For now I've got OBDII diagnostics, GPS and lane tracking systems in place.

![Lane Detecting Clip]({{ site.baseurl }}/assets/clip_1.gif)

I'm not sure why the screen capture turned out pink, you can still make out the traffic lines being detected in the lower half of the clip.

I've been obtaining diagnostics, GPS and video data for my short (< 2 mile) trip to work with some ideas of how to start analyzing the data. I'm currently limited by the temporary install of the Raspberry Pi 2 in my vehicle and have started on plans for a permanent solution. My current setup involves running everything through a 120 watt inverter plugged into the cigarette lighter outlet, a 22" monitor sitting in the passenger seat, and a Raspberry Pi 2 + camera module strapped to the rearview mirror...

![Lane Detecting]({{ site.baseurl }}/assets/raspberry-pi-car-1.png)

![Lane Detecting]({{ site.baseurl }}/assets/raspberry-pi-car-2.png)

and then I lug everything inside. I've got a few things on the upgrade/install list first!
