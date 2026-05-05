---
title: Reflection
---

## Review of Module's Success

After reviewing my final product, I see that I did not accomplish many of the project requirements. This can mainly be attributed to a poor PCB design. Several of my footprints were not the correct mounting type or were too small. This led to further complications with getting things to work. The voltage regulator only worked a couple of times, due to having to correct several mistakes on the PCB, many of which were not permanent fixes. The only thing that worked somewhat well was the code, which did not include anything for the actual stepper motor I wanted to use. The code worked very well with the UART messaging protocol employed by the entire team and it successfully recognized steering commands, but that was evvidenced by simple LEDs to indicate which command had been received.

## Microcontroller/Module Startup Tip

The biggest tip I can give anyone going into EGR 304 or 314, is try to learn some basic coding in C. I didn't know how to code anything before EGR 304 and I struggled a lot because of it.

Other tips/advice include:

* Try other pins for the same function, since everything about the code might be correct, maybe you have a bad pin
* Don't be afraid to refresh MPLAB a few times, it might just be acting slow
* Make good use of the header files included in your MPLAB code, because they explain how all the functions change between updates

## Lessons Learned

1) I've learned a lot about coding, but mostly how even experienced coders usually just reuse old code or revise someone else's.

2) I've learned how important footprint sizes are to your PCB design.

3) Apparently, unlike through-hole mounts, there are different kinds of surface-mount components. Some have legs sticking out and some don't.

4) It's really important to build your prototype circuit on a breadboard first, to make sure it works.

5) Soldering is already hard if you don't have steady hands, but surface-mount is significantly harder.

6) Converting between different coding languages can be really difficult.

7) It's always good to have lots of test points, debugging buttons and LEDs when you're troubleshooting.

8) Constantly ask the teaching team to review your design, even if they said it's fine. Maybe they missed something.

9) Talk to multiple people, not just on your team, but also the teaching team. This helps you gain different perspectives.

10) Make sure you have multiple components, so that if 1 breaks or never works to begin with, you have at least 1 replacement.

## Recommendations for future students

1) To reiterate, the most important thing you can do for this class, is learn to code, if you don't already know how.

2) Get some practice with surface-mount soldering. It's an entirely different beast than through-hole, so you might need more practice.

3) GO TO OFFICE HOURS! Talking with the teaching team face-to-face will always help you in the end.

4) Try to get big assignments, like your schematic design, PCB design and BOM done early, so you can ask the teaching team where you messed up. This way, you can correct everything before submission.

5) You don't have to submit something perfect. Sometimes you will be submitting something really close to the deadline. It's okay if 1 or 2 assignments aren't perfect. You need to priortize sleep sometimes.