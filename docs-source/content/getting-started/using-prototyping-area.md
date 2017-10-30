---
title: "Using the prototyping area"
weight: 8
date: 2017-10-28T15:30:33+01:00
draft: false
---

You can add whatever hardware you like to the prototyping area. It's where you'll be connecting extra LEDs, buzzers etc. The column of holes along the board's left edge are connected to pins D0 to D8, Ground and Power. However all of the other holes are unconnected and can be used to attach your components together.

You write to a pin with: digitalWrite(D1, 1)
And read from a pin with: digitalRead(D0)

Similarly you can read from a button with: digitalRead(BTNA)

This image shows the basic setup:


![Board basics](/images/badge_basics_01.png)