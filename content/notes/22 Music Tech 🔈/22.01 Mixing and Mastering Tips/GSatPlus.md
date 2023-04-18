---
tags: 
created: 2022-01-04, 22:35
modified: 2022-12-27, 19:41
---

# GSatPlus

## Tips and tricks
The saturation is "tube-based."[^1]

Has the ability to change channel modes natively, which could be useful for tolerance emulation stuff.

2x oversampling is enough for all modes, except Crisp. 

Fluctuation adds mid and side harmonics.[^2]

## CPU
~0.2% at 2x, comparable to [[Lindell 80]].

## Oversampling IR
4x
![[gsatplus impulse 4x.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Clean
![[gsatplus sine sweep clean.png]]

Warm
![[gsatplus sine sweep warm.png]]

Crisp
![[gsatplus sine sweep crisp.png]]

Classic
![[gsatplus sine sweep classic.png]]

## Hammerstein test

### Clean
Has a little bump around 5k.

Odd harmonics, 2 stages
![[gsatplus hammerstein clean odd harm 2 stages.png]]

Even harmonics, 2 stages
![[gsatplus hammerstein clean even harm 2 stages.png]]

### Warm
Dip at 10k, which could be useful for [[Controlling harsh high end]].

Odd harmonics, 2 stages
![[gsatplus hammerstein warm odd harm 2 stages.png]]

Even harmonics, 2 stages
![[gsatplus hammerstein warm even harm 2 stages.png]]

### Crisp
Like Warm, it has a 10k dip, but with higher harmonics.

Odd harmonics, 2 stages
![[gsatplus hammerstein crisp odd harm 2 stages.png]]

Even harmonics, 2 stages
![[gsatplus hammerstein crisp even harm 2 stages.png]]

### Classic
Odd harmonics
![[gsatplus hammerstein classic odd harm.png]]

[^1]: [Gearspace.com and TBProAudio announce GSat+ FREE Advanced Saturation Plug-In - Gearspace.com](https://gearspace.com/board/product-alerts-older-than-2-months/1349464-gearspace-com-tbproaudio-announce-gsat-free-advanced-saturation-plug.html)
[^2]: [Something isn't right about the SSL vintage drive plugin.. or is it the SSL fusion hardware?? 🤔 - YouTube](https://www.youtube.com/watch?v=AvaoDaXrF3U&t=1s)