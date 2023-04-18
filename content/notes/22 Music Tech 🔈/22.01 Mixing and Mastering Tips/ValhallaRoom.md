---
tags: 
created: 2022-09-27, 23:31
modified: 2022-11-10, 14:46
---

# ValhallaRoom

## Tips and tricks
The high cut filter is 12dB/oct. Settings between 3k/7.5kHz are suitable for larger spaces, with higher values being suitable for chambers, plates, and digital reverbs.[^1]

Early Size settings of 10-50ms will simulate smaller spaces, and greater values will simulate halls and cathedrals.[^2]

Early Cross is a crossfeed.[^2]

[Early controls](https://valhalladsp.com/2011/05/18/valhallaroom-the-early-controls/)

[Late controls](https://valhalladsp.com/2011/05/18/valhallaroom-the-late-controls/)

Useful for drum rooms. Use Large Room or Large Chamber. Use 15 to 30 milliseconds of predelay. Set decay between 0.3 seconds to just over 1 second. Start with Early Size between 10-30 msec, or 50-100 msec for a gated sound, or for simulating the flattening of the decay envelope produced by heavy limiting/compression or [[Tape saturation]]. Set Late Size to 0.5 or less, to produce the highest initial echo density. Set Late Bass should be set to 1.0X or less.[^3]

### Modes
- **Large Room**
	- Most "natural"
	- Shallower modulation depths are useful in obtaining a natural sounding decay
- **Medium Room**
	- More of a square than rectangle, as in the reflection patterns of Large Room
	- Initial echo density is the sparsest of the 4 algorithms, creating a wider stereo spread
	- The modulation is more random than Large Room, characteristic of many of the classic reverb algorithms as found in the early Lexicon boxes
- **Bright Room**
	- Slightly slower attack time than the other reverberation algorithms, characteristic of larger halls
	- Brighter, more "digital" than the other algorithms, in a good way
- **Large Chamber**
	- Like Large Room, but with a more even early echo density
	- The echo density of a small space, but the modal density of a large hall
	- Fairly colorless reverb that suits a wide variety of input sounds; used to emulate chambers, rooms, halls without imparting a specific space on the sounds
	- You hear the decay, not the walls[^4]
- **Dark Room**
	- Lo-fi, with noisy interpolation, no high frequencies above 11 kHz
	- Inspired by the Lexicon 224, the EMT250, and other vintage reverbs
	- The Late Size control can be used to adjust the speed of the flutter[^5]
- **Dark Chamber**
	- All frequencies above 1/4 the sampling rate are completely attenuated
	- The modulated delays are cleaner than the deliberately dirty delay modulation used in Dark Room
	- Fairly even initial echo density, similar to the Large Chamber reverb mode, but with deeper modulation and a much bigger size
- **Dark Space**
	- All frequencies above 1/4 the sampling rate are completely attenuated
	- The modulated delays are cleaner than the deliberately dirty delay modulation used in Dark Room
	- Lower initial echo density
	- A bit of a delay of the onset of reverberation with high settings of Late Size; also results in a wide stereo image[^6]
- **Nostromo**
	- Biggest sounding reverb in ValhallaRoom, with audible echos at the largest size settings that slowly evolve into a rich decay
- **Narcissus**
	- Nostromo's little sibling, with an initial denser decay
	- Lightest CPU hit[^8]
- **Sulaco**
	- Low CPU
	- Original goal was to produce a smaller room sound with small Late Size settings[^9]
- **LV-426**
	- Cross between Nostromo and Narcissus, but with a far higher earlier echo density
	- Slow attack[^10]

### Presets
Two vocal reverbs (one long, one short) and a drum room reverb from Don Gunn's Death Cab for Cutie VH1's Storytellers mix

`<ValhallaRoom pluginVersion=”1.0.4″ presetName=”DCfC-short vocal” mix=”1″ predelay=”0.190799996″ decay=”0.00650650635″ HighCut=”0.368456364″ earlyLateMix=”0.483999997″ lateSize=”0.109999999″ lateCross=”0.289999992″ lateModRate=”0.0545454547″ lateModDepth=”0.200000003″ RTBassMultiply=”0.333333343″ RTXover=”0.0909090936″ RTHighMultiply=”0.444444478″ RTHighXover=”0.530201316″ earlySize=”0.0238238238″ earlyCross=”0.699999988″ earlyModRate=”0.0383838378″ earlyModDepth=”0.0599999987″ earlySend=”0.109999999″ diffusion=”0.75999999″ type=”0.25″/>`

`<ValhallaRoom pluginVersion=”1.0.4″ presetName=”DCfC-long vocal” mix=”0.976999998″ predelay=”0.0494000018″ decay=”0.0200200193″ HighCut=”0.382550329″ earlyLateMix=”0.893000007″ lateSize=”0.899999976″ lateCross=”0.360000014″ lateModRate=”0.12525253″ lateModDepth=”0.300000012″ RTBassMultiply=”0.333333343″ RTXover=”0.062626265″ RTHighMultiply=”0″ RTHighXover=”0.597315431″ earlySize=”0.0222222228″ earlyCross=”0″ earlyModRate=”0.169696972″ earlyModDepth=”0″ earlySend=”1″ diffusion=”1″ type=”0.333333343″/>`

`<ValhallaRoom pluginVersion=”1.0.4″ presetName=”DCfC-drum room” mix=”1″ predelay=”0.0199999996″ decay=”0.0145145142″ HighCut=”0.442281872″ earlyLateMix=”0.653999984″ lateSize=”0.839999974″ lateCross=”1″ lateModRate=”0.0343434326″ lateModDepth=”0.439999998″ RTBassMultiply=”0.333333343″ RTXover=”0.0909090936″ RTHighMultiply=”0.444444478″ RTHighXover=”0.530201316″ earlySize=”0.192192197″ earlyCross=”0.100000001″ earlyModRate=”0.0909090936″ earlyModDepth=”0.0500000007″ earlySend=”0″ diffusion=”1″ type=”0.25″/>`[^7]

Realistic, small drum room
`<ValhallaRoom pluginVersion="1.0.5" presetName="SmallishDrumRoom" mix="0.300000012" predelay="0.0299999993" decay="0.00300300308" HighCut="0.530201316" earlyLateMix="0.5" lateSize="0.330000013" lateCross="1" lateModRate="0.0909090936" lateModDepth="0" RTBassMultiply="0.153333336" RTXover="0.0909090936" RTHighMultiply="0.444444478" RTHighXover="0.530201316" earlySize="0.0193193201" earlyCross="0.100000001" earlyModRate="0.0909090936" earlyModDepth="0" earlySend="0" diffusion="1" type="0"/>`

Compressed/gated drum room
`<ValhallaRoom pluginVersion="1.0.5" presetName="SmashedDrumRoom" mix="0.300000012" predelay="0.0299999993" decay="0.00300300308" HighCut="0.463087261" earlyLateMix="0.5" lateSize="0.49000001" lateCross="1" lateModRate="0.0909090936" lateModDepth="0" RTBassMultiply="0.153333336" RTXover="0.0909090936" RTHighMultiply="0.444444478" RTHighXover="0.530201316" earlySize="0.067467466" earlyCross="0.100000001" earlyModRate="0.0909090936" earlyModDepth="0" earlySend="0" diffusion="1" type="0.333333343"/>`

Slapback drum room
`<ValhallaRoom pluginVersion="1.0.5" presetName="SlapbackDrumRoom" mix="0.300000012" predelay="0.0299999993" decay="0.00300300308" HighCut="0.463087261" earlyLateMix="0.5" lateSize="0.49000001" lateCross="1" lateModRate="0.0909090936" lateModDepth="0" RTBassMultiply="0.153333336" RTXover="0.0909090936" RTHighMultiply="0.444444478" RTHighXover="0.530201316" earlySize="0.067467466" earlyCross="0.100000001" earlyModRate="0.0909090936" earlyModDepth="0" earlySend="1" diffusion="1" type="0.333333343"/>`[^3]

Dark Room starting point
`<ValhallaRoom pluginVersion="1.0.6" presetName="DarkStartingPoint" mix="0.289999992" predelay="0" decay="0.0265265256" HighCut="0.58523488" earlyLateMix="1" lateSize="0.720000029" lateCross="0.25999999" lateModRate="0.202020198" lateModDepth="0.430000007" RTBassMultiply="0.413333327" RTXover="0.0666666701" RTHighMultiply="0" RTHighXover="0.410067111" earlySize="0.0581581593" earlyCross="0" earlyModRate="0.0909090936" earlyModDepth="0.800000012" earlySend="1" diffusion="1" type="0.416666657"/>`[^5]

## CPU
[^1]: [ValhallaRoom: The High Level Sliders - Valhalla DSP](https://valhalladsp.com/2011/05/02/valhallaroom-the-high-level-sliders/)
[^2]: [ValhallaRoom: Early Reflections versus Early Energy - Valhalla DSP](https://valhalladsp.com/2011/05/04/valhallaroom-early-reflections-versus-early-energy/)
[^3]: [ValhallaRoom Tips and Tricks: Short Drum Rooms - Valhalla DSP](https://valhalladsp.com/2011/05/23/valhallaroom-tips-and-tricks-short-drum-rooms/)
[^4]: [ValhallaRoom: The Reverb Modes - Valhalla DSP](https://valhalladsp.com/2011/05/03/valhallaroom-the-reverb-modes/)
[^5]: [ValhallaRoom V1.0.6: Introducing Dark Room - Valhalla DSP](https://valhalladsp.com/2011/06/21/valhallaroom-v1-0-6-introducing-dark-room/)
[^6]: [ValhallaRoom Updated to Version 1.0.7. New reverb modes: Dark Chamber and Dark Space - Valhalla DSP](https://valhalladsp.com/2011/07/18/valhallaroom-updated-to-version-1-0-7-new-reverb-modes-dark-chamber-and-dark-space/)
[^7]: [Death Cab for Cutie's ValhallaRoom presets - Valhalla DSP](https://valhalladsp.com/2011/05/26/death-cab-for-cutie-on-vh1-tomorrow-night-special-appearance-by-valhallaroom/)
[^8]: [ValhallaRoom Updated to 1.0.8. Resizable GUI, new reverb modes - Valhalla DSP](https://valhalladsp.com/2011/09/19/valhallaroom-updated-to-1-0-8-resizable-gui-new-reverb-modes/)
[^9]: [ValhallaRoom Updated to Version 1.0.9. New Reverb Mode: Sulaco - Valhalla DSP](https://valhalladsp.com/2011/11/17/valhallaroom-updated-to-version-1-0-9-new-reverb-mode-sulaco/)
[^10]: [ValhallaRoom Updated to Version 1.1.0 - Valhalla DSP](https://valhalladsp.com/2012/04/23/valhallaroom-updated-to-version-1-1-0/)