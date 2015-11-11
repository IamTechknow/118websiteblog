---
layout: post
title: Driving Solenoids
---

Among the parts we salvaged from a Xerox Laser Printer are a few solenoids. When brainstorming ammo collection we decided that solenoids were a better alternative towards keeping ping-pong balls in place instead of a servo because of its push and pull motion of a leveler. In this video we demo operating the solenoid by sinking and sourcing current. 

<video src="http://iamtechknow.github.io/118website/images/solenoid.mp4" width="640" height="360" controls></video>

We drive the solenoids similar to driving a DC motor - connect the solenoid to power with a kickback diode and the collector end of a TIP122 transistor. On experimentation we found the solenoids do what they intend to do but consume quite a lot of power, half an amp at 12 volts! We will look into creating a test harness to control the solenoid with the Uno32 stack, but if it doesn't work out we should stick with the servo.