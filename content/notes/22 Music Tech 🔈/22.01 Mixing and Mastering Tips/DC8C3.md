---
tags: 
created: 2022-01-10, 22:41
modified: 2022-12-09, 17:58
---

# DC8C3

## Tips and tricks
In easy mode, smooth is slow and good for leveling. Punch is good for standard compression. Snap is VCA-style compression. Crush is FET-style compression.

I like this a lot for fast compression. It does a FET-type thing well on Punch mode for snare and vocals. Sounds a little more open than FETISH and [[MTurboComp]] at this task.

DC8C can do [[Feedback compression]] and also blend it with [[Feed-forward compression]]. However, it seems to half the ratio. Full feedback and SMASH mode at 20:1 is ~4:1 compression again, but the threshold needs to be adjusted -10dB. Negative mode allows you to use the ratio pretty much normally.

The saturation warms things up considerably.

The manual says that in snap mode, "A gain reduction around -2 dB might already be enough to spice up drums."

In full feedback mode, the ratio decreases considerably. Full feedback and a 20:1 ratio is closer to 4:1.

## CPU
0.1%

## Oversampling IR
2x OS
![[dc8c3 impulse 2x os.png]]

4x OS
![[dc8c3 impulse 4x os.png]]

8x OS
![[dc8c3 impulse 8x os.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Normal ratio mode, settings maxed, 2x OS
![[dc8c3 sine sweep normal ratio mode settings maxed 2x os.png]]

Smash ratio mode, settings maxed (except attack at 0.1), 8x OS
![[dc8c3 sine sweep smash ratio mode settings maxed attack .1 8x os.png]]

Limit mode, settings maxed (except no saturation), 4x OS
![[dc8c3 sine sweep limit mode no sat 4x os.png]]

## Harmonic analysis

### Yellow
![[dc8c3 harmonic analysis saturation mode yellow noon.png]]

### Red
![[dc8c3 harmonic analysis saturation mode red noon.png]]

## Hammerstein test

### Yellow
![[dc8c3 hammerstein saturation mode yellow noon.png]]

### Red
![[dc8c3 hammerstein saturation mode red noon.png]]

### Smooth
![[dc8c3 hammerstein smooth no sat.png]]

![[dc8c3 hammerstein smooth sat maxed.png]]

### Punch
![[dc8c3 hammerstein punch no sat.png]]

![[dc8c3 hammerstein punch sat maxed.png]]

### Snap
![[dc8c3 hammerstein snap no sat.png]]

![[dc8c3 hammerstein snap sat maxed.png]]

### Crush
![[dc8c3 hammerstein crush no sat.png]]

![[dc8c3 hammerstein crush sat maxed.png]]