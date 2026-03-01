---
layout: post
title: "Recovered Field Log — Day 19: First Boot"
date: 2026-03-05
categories: archive
---

**RECOVERED DOCUMENT — UNCLASSIFIED**
*Origin: Same field station.*

---

We got one running.

Liao wired a TR-16 to a PI-40 screen and a keyboard. Power from the generator we rebuilt with mechanical ignition. She spent two days reading the reference manual, writing hex values on graph paper, converting them by hand.

Her first program was four instructions. It wrote the letter A to the screen.

Four instructions. MOV to set the framebuffer address. MOV to write the character code. She had to look up the ASCII table in the appendix. She got the port address wrong twice — wrote to the scanner instead of the screen. The manual has a memory map diagram but the print is small and she was working by torchlight.

When the A appeared on the CRT, green on black, everyone in the room went quiet. Not because it was impressive. Because of what it meant.

It meant we could make these things do what we tell them.

She wrote a longer program the next day. Read a key from the keyboard, echo it to the screen. Then a loop — read, echo, read, echo. Then cursor movement. Then backspace.

By the end of the week she had a text editor. Forty columns wide, fifteen rows tall, running on a processor from 1984, displaying on a CRT that weighs more than my rucksack.

She typed "hello world" and it sat there on the screen glowing at us.

Jensen asked what happens next.

Liao said: now we put this thing on wheels.
