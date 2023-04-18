---
tags: 
created: 2022-10-17, 16:52
modified: 2022-10-25, 17:37
---

# Use mid-side nonlinear processing
Mid-side saturation effects the sum and difference of the two channels, rather than the two channels themselves, which results in more intermodulation distortion. This can result in more "gluey" mixes, depending on the source material. For plugins that don't have a mid-side mode, use [[MSED]] or another encoder/decoder. With MSED, you have the added bonus of being able to adjust input gains for the two channels, which may be especially useful, since the side channel will be a lot quieter than the mid.[^1]

I was inspired by Dr. MS to use [[SDRR2]] and [[MSED]] to crossfeed the mid and sides.

[^1]: [The Magic Of Mid Side - YouTube](https://www.youtube.com/watch?v=dD6_Bajj2DI)