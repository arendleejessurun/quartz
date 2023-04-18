---
tags: 
created: 2022-01-04, 18:36
modified: 2022-11-12, 19:05
---

# SlickEQ GE

## Tips and tricks.
64 bit internal processing.

The low band has a phase shift button that works just on that band, causing lower frequencies to lag behind. It can soften attack, subtly extend the bass, and just offer "color." It does not affect frequency magnitude like [[All-pass filters]].[^1]

Good for adding frequency-dependent saturation. Brit mode has dip before shelf, German mode has tilt shelves.

The mid band has proportional Q the more you boost or cut.[^2]

Use equal boosts and cuts with EQ saturation enabled to just apply gentle saturation to a frequency band.[^2]

The high-pass filter follows the EQ, so you can add saturation on the low end and then clean it up with the filter, without losing any of the harmonics. The other shape for the HPF features a bump an octave above the cut-off frequency.[^2] The HPF is 18dB/oct.

### EQ modes
British mode has a slight dip before its high shelf. Its mid band has a tighter Q for cuts.[^2]

German mode has even gentler filters than the American mode.[^2]

Soviet mode is more surgical for small cuts and boost, and gentler for larger cuts and boosts.[^2] Can do an SSL high shelf type of thing, with a slight dip before the boost. It has that SSL sizzle in general.

Japanese mode is the most surgical.[^2]

Has some custom analog models, like API and Pultec, [here](https://docs.tokyodawn.net/slickeq-custom-models-guide/).

The Pultec model switches between two distinct modes.

Mode A:
![[slickeq-custom-models-pultec-mode-a.png]]

Mode B:
![[slickeq-custom-models-pultec-mode-b.png]]

### Saturation modes
- **Linear**: "As clean as it gets, absolutely linear."
- **Silky**: "Dynamic saturation with an 'open' character. Generates low order, even and odd harmonics (average case)."
- **Mellow**: "Subtle warming. Generates a very low level odd order harmonics series with a dominant 3rd partial (average case)."
- **Deep**: "Dynamic odd order distortion with a distinct frequency dependent touch for increased depth and dimension."[^3] I like this one a lot.
- **Toasted**: "Crudely approximates the behavior of in/out transformers."
- **Excited**: "Exciter style saturation, enhances the perceived bandwidth."[^3] Has a bit of an upfront sound while remaining warm.
- **Funky:** "Input transformer behavior including magnetic hysteresis."[^3] I like this on uke a lot. This might be useful for other instruments in that frequency range. It seems to cut a little low mids and refocus it in the high mids.
- **Seven:** "A transient specific saturator."[^3] This is nice on clean [[Mixing electric guitar|Electric guitar]].

## CPU
0.2%

## Oversampling IR
Better than [[Lindell 80]]
![[slickeq impulse response.png]]

## Sine sweep test at -18, spectrograph readings at -130dB
Silky, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep mellow eq sat maxed.png]]

Mellow, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep silky eq sat maxed.png]]

Deep, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep deep eq sat maxed.png]]

Excited, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep excited eq sat maxed.png]]

Toasted, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep toasted eq sat maxed.png]]

Funky, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep funky eq sat maxed.png]]

Seven, out stage saturation maxed, EQ saturation maxed
![[slickeq ge sine sweep seven eq sat maxed.png]]

## Hammerstein test
Saturation maxed

### Silky
![[slickeq ge hammerstein silky.png]]

### Mellow
![[slickeq ge hammerstein mellow.png]]

### Deep
Almost the same as mellow, just less harmonics after 5k
![[slickeq ge hammerstein deep.png]]

### Excited
![[slickeq ge hammerstein excited.png]]
Also causes a 0.3dB increased crest factor when paired with a HP filter on a sine wave.

### Toasted
![[slickeq ge hammerstein toasted.png]]

### Funky
![[slickeq ge hammerstein funky.png]]

### Seven
![[slickeq ge hammerstein seven.png]]

[^1]: [SlickEQ GE – Manual | Tokyo Dawn Knowledge Base](https://docs.tokyodawn.net/slickeq-ge/#Low_Frequency_Band)
[^2]: [Introduction to SlickEQ and SlickEQ GE - YouTube](https://youtu.be/-z8v6hO9wBE)
[^3]: [SlickEQ GE – Manual | Tokyo Dawn Knowledge Base](https://docs.tokyodawn.net/slickeq-ge/#Output_Stage)
