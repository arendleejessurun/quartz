---
tags: 
created: 2022-01-04, 18:22
modified: 2022-12-26, 23:16
---

# Satin

## Tips and tricks
[[Tape saturation]], delay, and flange emulator.

Vintage mode loses high frequencies earlier.[^1]

Pre-emphasis acts as a pre-record high-shelf boost, as defined by gap width and tape speed.[^1]

You can use it for the [[Dolby A mod trick]].[^2] 

Matt Boudreau says it works well with the workflow of boosting to its limits and then dialing it back.[^3]

Anti-aliasing and post-ring is not as good as [[Wow Control]], but it's easier to load up and render across an entire project, since oversampling is already engaged. Group functions are helpful too.

Benefits from Reaper's x2 oversampling.

More hifi than [[Wow Control]] on the 2buss.

One commenter says to use the Outside the club preset before a room or hall reverb.[^3]

Lower inches per second settings result in less high end detail. Warren Huart says the low bump of 15ips can sound great for drums.[^3]

## CPU
0.3%

## Oversampling IR
Some very slight post-ring
![[satin impulse modern.png]]

## Sine sweep test, spectrograph readings at -130dB, OS on
Modern, 3dB of drive
![[satin sine sweep modern 3db drive.png]]

Vintage, 3dB of drive
![[satin sine sweep vintage 3db drive.png]]

## Hammerstein test
Input gain at 6dB
It has a bump in the harmonics regardless of where the bump knob is set. Use this instead of [[Wow Control]] or [[Saturn 2]] when I want some saturation in the bass frequencies.

Modern
![[satin hammerstein modern.png]]

Vintage
![[satin hammerstein vintage.png]]

[^1]: [u-he Satin Basics, Part 1: Studio - YouTube](https://youtu.be/jZ_06w0zTu8)
[^2]: [WTF is a Compander? - YouTube](https://www.youtube.com/watch?v=ZRP5uI9mbzQ)
[^3]: [U-He Satin Review with Matt Boudreau - Warren Huart: Produce Like A Pro - YouTube](https://www.youtube.com/watch?v=rnnKEPqA0dE)
