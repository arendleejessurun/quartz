---
tags: 
created: 2022-06-28, 18:35
modified: 2023-01-02, 15:48
---

# AnalogStage MK2

## Tips and tricks
Console emulator plug-in.

This softens electric guitars nicely.

- OpAmp: think SSL or API. Very forward.
- Transistor: has an exciting sparkle for vocals. Very forward.

It has some cool left and right tolerance differences. I made a preset in [[Volcano 3]] that does something similar.

Kind of a weird spike at F0 up near Nyquist when the input is cranked. However, this happens way above 3 VU of additional gain. This plugin seems best suited for subtle analog coloring, not huge distortions. I'd probably use [[Saturn 2]] or [[SDRR2]] for the latter.

Has built-in OS, so that makes it easy for just setting and forgetting.

## CPU
0.3%

## Oversampling IR
![[analogstagemk2 impulse tube.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on

### OpAmp
![[analogstagemk2 sine sweep opamp max.png]]

### Transistor
![[analogstagemk2 sine sweep transistor max.png]]

### Tube
![[analogstagemk2 sine sweep tube max.png]]

## Hammerstein test

### OpAmp
![[analogstagemk2 opamp hammerstein.png]]

### Transistor
![[analogstagemk2 transistor hammerstein.png]]

### Tube
![[analogstagemk2 tube hammerstein.png]]