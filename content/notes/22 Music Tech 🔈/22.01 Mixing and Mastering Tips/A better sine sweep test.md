---
tags: evergreen, 
created: Thursday, January 6th 2022, 2:11:31 am
modified: Friday, January 7th 2022, 11:02:37 pm
---

# A better sine sweep test
As I learned from Dan Worrall, a sine sweep stays at a constant loudness throughout the whole frequency range in a way that doesn't occur in most recorded sounds.^[ [Linear, Logarithmic, Exponential & Perspective](https://www.youtube.com/watch?v=rw-7fkEDmDw)] To solve this problem, I created a sine sweep test that decreased in volume the higher it went, in accordance to how real-world sounds decrease in volume at the higher frequencies. Because I know that pink noise is found in many sounds in nature,^[ [Pink noise - Occurence](https://en.wikipedia.org/wiki/Pink_noise#Occurrence)] I created a sine sweep that decreased in decibels per octave at the same rate pink noise decreases. To do so, I had to answer the question, [[At what rate does pink noise decrease in volume?]].

If I'm at 48kHz sample rate, the highest frequency I can replicate is 24k. So I worked backwards from there, dividing each decade until I reached a suitable lowest frequency. The sine sweep would start at 2.4Hz and linearly decrease in volume by 40dB once it reached 24kHz. In iZotope RX, I created a sine sweep that starts at -18dB and ends at -58dB.

[[Satin]] was my first test subject with this.

I decided to start the test tone at -16dB, which gives a 2dB margin on either side of my -18dB RMS gain stage target.
![[Screen Shot 2022-01-07 at 11.02.23 PM.png]]