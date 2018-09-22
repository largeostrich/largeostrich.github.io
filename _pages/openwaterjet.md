---
layout: single
title: "openwaterjet"
permalink: /openwaterjet/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/plainblue.png
  caption:
excerpt: 'Page for the openwaterjet/open electric surfboard project'
author: Peter Bennett
---

On GitHub [here](github.com/largeostrich/openwaterjet).

On Thingiverse [here](https://www.thingiverse.com/thing:3112554/).

## The Idea

So around Easter 2018 I was bored at home and had a thought: Electric surfboards are cool, but they're also really expensive - why can't I just build my own for less? Well, it looks like I probably can build my own one for less.

## The Cost

The commercially available electric surfboards on the market at the moment all seem to cost around £10k. I am a student. I do not have £10k. With the project all completed, this thing should hopefully cost about £500 all in, a much more reasonable price for a student like me.

## The Design

### Drive Units

Armed with a basic understanding of how OpenSCAD works, I began messing around with designs for drive units, constrained by what I knew I could reasonably print. The fiddling around in openscad continued for a while as I tried to determine quite how a waterjet unit should look, and what off-the-shelf components were availble for me to use

![OpenSCAD screenshot]({{ "/assets/images/openscadss.png" | absolute_url }})

### The Board

I should probably make the board simple for the best chance of success right? Weeeell I had free choice to build what I want, so I made it complicated. The basic board design is half way between a surfboard and a racing hydroplane motorboat. When its all finished, hopefully it'll look really cool. (That's half the point, right?) The front half is mostly made of polystyrene, and the rear is made up of plywood with a waterproof compartment for all our electronics, given we don't want that to get wet. n the end, the plan is to wrap this all in GRP, to make it strong enough to be used.

![Top View of Board]({{ "/assets/images/topview.jpg" | absolute_url }})

## The Build

### Drive Units

I started by printing the pair of drive units and assembling them with RC boat propshafts and propellers. The motors are 3kW Turnigy 4074 brushless inrunners, with watercooling jackets. These are fed by 6mm silicone hose (yellow in the photos), with ram intakes next to the main drive intakes, and exits in the main intake just ahead of the drive propellers.

![Side View of Drive Units]({{ "/assets/images/driveunitsideview.jpg" | absolute_url }})

### Control Systems

A bicycle brake lever is used to actuate a slide potentiometer, which is interpreted by an ATMega 328 microcontroller to feed signal to two 125A Hobbyking Red Brick ESCs. These take power from a 6S 20000mAh quadcopter LiPo battery pack to drive the motors. The control circuits have been soldered up and are working but I haven't done the heavy electrics yet.

![Control Systems]({{ "/assets/images/controlsystems.jpg" | absolute_url }})

### The Board

I don't have much to write here yet, but here's a picture of me holding the partially complete board, which sholud give you a sense of scale.

![Me, holding the board]({{ "/assets/images/holdingboard.jpg" | absolute_url }})

Hopefully around New Year time ish I should have more stuff, including me hopefully riding this thing for the first time (which, for comedy purposes, I fully intend to video).


