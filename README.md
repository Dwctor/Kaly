# Kaly

The Kaly is a 42 key DIY keyboard for those that seek an affordable and confortable split keyboard that is easy to build for first timers!

![Kaly](/Pictures/20230716_153452.jpg)

This keyboard has been heavily inspired on other projects, like the [Ferris Sweep](https://github.com/davidphilipbarr/Sweep) and the [Cantor](https://github.com/diepala/cantor).

If you want to see more images, feel free to go to the `Pictures` folder or visit [this post on Lemmy](https://lemmy.world/post/1589095). Also, I have made a [youtube video](https://www.youtube.com/watch?v=PhxM8o__9Xo) about the Kaly and the journey of going from a standard keyboard to building my own, please check it out!

## Why build a Kaly?

- All three thumb keys are reachable.
- Extremelly affordable (50$ with sales on parts)
- Cute Mascot!
- Easy to build (No diodes or difficult connectors)
- Strong Stagger on the pinky collumn.

## How to build a Kaly?

Sadly this is a WIP, I will be updating the repo with a build guide soon, however, you can follow the [Cantor's build guide](https://github.com/diepala/cantor/blob/main/doc/build_guide.md), as it is quite similar! The firmware for the Kaly will be released sometime soon and will be linked here. If you need it before that, feel free to contact me on discord (dwctor) as I have a working version for QMK/VIAL.

As for the parts list, you will need

- 2x PCB (The left and right half are the same)
- 42 Chocv1 Keys
- 42 Chocv1 Keycaps
- 2x TRRS jacks (PJ-320A)
- 2x Blackpill microcontrollers (STM32F401CC)
- 10x Rubber/Silicone feet (6 or 7 mm)

You can find the Gerber files needed to order the PCB on the `Gerbers` directory. Look for the .zip of whatever version you would like!

**If you end up building a Kaly, please send me a picture of it, it would make my day!**

## Can I use the Kaly (mascot) image for x?

The mascot and the use of it does not follow the same license as the rest of the repository. Please contact me on this. If it's for personal use, most likely I will accept it!

## What can I expect for future developments?

I plan on making a 36 key version and hotswap versions soon, so keep an eye out for them!

## I want to modify/create a variation of Kaly, where do I start?

You can find the Ergogen file at the `Layout` folder and the initial PCB's on the `KalyPCB/Steps` folder.
