---
tags:  
created: 2022-11-05, 20:23
modified: 2022-11-27, 19:49
---

# DC1A

## Tips and tricks
Bit of an asymmetric release.

I can match the attack with [[Pro-C 2]] in Punch mode and a 3ms attack.

At full-tilt, it's about 4:1 with a moderately soft knee. Relaxed mode is like 3.5:1. The transfer curve approaches infinity:1 and eventually turns into negative compression. At more moderate input values, it's more like 2.5:1.

Deep mode enables a side-chain HPF.

Relaxed mode offers longer time constants and less saturation.

Negative mode works like a limiter at ~90% mix. This is less aggressive than [[DC8C3]]'s limiter setting.

## CPU

## Step function
![[dc1a step function.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Benefits from Reaper's 2x oversampling.
![[dc1a sine sweep reaper 2x os.png]]

## Harmonic analysis
![[dc1a3 harmonic.png]]

## Hammerstein test
Pretty different from [[DC8C3]] Punch.
![[dc1a3 hammerstein.png]]