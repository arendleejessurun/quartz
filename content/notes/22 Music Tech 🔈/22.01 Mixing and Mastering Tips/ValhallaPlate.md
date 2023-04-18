---
tags: 
created: 2022-09-27, 23:43
modified: 2022-09-28, 14:26
---

# ValhallaPlate

## Tips and tricks
ValhallaPlate was analyzed and dialed in against an EMT 140 at [Avast! Recording](http://www.avastrecording.com/), used on Fleet Foxes records.[^1]

### Modes
- **Chrome**
	- Good starting point
	- Fairly neutral sounding plate
- **Steel**
	- Like Chrome, but darker
- **Cobalt**
	- More "distant" attack than Chrome and Steel
	- Fairly dark; resonance in the very low midrange, dialed in from a specific EMT140 we tested at Avast Recording here in Seattle
- **Brass**
	- Much sharper attack than the first 3 modes
	- If you listen to the signal 100% wet, it almost sounds like there is some dry signal in there
	- Fairly bright.
- **Aluminum** 
	- Higher modal density than the first 4 modes
	- With the SIZE parameter set >100%, Aluminum can sound much more like a chamber than a plate
	- Aluminum (and Copper & Unobtanium) have less metallic sound, and can sound much clearer
	- Fairly bright
- **Copper**
	- High modal density, but deeper and darker than Aluminum
	- Set the SIZE up to 200%, and add a touch of modulation, and you have an open sounding reverb that works on almost any source material
- **Unobtanium** 
	- High modal density, bright, with a longer high frequency decay than the other plates
	- Ecoplate sound, but without the metallic ringing artifacts
	- Turn up the modulation, and you have a perfect reverb for synths
- **Adamantium** 
	- Mono-in, stereo-out mode, with the dense upper midrange and lower modal density found in older plates
	- Lots of air
- **Titanium**
	- Mono-in, stereo-out mode
	- Darker tone color than Adamantium
- **Osmium** 
	- Mono-in, stereo-out mode
	- Dark tone color, with a booming low end that is befitting of the densest metal found in nature
- **Radium**
	- A chamber/plate hybrid that uses the equivalent of 2 parallel mono plates to preserve the stereo image of your input signal
- **Lithium** 
	- A lush chamber/plate hybrid, with a unique approach to the stereo image that is inspired by the "stereo" chambers found in some recording studios
	- Helps to preserve the input panning of signals, while still having a realistic fill of the stereo image over time[^2]

### Presets
Copy and paste into the plugin.

Abbey Road 1

`<ValhallaPlate pluginVersion="1.5.0dot25" presetName="Abbey Rd 1" Mix="1" PreDelay="0" Decay="0.34000000357627868652" Size="0" Width="0.5" ModRate="0.25990557670593261719" ModDepth="0" LowEQFreq="0.29816749691963195801" LowEQGain="0" HighEQFreq="0.5" HighEQGain="0" Type="0.083333335816860198975"/>`[^3]

## CPU

## Oversampling IR

## Sine sweep test at -18, spectrograph readings at -130dB, OS on

## Hammerstein test
[^1]: [Plate Reverb Tips | Valhalla Plugins](https://valhalladsp.com/2017/06/15/plate-tips/)
[^2]: [ValhallaPlate: The Reverb Modes - Valhalla DSP](https://valhalladsp.com/2015/11/08/valhallaplate-the-reverb-modes/)
[^3]: [Chamber & Plate Reverb | Valhalla DSP Plugins](https://valhalladsp.com/2017/05/23/chambers-and-plates-and-bears-oh-my/)