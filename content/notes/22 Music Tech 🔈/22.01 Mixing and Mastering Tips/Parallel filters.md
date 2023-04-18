---
tags: 
created: 2022-09-30, 10:56
modified: 2022-11-21, 22:03
---

# Parallel filters
A parallel 12dB/oct high pass at 2kHz at unity gain produces a 6dB high shelf boost and a 2dB cut at 1kHz. At a 6dB/oct slope, the phase shift almost doesn't matter anymore, with the corner frequency effectively shifting a little lower.[^1]

![[Screen Shot 2022-09-30 at 11.16.53 AM.png]]

Use a parallel high pass to apply a shelving boost to multiple channels at once, with the added flexibility of controlling how much gain of each channel you send to the parallel high pass.[^1]

A parallel low pass with a 12dB/oct slope has an effect like the Pultec low end trick. When applying dynamic processing to this shape, a compressor turns into an expander at the dip just above the corner frequency, where the two are summed.[^1]

![[Screen Shot 2022-09-30 at 11.17.25 AM.png]]

Parallel bandpass filters are especially useful for bringing out more fundamental in your drum shells.[^2]

Flip the polarity of a parallel bandpass filter to produce a hard notch at the corner frequency. Turn down the volume of the parallel track to turn the notch into a cut. Turning down 6dB creates a ~6dB cut. Turning down 12dB creates a ~3dB cut. Send anything that you want to cut to this track. To make it dynamic, a downward expander becomes a downward compressor after the polarity is flipped.[^3]

![[Screen Shot 2022-09-30 at 1.01.04 PM.png]]

Use a parallel band-pass filter to boost and cut two tracks. Send both to the parallel channel with the polarity flipped on one. This results in a bell boost for one track and a notch for the polarity-flipped track. Back off the send gain to the notch track -6dB to turn it into a 6dB bell cut. Adjust the fader to dial in the cut and boost. Dan Worrall then uses a downward expander to dynamically ride this frequency region and allow each part to interact.[^4]

Send both to the parallel channel with the polarity flipped on one. This results in a notch filter for one track and a bandpass filter for the polarity-flipped track.[^4]

[^1]: [Parallel Filter Tricks: Highpass and Lowpass Filters - YouTube](https://youtu.be/le7oVIrt9oU)
[^2]: [Parallel Bandpass Filters - YouTube](https://www.youtube.com/watch?v=4hGBYs10ZAU)
[^3]: [Parallel Filters, Pro Level: Flip It And Reverse It - YouTube](https://www.youtube.com/watch?v=O8zIJ0A--lI)
[^4]: [Parallel Filters, God Tier: The Delta Channel - YouTube](https://www.youtube.com/watch?v=QyZbIbjvQVE)