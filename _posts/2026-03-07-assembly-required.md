---
layout: post
title: "Recovered Field Log — Day 40: Assembly Required"
date: 2026-03-07
categories: archive
---

**RECOVERED DOCUMENT — UNCLASSIFIED**
*Origin: Same field station.*

---

Liao built the first mobile unit today.

It's not pretty. An Ironhorse motor bolted to a chassis plate, TR-16 processor mounted on top, Axiom scanner board zip-tied to the side, radio module hanging off the back. It looks like something a child would build from a bin of spare parts.

It works.

She wrote the firmware on the commander terminal — our name for the main CRT workstation now — then used the flasher module to beam it across. The flasher is another Axiom part: short-range, line-of-sight, writes compiled code directly into a target CPU's program memory. You have to be standing right next to the unit. She held the flasher board against the drone's chassis, pressed Ctrl+C on the terminal, and the status line printed OK.

The drone's motor spun up. It rolled forward three metres, stopped, turned, rolled back. A simple patrol loop. Four waypoints.

Then she gave it the scanner firmware. The drone swept its sensor, picked up our transponder signals, and transmitted coordinates back over the radio. Liao's receiver program printed them on the CRT. We could see ourselves on the screen, represented as numbers. Grid coordinates and transponder codes.

Martinez asked how fast we can build more.

That's the bottleneck. Every unit needs a CPU, and CPUs are finite. The warehouse had maybe sixty. Each one we use for a scout is one we can't use for a fighter or a hauler or a relay. And every unit needs firmware — someone has to sit at the terminal and write assembly, instruction by instruction, looking up port addresses in the manual, testing, debugging, iterating.

No compiler. No copilot. No copy-paste. Just the reference manual and whatever you can hold in your head.

Liao says the manual is the most valuable object we own. More valuable than the CPUs. You can scavenge a CPU from wreckage. You can't scavenge knowledge.

I asked her what happens if we lose it.

She said don't.
