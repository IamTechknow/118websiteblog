---
layout: post
title: Design Checkoff
---

<p>Today we successfully passed the design check-off of our project! We had to complete the following tasks:</p>
<ul>
	<li>Bill of Materials</li>
	<li>System Block Design</li>
	<li>Mechanical Design Sketches</li>
	<li>Breadboard Tape Sensors</li>
	<li>Top 2 levels of State Machine</li>
	<li>Team Schedule</li>
	<li>Personal Schedules</li>
</ul>

In the last few days we updated the droid assembly in solidworks to include the caster wheel, pipe mounts, and bumper mechanism. To add the caster wheel we first found a model in GrabCAD which had a screw instead of a mount plate. We removed the screw and created our own mount plate to mate on top of the circular roller mechanism. We couldn't tell the exact placements of the screw holes until we received the caster wheels we ordered from Amazon, so for now we offset the center of each screw hole (with a 4-40 thread size diameter or 0.112 inches) from each corner with a 0.2 inches wide square. Since we need to screw in the mount plate to screw the wheel, we also have to create the holes on our base. Solidworks does not seem to allow a sketch to be transfered between a part and an assembly, so to improvise we first created a sketch of the holes in our assembly to look like it is on the base. Then we drew construction lines to define the center of the sketch in the base part before copying and pasting it. We also modeled our pipe mounts that we considered to secure the motors with the base to place screw holes for the motor mounts on the base. The shape of the pipe mounts is complex enough that we likely won't get the screw holes correct right away. We actually won't be using the pipe mounts, instead we will be use bendable metal hangar straps which are malleable enough to create a precise shape of a mount that will secure the motors we are using.

We also started working on the track wire sensor. We haven't started on filtering the signal yet but we found the inductors do not behave consistently, they will work and then they will introduce noise. We will create a schematc using an UAF42 active filter IC to create our band pass filter. Our band pass filter must attentuate when the IR beacon is close by, so we may need a 6th level or higher order filter to insure it doesn't interfere with our track wire sensors.

<p></p>

<p></p>
