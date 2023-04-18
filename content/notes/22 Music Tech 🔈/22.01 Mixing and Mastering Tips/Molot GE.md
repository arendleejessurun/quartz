---
tags: 
created: 2022-01-04, 22:12
modified: 2022-11-27, 19:40
---

# Molot GE

## Tips & tricks
Alpha mode has a very fast attack. Sigma mode has a very slow attack.[^1] Use alpha for transient suppression and sigma for transient shaping.[^2]

This is a good character compressor, almost like an LA2A, [[Tube compression]], or [[Diode-bridge compression]].[^3] It can be useful for warming things up. It has a similar saturation character as [[DC8C3]], but more aggressive due to having more odd harmonics. Kinda like a more dramatic [[MJUC]] Mk2, which makes sense since it does an 1176-type thing well.

The signal flow goes compressor, equalizer, limiter, saturator.[^2]

Sigma mode is really great for bringing some click out of a bass drum. The sidechain phase rotate button does something cool for helping the low end body of the bass drum stay intact too. It makes the the attack and release slower for the low frequencies.[^1]

Molot can do [[Feedback compression]].

Molot can also do negative compression in feedforward mode by turning on ratio inverse and relaxed mode.

Short releases have nice distortion in alpha mode.

Mid EQ emulates different left and right tolerances and can be made dynamic so it works only on the compressed signal. I like this for [[Compressing vocals]]. I can soften or accentuate the high mids.

Settings can be copied and pasted between Molot and Molotok.

To match Molotok perfectly, turn feedback off, relaxed release on, and saturate on.[^1]

Enable dual-stage, feedback, relaxed release, and put alpha-sigma halfway up to match beta mode in Molotok.[^1] This is best for buss compression.

Disable feedback and relaxed release, and enable sidechain phase rotation to match 0.2 on the alpha-beta-sigma knob.[^1]

In Molotok, switch to 0.3 on the alpha-beta-sigma knob to enable dual-stage mode and disable sidechain phase rotation.[^1]

Harder knee settings over 0.5 start to introduce a positive bump before gain reduction. Set it so transients happen around the knee to add more punch.[^1] High knee settings give the famous Molot sounds.[^2]

![[molot ge hard knee relaxed mode.png]]

In feedback mode, turning on inverse mode to enables the wrong transfer curve, which results in very gentle ratios.[^1]
![[molot ge feedback mode 4-1 relaxed on.png]]

In feedforward mode, inverse mode turns a 2:1 ratio into a limiter.
![[molot ge feedforward inverse 2-1 relaxed on.png]]

Any ratio above that starts ducking signals above the threshold.
![[molot ge feedforward inverse 3-1 relaxed off.png]]

Mid EQ has slight differences in the left and right channels to emulate analog tolerances. Double-click the logo to reset to a different random seed.[^1]

Opt + click sidechain phase button to switch the envelope follower from a vintage-style RMS detector to a more precise, mathematically correct raw Hilbert detector. This results in less bass distortion and a crisper treatment of transients.[^1]

The SSL bus compressor is designed so fast attack/release times result in less reduction.[^4] I noticed Molot does something similar in feedback mode.

## CPU
~0.3%

## Oversampling IR
Insane mode
![[molot ge impulse.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Settings maxed
![[molot ge sine sweep settings maxed.png]]

With lofi enabled
![[molot ge sine sweep lofi on.png]]

## CPU handling
~0.2% in eco mode, ~0.3 in precise, limiter on adds another 0.1%

## Harmonic analysis
Alpha mode has some built-in harmonics, even when it's doing nothing.
![[molot alpha harmonic.png]]

Saturation is pretty much the same in either alpha or sigma.
![[molot alpha with sat harmonic.png]]

## Hammerstein test
Saturation maxed
![[molot ge hammerstein.png]]

## Linear analysis of mid EQ
-12
![[molot ge linear analysis mid eq -12.png]]

+12
![[molot ge linear analysis mid eq 12.png]]

[^1]: [Introduction to Molotok and Molot GE](https://www.youtube.com/watch?v=JxVnt21eJV0)
[^2]: [Molot GE – Manual | Tokyo Dawn Knowledge Base](https://docs.tokyodawn.net/molot-ge-manual/)
[^3]: [Fetching Title#kx29](https://youtu.be/CjvxkSJG1YU)
[^4]: [Feedback Vs. Feed-Forward Compression: The Differences You Need to Know](https://sonicscoop.com/2018/11/07/feedback-vs-feed-forward-compression-differences-need-know/)
