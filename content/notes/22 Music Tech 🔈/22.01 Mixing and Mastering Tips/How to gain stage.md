---
tags: to/develop 
created: 2022-01-06, 23:21
modified: 2022-11-08, 19:38
---

# How to gain stage
Everything and anything that amplifies a signal can be called a [[What is gain?|Gain]] stage.

Gain staging is about balancing your signal, sometimes using several amplification stages, to achieve a quality sound without the extremes of [[What is noise?|Noise]] or [[What is clipping?|Clipping]].[^2] Record a signal at too low of a level, and you will have a lot of noise relative to the signal. Record a signal at too high of a level—anything above what we call 0 [[Decibels relative to full scale]], or 0dBFS for short—and you will have clipping.[^6]

Imagine you're at an indoor trampoline park: to optimize your amusement, your goal is to get as high off the floor as possible without hitting your head on the ceiling. You may have to sign a waiver promising you won't jump higher than 7 feet, even though the facility has 20-foot high ceilings, leaving even [the tallest person](https://en.wikipedia.org/wiki/Robert_Wadlow) with about 4 feet of headroom before they bump their noggin.

In digital audio land, you've got your [[What is the noise floor?|Noise floor]], your 0dBFS ceiling (here there be clipping), and headroom to allow yourself some safety.

In analog days of yore, engineers would try to push signals as close to 0 VU ([[Volume units]]) as possible, in order to reduce noise, and sometimes they'd push signals past 0 VU to get some of that legendary analog saturation (a form of soft clipping).

In early 16-bit digital days of yore, engineers would still to push signals close to 0dBFS to maximize the signal to noise ratio, leaving enough headroom to avoid digital [[What is clipping?|Clipping]], which tends to sound nasty. But now that we have nice things, like 24-bit and 32-bit recording, we don't need to worry as much as they did about the [[What is the noise floor?|Noise floor]].[^5]

-18dB in digital audio is equivalent to 0 VU in analog.[^7] Gain stage at -18dB [[What is RMS volume?|RMS]] to hit analog-emulated nonlinearities at the sweet spot.[^6]

Write about floating point mixing.[^6] Mixes exported at 24-bit that exceed 0dBFS will still clip. 

Unity gain is when a gain stage doesn't change the volume.[^7]

Write about signal path: audio file, plugins, fader.

Use an RMS meter when tracking to set your input in the sweet spot with enough headroom to not worry about clipping.

You don't need to worry too much about recording too quietly. [[At what decibel level does a signal become inaudible?]]

Gain staging is also important when using compressors, limiters, saturators, and any other dynamic processors. Your input gain effects how the processor responds.

It's also important to set your output gain of each plug-in in your chain. Set the gain of your busses after tracks have been summed to them. 

Write about how I gain stage. [[Balancing workflow]]

Beware gain staging material with a lot of transients, like drums. Gain staging with RMS may result in overs. Instead, I like to gain stage this kind of material to a peak of -9 or -6dB. Record with peaks at -12dBFS.[^3] It's normally recommended to not go over -6dBFS.[^1]

[^1]: [What is gain staging? | Antelope Audio](https://en.antelopeaudio.com/2022/03/what-is-gain-staging/?utm_source=pocket_mylist)
[^2]: [Gain Staging Like a Pro](https://www.sweetwater.com/insync/gain-staging/)
[^3]: [Gain Staging Secrets Every Great Audio Engineer Understands! - YouTube](https://youtu.be/TCBHysRV4vs)
[^4]: [What Is Gain Staging? - YouTube](https://www.youtube.com/watch?v=E0gvT2RHMXk)
[^5]: [Gain Staging In Your DAW Software](https://www.soundonsound.com/techniques/gain-staging-your-daw-software)
[^6]: [Gain Staging: What It Is and How to Do It](https://www.izotope.com/en/learn/gain-staging-what-it-is-and-how-to-do-it.html)
[^7]: [The secret of maximum loudness (part 1) - YouTube](https://www.youtube.com/watch?v=-10h7Mu5VP8)
