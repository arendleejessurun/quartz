---
tags: 
created: 2022-11-06, 22:43
modified: 2022-11-09, 19:25
---

# Setting up PreSonus FaderPort for Reaper
Reaper supposedly has native support for FaderPort, but it doesn't seem to work.[^1]

Logic mode (hold Next while powering on and then press Mute) seems to be the most stable.[^2]

Control Surface Integrator works fairly well on X-Touch One mode. I do miss having the previous and next buttons though.[^3]

I can also use midi information from it to control actions.[^4]

To control an FX parameter without midi:
- Create a new channel
- Insert a test tone with JS Tone Generator
- Remove the output from the master send (hold opt+click the routing button)
- Route the channel to the plugin
- Select the parameter, choose parameter modulation, then audio signal control and select the sidechain you've routed the signal to[^5]

This is especially useful for automation.

DrivenByMoss4Reaper may also work with my FP2.[^6] [^7]

[^1]: [Control surfaces - CockosWiki](https://wiki.cockos.com/wiki/index.php/Control_surfaces)
[^2]: [Faderport V2 (2018) and Reaper *SOLVED* - Questions & Answers | PreSonus](https://answers.presonus.com/38115/faderport-v2-2018-and-reaper-solved)
[^3]: [Installation and Setup · GeoffAWaddington/CSIWiki Wiki · GitHub](https://github.com/GeoffAWaddington/CSIWiki/wiki/Installation-and-Setup)
[^4]: [Midi Controlled - Control Surface in REAPER - YouTube](https://www.youtube.com/watch?v=gVPVY7LYAMs)
[^5]: [Using Faders to Control Parameters in REAPER - YouTube](https://youtu.be/6aV_Xh_vS_Q)
[^6]: [DrivenByMoss4Reaper release: Support for several hardware controllers - Page 41 - Cockos Incorporated Forums](https://forum.cockos.com/showthread.php?t=206610&page=41)
[^7]: [DrivenByMoss4Reaper release: Support for several hardware controllers - Page 52 - Cockos Incorporated Forums](https://forums.cockos.com/showthread.php?t=206610&page=52)