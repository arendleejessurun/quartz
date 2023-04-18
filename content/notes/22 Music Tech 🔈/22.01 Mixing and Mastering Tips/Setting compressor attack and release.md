---
tags: mixing-secrets-for-the-small-studio level-rodeo 
created: 2022-02-26, 00:07
modified: 2022-12-11, 19:56
---

# Setting compressor attack and release
Attack time, simply put, is the amount of time it takes for the compressor to reach full gain reduction. A compressor begins compressing immediately, but it takes some time to wind up.[^1] An attack time of 100ms or greater will have a pumping effect on transient material with low-level stuff in it.[^2]

Release time, simply put, is the amount of time it takes to return to unity gain.[^1] A release time of 100ms or greater with have a breathing effect.[^2]

With this in mind, anything equal or greater than 100ms can be considered slow, and anything less can be considered fast.[^3]

These time constants usually work logarithmically.[^4] I can check the step transfer curves in Plugin Doctor.

Temporarily crank a compressor's threshold and ratio to better hear the effects of attack and release.[^5]

Use an oscilloscope to see how it changes.

Attack is how long it takes to apply compression. A fast attack softens transients and has the effect of pushing an element back.[^6]

Release is how long it takes to return to unity. Release times can effect the sustain. A too-fast release may have a weird ducking sound to it.[^6]

Alex Tumay says attack and release is much more important than how much gain reduction you're getting.[^7]

With max ratio, fast release, and a deep threshold, adjust the attack to your liking. After you've found the right attack setting, do the same for the release.[^8]

[[Attack and release for bass frequencies]].

[^1]: [[Audio Production and Critical Listening]] pg. 84
[^2]: [[Audio Production and Critical Listening]] pg. 89
[^3]: [5 Effective Ways to Use Compression in a Mix — Pro Audio Files](https://theproaudiofiles.com/compression-techniques/)
[^4]: [Are Compression Attack and Release times LYING TO YOU when mixing & mastering? - YouTube](https://www.youtube.com/watch?v=d-CvbKULDUY)
[^5]: [[Mixing Secrets for the Small Studio]] pg. 179
[^6]: [How Attack & Release Works in a Compressor - YouTube](https://www.youtube.com/watch?v=hWNgXOdREPE)
[^7]: [PRO MIXERS HATE THIS FREQUENCY (AES 2022 Panel) - YouTube](https://youtu.be/D_wI4VusNAo)
[^8]: [[Level Rodeo]] pg. 26