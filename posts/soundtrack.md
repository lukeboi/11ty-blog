---
title: SOUNDTRACK. (A.K.A. The Guitar Project)
description: SOUNDTRACK. Is an art installation consisting of 50 computer-controlled guitars.
date: 2020-12-15
tags:
  - project
layout: layouts/post.njk
---
2021 update: this is an older post about Soundtracks. A more up-to-date summary is coming soon!

Imagine fifty guitars hanging from the ceiling of one small room, each controlled by a computer, being mechanically strummed in rhythm. This room-sized musical instrument is the premise for SOUNDTRACK, an ambitious art project I’m working on with a local artist [Charley Friedman](https://www.charleyfriedman.com/).

<iframe height="450" src="https://www.youtube.com/embed/9xeQy0V2tI8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" style="width:100%; max-width:750;" allowfullscreen></iframe>

We recently crowd funded over thirteen thousand dollars on [Kickstarter](https://www.kickstarter.com/projects/78577585/soundtrack) using our four-guitar proof-of-concept prototype. I’m currently building the final 50 guitar installation.

![4 guitar proof of concept](/img/4_guitar_concept.png)
Above: The four-guitar proof of concept, used in our kickstarter video

The earliest prototypes used an Arduino to the control the guitars, all wired to the box shown above. However, controlling 50 guitars from a single arduino isn't feasible. The final installation will feature some totally custom circuit boards using STM32 microcontrollers. Each guitar will have a circuit board which communicates with  and is powered by a power distribution board. I designed these boards using Altium, which is an industry standard PCB designer. I was introduced to Altium by [Jay Carlson](https://jaycarlson.net/), an engineer and friend of mine best known online for his [The Amazing 1$ Microcontroller guide](https://jaycarlson.net/microcontrollers/).

Each PCB on the guitar will be using firmwhere I wrote, which inclues a custom implmentation of the MIDI serial protocol, allowing it to be controlled by other MIDI-compatable tools. 

![Altium PCB design screenshot](/img/altium.png)
Above: The PCBs in Altium, a popular electronics design tool.

![Parts on the laser cutter](/img/laser-cutting-guitars-1.jpg)
Above: Laser cutting mounts for electronics and motors

To learn more, check out some of our project links and repositories below:

[My Altium PCB Board Design Files (on GitHub)](https://github.com/lukeboi/guitar-board)

[My Guitar Board code repository (on GitHub)](https://github.com/lukeboi/guitar-actuator)

[Kickstarter page](https://www.kickstarter.com/projects/78577585/soundtrack)

[Charley Friedman's Website](https://www.charleyfriedman.com/)

[Jay Carlson's Website](https://jaycarlson.net/)