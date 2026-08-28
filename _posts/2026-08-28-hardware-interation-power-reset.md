---
layout: post
title: "Hardware Interation: Power Reset!"
project: rotarycell
project_name: RotaryCell
image: "/images/log/2026/08/hardware-interation-power-reset-01-mtdcl3xvlhml0.png"
---

I brought the prototype to the [RARS Gathering](https://www.rars.org/#GATHERING) this week, and everyone seemed to get a huge kick out of it! Having a few dozen people hammer at it for a few hours did, however, expose a problem.

For some unknown reason, the modem can get into some sort of locked/wedged state where it no longer makes or receives calls. This had happened once before, and I put in a "service reset" code you could dial to cycle the modem's software power button. Seems that wasn't aggressive enough, though. To reliably fix it requires manually power cycling the LilyGO board with its power switch.

Well, even if it is infrequent, having to open the whole phone to fix a problem is a no-go. So I added a hardware reset feature to the same PCB where the audio interface components live. It still fits comfortably into the available space, and having that board professionally made is a lot easier to justify now!

It still blows my mind how quickly you can design, redesign, and even iterate a PCB nowadays. Ought to be in my hands in a couple weeks!

![Pasted image](/images/log/2026/08/hardware-interation-power-reset-01-mtdcl3xvlhml0.png)
