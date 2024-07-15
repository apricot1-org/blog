---
layout: post
title:  "Down the Rabbit-Hole of emulators and microcontrollers"
date:   2024-07-15 22:45 +0900
---

_There were doors all round the hall, but they were all locked; and when Alice had been all the way down one side and up the other, trying every door, she walked sadly down the middle, wondering how she was ever to get out again._

## Hello, World (as they say).

A few months ago, I bought a Raspberry Pi Pico on a whim. I had no idea what
I wanted to do with it, I just knew that I wanted to buy it, in large part because
it was so small and so inexpensive (about 800 JPY these days).

When I got home, I started googling. I learned that there are _many_ resources
for developing / hacking on the pico. For starters, the official documentation
and data sheets from the Raspberry Pi Foundation are amazing.

After a few days of learning (translation: binging on youtube videos) about the
pico's capabilities, I had a crazy idea.

"What if I tried to build an NES emulator that runs on the pico?"

That idea morphed into "what if I built a handheld gaming device that used the pico
to do cycle-accurate emulation of the NES _and_ keeps input lag to an absolute minimum?"

I have no experience with writing emulators, no experience with building non-trivial
things with microcontrollers, or even any electronics experience to speak of (
besides following along with a Ben Eater video where he makes a 4 bit adder out
of ICs and a breadboard).

But I thought, "what the hell.. let's just try and see how far I get."

And of course, while I'm going down this adventure, I decided I may as well write
about my experience stumbling through the world of NES emulation and pico hacking
on a blog. So here we are.

Wish me luck!
