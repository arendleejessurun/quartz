---
tags: 
created: 2022-03-07, 15:13
modified: 2022-12-19, 22:49
---

# ReaComp

## Tips and tricks
ReaComp can do [[Feed-forward compression]] as well as [[Feedback compression]] via the detector input.[^1]

Classic attack mode seems to make its grabby attack even grabbier.[^1] With this enabled, the ratio is reduced as the volume increases above the threshold (almost like a range control).[^2]

Some people use Weird knee to make it sound like an LA2A.[^3] It doesn't seem to perform as much gain reduction as the "normal" knee.[^2]

ReaComp has a pretty linear release curve.[^4]

Dan Worrall makes ReaComp into a fully functional [[Feedback compression|Feedback compressor]] with the [[Fabulous fake feedback trick]].

Consider trying [[Gain riding with ReaComp]].

## Sine sweep test at -18, spectrograph readings at -130dB
No OS
![[reacomp -18db gr 10.1 ratio 1ms attack 1ms release sine sweep.png]]

## Hammerstein test
[^1]: [What's Wrong With Stock Plugins? ReaComp - YouTube](https://www.youtube.com/watch?v=FpXqYk1FoWA&t=282s)
[^2]: [Reaper in the Weeds: ReaComp - Comprehensive Overview - YouTube](https://www.youtube.com/watch?v=T_DUZ65wiIs)
[^3]: [What is weird knee ?? - Cockos Incorporated Forums](https://forum.cockos.com/showthread.php?t=214101)
[^4]: [What's Wrong With Stock Plugins? ReaComp ReaVisited - YouTube](https://www.youtube.com/watch?v=7Yit769SN64)
