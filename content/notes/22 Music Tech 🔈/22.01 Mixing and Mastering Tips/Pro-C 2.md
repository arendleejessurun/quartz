---
tags: 
created: 2022-01-04, 21:54
modified: 2023-03-01, 23:09
---

# Pro-C 2

## Tips and tricks
I really like Opto mode as a leveler for vocals.

### Styles
- **Clean** - An allround, low distortion, feedforward, program dependent style (_originally from Pro-C v1_).
- **Classic** - A vintage, feedback, very program dependent style (_originally from Pro-C v1_).
- **Opto** - The manual says, "A relatively slow, very soft knee, more linear opto style (_originally from Pro-C v1_)", though you can make it fast, and one user says you can make it sound close to an 1176.[^3]
- **Vocal** - A very effective algorithm to bring vocals to the front of your mix. It works with automatic knee and ratio settings, so compressing your lead vocal is as easy as choosing the right threshold.[^1] The transfer curve is the same as RVox (see [[Pro-C 2 and RVox]]).
- **Mastering** - Designed to be as transparent as possible, introducing as little harmonic distortion as possible, while still being able to catch those fast transients.
- **Bus** - Especially great for bus processing, or for adding a pleasant glue to your drums, mixes or tracks.
- **Punch** - Traditional, analog-like compression behavior, sounds good on anything![^1] Kinda like an 1176.[^2] [^4]
- **Pumping** - Deep and over-the-top pumping, great for drum processing or EDM.[^1]

## CPU
0.1%, 0.2% with 4x OS.

## Oversampling IR
2x
![[pro-c 2 impulse 2x.png]]

4x
![[pro-c 2 impulse 4x.png]]

No big difference, so 4x OS should be my default for rendering.

## Sine sweep test at -18, spectrograph readings at -130dB, OS on

### Clean
Settings maxed, 2x OS
![[pro-c 2 sine sweep clean settings maxed 2x.png]]

### Classic
Settings maxed, no OS
![[pro-c 2 sine sweep classic settings maxed no os.png]]

### Opto
Settings maxed, 2x OS
![[pro-c 2 sine sweep opto settings maxed 2x.png]]

### Vocal
Settings maxed, no OS
![[pro-c 2 sine sweep vocal settings maxed no os.png]]

### Mastering
Settings maxed, no OS
![[pro-c 2 sine sweep mastering settings maxed no os.png]]

### Bus
Settings maxed, no OS
![[pro-c 2 sine sweep bus settings maxed no os.png]]

### Punch
Settings maxed, 4x OS
![[pro-c 2 sine sweep punch settings maxed 4x.png]]

### Pumping
Settings maxed, 2x OS
![[pro-c 2 sine sweep pumping settings maxed 2x.png]]

## Harmonic analysis

### Clean
![[pro-c2 clean harmonic.png]]

### Classic
![[pro-c2 classic harmonic.png]]

### Opto
![[pro-c2 opto harmonic.png]]

### Vocal
![[pro-c2 vocal harmonic.png]]

### Mastering
![[pro-c2 mastering harmonic.png]]

### Bus
![[pro-c2 bus harmonic.png]]

### Punch
![[pro-c2 punch harmonic.png]]

### Pumping
![[pro-c2 pumping harmonic.png]]

## Hammerstein test

### Clean
![[pro-c2 clean hammerstein.png]]

### Classic
![[pro-c2 classic hammerstein.png]]

### Opto
Cleaner than [[DC8C3]]'s Smooth setting.
![[pro-c2 opto hammerstein.png]]

### Vocal
![[pro-c2 vocal hammerstein.png]]

### Mastering
![[pro-c2 mastering hammerstein.png]]

### Bus
![[pro-c2 bus hammerstein.png]]

### Punch
Cleaner than [[DC8C3]]'s FET thing.
![[pro-c2 punch hammerstein.png]]

### Pumping
![[pro-c2 pumping hammerstein.png]]
[^1]: [FabFilter Pro-C 2 Help - Dynamics controls](https://www.fabfilter.com/help/pro-c/using/dynamicscontrols)
[^2]: [What's Wrong With Stock Plugins? ReaComp - YouTube](https://youtu.be/FpXqYk1FoWA)
[^3]: [Emulating Vintage Compressors in Pro C2 - Gearspace.com](https://gearspace.com/board/music-computers/1262672-emulating-vintage-compressors-pro-c2.html)
[^4]: [FabFilter Pro-C 2 - User review - Gearspace.com](https://gearspace.com/board/reviews/1037083-fabfilter-pro-c-2-a.html)