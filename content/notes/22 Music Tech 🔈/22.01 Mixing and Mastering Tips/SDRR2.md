---
tags: 
created: 2022-01-04, 18:08
modified: 2022-12-27, 23:29
---

# SDRR2

## Tips and tricks
Generally, HQ ON is best for high distortion, but has the adverse affect of post-ring. HQ ON+ is best for lower levels and doesn't have post-ring. This is because ON+ engages a linear phase filter.

Digi mode is great for dialing in even harmonics.

I like sandwiching the crosstalk feature between an encoder and decoder instance of [[MSED]]. It gives a cool, holographic sound (see [[Use a holographic sound on the mixbus]]).

- Tube: really nice on [[Mixing electric guitar|Electric guitar]].
- Desk: nice hi-fi sound. Introducing more stages seems to tuck it back a bit. It even has a transient shaper in there. This could be great for [[Mixing acoustic guitar]] and uke.

## CPU
0.2-0.3% with OS

## Oversampling IR

### Tube
HQ on
![[sdrr2 impulse tube hq on.png]]

HQ on+
![[sdrr2 impulse tube hq on+.png]]

### Digi
HQ on
![[sdrr2 impulse digi hq on.png]]

HQ on+
![[sdrr2 impulse digi hq on+.png]]

### Fuzz
HQ on
![[sdrr2 impulse fuzz hq on.png]]

HQ on+
![[sdrr2 impulse fuzz hq on+.png]]

### Desk
HQ on
![[sdrr2 impulse desk hq on.png]]

HQ on+
![[sdrr2 impulse desk hq on+.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on

### Tube
Drive at 3, HQ on
![[sdrr2 sine sweep tube 3db hq on.png]]

Drive at 1, HQ on+
![[sdrr2 sine sweep tube 1db hq on+.png]]

### Digi
First 4 harmonics, drive at 9, HQ on
![[sdrr2 sine sweep digi first 4 9db hq on.png]]

First 4 harmonics, drive at 9, HQ on+
![[sdrr2 sine sweep digi first 4 9db hq on+.png]]

Inf harmonics, drive at 5, HQ on
![[sdrr2 sine sweep digi inf 5db hq on.png]]

Inf harmonics, drive at 1, HQ on+
![[sdrr2 sine sweep digi inf 1db hq on+.png]]

### Fuzz
Drive at 6, HQ on
![[sdrr2 sine sweep fuzz 6db hq on.png]]

Drive at 3, HQ on+
![[sdrr2 sine sweep fuzz 3db hq on+.png]]

### Desk
Drive at 8, HQ on
![[sdrr2 sine sweep desk 8db hq on.png]]

Drive at 4, HQ on+
![[sdrr2 sine sweep desk 4db hq on+.png]]

## Hammerstein test

### Tube
Pretty even distribution of even and odd, like [[Saturn 2]].
1 stage, drive at 3
![[sdrr2 hammerstein tube 1 stage.png]]

2 stages
![[sdrr2 hammerstein tube 2 stage.png]]

3 stages
![[sdrr2 hammerstein tube 3 stage.png]]

### Digi
Even and odd harmonics can be dialed in independently.

#### Drive at 7, first 4 harmonics
1 stage
![[sdrr2 hammerstein digi first 4 1 stage.png]]

2 stages
![[sdrr2 hammerstein digi first 4 2 stage.png]]

3 stages
![[sdrr2 hammerstein digi first 4 3 stage.png]]

#### Drive at 5, inf harmonics
1 stage
![[sdrr2 hammerstein digi inf harm 1 stage.png]]

2 stages
![[sdrr2 hammerstein digi inf harm 2 stage.png]]

3 stages
![[sdrr2 hammerstein digi inf harm 3 stage.png]]

#### Even/odd weighting
Even harmonics maxed
![[sdrr2 hammerstein digi inf harm 1 stage even harm maxed.png]]

Odd harmonics maxed
![[sdrr2 hammerstein digi inf harm 1 stage odd harm maxed.png]]

### Fuzz
Mostly odd harmonics.
Drive at 6
1 stage
![[sdrr2 hammerstein fuzz 1 stage.png]]

2 stages
![[sdrr2 hammerstein fuzz 2 stage.png]]

3 stages
![[sdrr2 hammerstein fuzz 3 stage.png]]

### Desk
Even and odd harmonics. I noticed even harmonics increased the more I drove it.
Drive at 8
1 stage
![[sdrr2 hammerstein desk 1 stage.png]]

2 stages
![[sdrr2 hammerstein desk 2 stage.png]]

3 stages
![[sdrr2 hammerstein desk 3 stage.png]]

## CPU handling
~0.1% with HQ off