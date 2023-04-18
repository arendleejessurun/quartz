---
tags: 
created: 2022-04-05, 10:39
modified: 2022-07-03, 14:24
---

# Have no fear about high-pass filtering
I did some investigation after watching [this Paul Frindle video](https://www.youtube.com/watch?v=73PbD6omOGQ&t=102s).

Sine wave 100Hz, soft clipper clipping 6dB. High pass at 50Hz and bell cut at 300Hz (third harmonic) -6dB restores crest factor to 0dB. I can use a Bessel at 70Hz if I need to cut higher. Bessel filters are gentler than [[Butterworth filters]], causing less phase shift and thereby less crest factor change. I found 1st and 2nd order Bessels cause the least change in crest factor.

The principle here is crest factor can be massaged back into place by doing a bell cut in the low mids. This is a sensible practice. Most of the time, the low mids are congested. This is also where the lower-order harmonics live, which will cause a [[Missing fundamental]] effect. So if I want to reduce subsonic information, I will also have to reduce the harmonics of the subsonics.

Using a clipper can also solve this issue, especially if you'd like the added benefits of clipping. I'd recommend [[FreeClip]]. I got cubic soft clip style to generate about the same harmonic balance as before.

The other interesting thing about high passing after distortion, is that the square wave seems to approach more of a triangle shape as the filter approaches the fundamental. This is not such a bad thing. Triangle waves have fewer dissonant high harmonics than square waves.[^1]

Interestingly enough, high pass filtering a triangle wave actually *reduces* rather than increases its crest factor. It begins to resemble more of a sine wave as it is filtered.

And a 36 or 48dB/octave cut at 50Hz with [[Pro-Q 3]] actually causes no change in crest factor. At this point, the wave looks most like a sine again. The peak does get about a decibel higher though. This would make this suitable for bass and kick drums.

Adding some resonance to the HPF also makes the crest factor change less dramatic.

Another weird thing is 24dB/octave causes more crest factor increase at 50Hz than it does at 80Hz. At 80Hz there is no crest factor change. It just gets a little louder on both peak and RMS levels. This is similar for 48 and 96 too. I don't know why this is. Maybe it's caused by where the phase is shifting.

So, in practice, have no fear about high pass filtering.

[^1]: [You Don't Understand Saturation](https://www.youtube.com/watch?v=YuojAtE8YCY&t=692s)