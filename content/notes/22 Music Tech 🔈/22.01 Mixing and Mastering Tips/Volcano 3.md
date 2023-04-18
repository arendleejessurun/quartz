---
tags: 
created: 2022-07-03, 08:32
modified: 2022-12-28, 12:11
---

# Volcano 3

## Tips and tricks
Just using a high and low pass can really enhance a signal.[^1]

The Clean filter mode is just as linear as [[Pro-Q 3]].[^1]

All pass filters still use the different nonlinearity settings.[^3]

You can pan filters for cool stereo effects.[^2]

- [I] Perhaps I can use the all-pass to mimic Disperser. #idea 

### Navigation 
Use the mouse wheel or cmd+vertical drag to change the slope of the filter.

Use the mouse wheel with cmd to adjust the peak.

Use cmd+horizontal drag to adjust frequency panning. 

Use shift+drag to fine-tune settings. 

Use cmd+opt+click on the dot to change its shape.

Right-click to open a pop-up menu.[^5]

### Filter styles
1. _Classic_, "the original filter style taken from our award-winning FabFilter One synthesizer"
2. _Smooth_, "like the cream in your coffee."[^4] I like this on voice.
3. _Raw_, "a filter with lots of overdrive and exhibits a character of its own. Great for distortion guitar sounds"
4. _Hard_, "moderately distorting filter, with a nice clean whistle"
5. _Hollow_, "juicy moderate distortion with fairly much low-end self-oscillation."[^4] I like the depth; it tucks things back a bit.
6. _Extreme_, "for more wild sonic ideas"
7. _Gentle_, "a more smooth and clean general purpose style"
8. _Tube_, "with a warmer sound and nice overdrive, great for synth sounds"
9. _Metal_, "with a rough, sharper sound and distortion"
10. _Easy Going_, "a softer version of the _Tube_ filter"
11. _Clean_, "linear behavior with no drive or clipping at all"[^4]

## CPU
0.0-0.2% depending on OS. If I need a saturator, it would be good to reach for this first, since it only adds a bit of extra CPU to use oversampling.

## Oversampling IR
![[volcano 3 impulse signal 1k.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
6db drive, filter set at 10k
![[volcano 3 sine sweep 10k classic.png]]

## Hammerstein test
All these readings were done with an all-pass filter at 200 Hz.

### Classic
![[volcano 3 classic.png]]

### Smooth
Cool how this one dips the fundamental a bit.
![[volcano 3 smooth.png]]

### Raw
This one dips the fundamental too.
![[volcano 3 raw.png]]

### Hard
![[volcano 3 hard.png]]

### Hollow
This one dips the fundamental too.
![[volcano 3 hollow.png]]

### Extreme
This one dips the fundamental.
![[volcano 3 extreme.png]]

### Gentle
![[volcano 3 gentle.png]]

### Tube
![[volcano 3 tube.png]]

### Metal
![[volcano 3 metal.png]]

### Easy going
![[volcano 3 easy going.png]]

### Clean
![[volcano 3 clean.png]]

[^1]: [Introduction to FabFilter Volcano 3 - YouTube](https://youtu.be/a94R5T4dSsM)
[^3]: [MMTV: FabFilter - Volcano 3 Wide Sound | Eric Burgess - YouTube](https://youtu.be/-1WjxxROwmY)
[^2]: [Synthesizing snare drums with FabFilter Volcano 3 - YouTube](https://youtu.be/IyzXl0urbDU)
[^5]: [FabFilter Volcano 3 Help - Filter controls](https://www.fabfilter.com/help/volcano/using/filtercontrols)
[^4]: [FabFilter Volcano 3 Help - Display and workflow](https://www.fabfilter.com/help/volcano/using/display)