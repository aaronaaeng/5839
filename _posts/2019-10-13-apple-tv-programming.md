---
layout: category-post
title:  "Programming on an Apple TV"
date:   2019-10-13 12:10:00 -0700
categories: general
---

My first idea was ridiculous.  The remote has an accelerometer and a touchpad.  This means that by combining the motion of the remote and a swiping gesture direction, you can select a character.  It was inspired by an alternative to a standard keyboard that allowed users to move two large pads in various directions which would act as input selection.  It clearly wouldn't be ideal for something like the TV remote but it would be possible.  My next two designs were using the accelerometer to simulate pointer functionality.  This is how the Nintendo Switch simulates pointer functionality without a true IR pointer.  The first idea was to use an on-screen keyboard and to point at the characters to select them.  However, there is a better way to support input.  Block-based languages, like Scratch, already exist and would translate way better to this type of system.  By having the user point at the screen and drag blocks, these languages could be directly ported to Apple TV.

![Location Sketches]({{ "https://aaronaaeng.github.io/5839/assets/apple-sketches.png" }}){: .center-image }