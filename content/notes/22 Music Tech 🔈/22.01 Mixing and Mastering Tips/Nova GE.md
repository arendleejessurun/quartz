---
tags: 
created: 2022-01-04, 22:16
modified: 2022-12-26, 23:26
---

# Nova GE

## Tips & Tricks
Has more dynamics options than [[Pro-Q 3]].

Dynamics are based on RMS.[^1]

[TDR Nova compressor transfer function | vladg/sound](https://vladgsound.wordpress.com/2015/12/05/tdr-nova-compressor-transfer-function/#more-1400)

## CPU
0.3% with EQ and dynamics in Precise mode.

## Oversampling IR
Insane+ mode
![[nova ge impulse insane+.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
![[nova ge sine sweep insane+.png]]

inf:1 ratio, precise mode
![[nova ge sine sweep limiter precise.png]]

## Upward compression transfer function
Only does 2:1 (inversely written as 0.5:1) and is static at a 12dB range. No controls over knee, but it's something between 3-6dB. I matched it as best as I could with [[TB Compressor 4]].
![[nova ge upward comp.png]]

## Hammerstein test
Insane+ mode
![[nova ge insane+.png]]

[^1]: [Introduction to NOVA and NOVA GE - YouTube](https://www.youtube.com/watch?v=1CHFv4mWQYM&t=102s)