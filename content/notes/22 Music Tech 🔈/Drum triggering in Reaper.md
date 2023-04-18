---
tags: 
created: 2023-01-02, 22:26
modified: 2023-01-02, 23:11
---

# Drum triggering in Reaper
In Reaper, use [[Dynamic split]] and select "Create chromatic MIDI item from slices."[^1]

You can also set up ReaGate with a fast attack and release, dial in hold to taste, and have it send MIDI to your sampler channel.[^2] Find the MIDI notes by opening the MIDI editor window and clicking "Named notes."[^4]

You can also use JS Audio To MIDI Drum Trigger.[^2] This renders each hit's velocity. Dial in the retrigger interval parameter to prevent glitchy double hits. The velocities created from this are often quiet, so this plugin is best used in conjunction with JS MIDI Velocity Control.[^3]

You can then use [[ReaSamplOmatic 5000]] for multi-velocity samples.[^5]

[^1]: [Drum Sound Replacement in REAPER - Midi - YouTube](https://www.youtube.com/watch?v=EULTya31X1g&t=63s)
[^2]: [Drum Sample Replacement in REAPER | The REAPER Blog](https://reaperblog.net/2015/02/drum-sample-replacement-in-reaper-four-methods-explained/)
[^3]: [Audio to MIDI Drum trigger JS Plugin (Rapid-fire Reaper Tutorials Ep65) - YouTube](https://www.youtube.com/watch?v=XtnuecwO8hM)
[^4]: [Using JS Audio to midi drum trigger - YouTube](https://www.youtube.com/watch?v=5_7jbzOx8pY)
[^5]: [Make Your Own Drum Trigger with JS: Audio to MIDI and ReaSamplomatic5000 - YouTube](https://www.youtube.com/watch?v=33U3nAPGiWY)