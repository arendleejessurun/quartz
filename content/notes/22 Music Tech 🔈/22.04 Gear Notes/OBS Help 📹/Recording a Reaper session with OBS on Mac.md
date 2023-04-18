---
tags: 
created: 2023-01-05, 13:10
modified: 2023-01-05, 14:44
---

# Recording a Reaper session with OBS on Mac
Use Loopback to capture Reaper audio.[^1] In OBS create a Display Capture.[^2] Create an Audio Input Capture and set device to Loopback Audio.

Another way is to use [BlackHole](https://existential.audio/blackhole/), create a Multi-Output Device with Audio MIDI Setup. In Reaper, change the Audio Device to this new Multi-Output Device. In OBS audio settings, select BlackHole as Mic/Auxiliary Audio. You can also use this method to separate audio tracks for editing later.[^7]

You can also record video with OBS and audio with Reaper.[^4]

I'd like to learn how to do the same with Focusrite loopback, that way I can minimize the amount of apps I have to use.[^5] Loopback inputs are 5 and 6.[^6]

[^1]: [How I make a REAPER Blog Video - my recording and streaming setup explained - YouTube](https://www.youtube.com/watch?v=DRB3YUrg0wk)
[^2]: [How to Use OBS Studio (Beginners Guide) - YouTube](https://www.youtube.com/watch?v=DTk99mHDX_I)
[^4]: [Recording Videos in REAPER (Through OBS) - YouTube](https://www.youtube.com/watch?v=E4R4wlfKdcw)
[^5]: [OBS not seeing Focusrite Loopback : obs](https://www.reddit.com/r/obs/comments/i85pci/obs_not_seeing_focusrite_loopback/)
[^6]: [How do I use the 'Loopback' feature on the Scarlett 3rd Gens? – Focusrite Audio Engineering](https://support.focusrite.com/hc/en-gb/articles/360006883140-How-do-I-use-the-Loopback-feature-on-the-Scarlett-3rd-Gens-)
[^7]: [HOW TO: Setup OBS on Mac to Capture Voice, Guitar, DAW, Camera & Screen - YouTube](https://www.youtube.com/watch?v=rYDbtvH5cR8)