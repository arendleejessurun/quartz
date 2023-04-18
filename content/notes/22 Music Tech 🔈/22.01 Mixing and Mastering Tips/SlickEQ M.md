---
tags: 
created: 2022-01-04, 22:20
modified: 2022-11-12, 18:57
---

# SlickEQ M

## Tips and tricks
All its filters use a parallel algorithm, which helps make them transparent.[^1]

The peaking filters' Q gets narrower the more you boost or cut. Q gets wider at higher frequencies.[^1]

The stereo width parameter of each band is equivalent to EQing just the side channel. To EQ only the mid channel, dial in the cut or boost then offset it with an equal and opposite change for the side.[^1]

Its exciters use inductor-style saturation,[^1] which is similar to that found in passive EQs.[^2] In its legacy version, the saturation is greater at the extreme high and low bands. Each band has its own frequency-dependent saturation.[^1]

Double-click the logo to randomize the stereo placement of each band, emulating analog tolerances.[^1]

Ctrl+click the low-cut filter to enable a phase shift on the low frequencies.[^1]

## CPU
~0.5%

## Oversampling IR
Insane mode
![[slickeq m impulse response sat maxed.png]]

Otherwise, oversampling didn't seem to do anything to the impulse.

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Exciters maxed, precise mode
![[slickeq m sine sweep sat maxed.png]]

## Hammerstein test
HF excite at 1k, 100%
![[slickeq m hammerstein hf excite 100.png]]

LF excite at 280, 100%
![[slickeq m hammerstein lf excite 100.png]]

[^1]: [Fetching Title#uzz8](https://youtu.be/fU86QXUisuE)
[^2]: [The Magic of Passive EQ - Sonarworks Blog](https://www.sonarworks.com/blog/learn/the-magic-of-passive-eq)
