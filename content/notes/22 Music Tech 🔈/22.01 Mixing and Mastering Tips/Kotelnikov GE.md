---
tags: 
created: 2022-01-04, 22:11
modified: 2022-11-27, 19:33
---

# Kotelnikov GE

## Tips and Tricks
Peak crests less than 2dB will yield more aggressive compression sounds. Peak crests from 2-8dB are the sweet spot. Anything more is very smooth.

Yin and Yang modes introduce some nonlinearities depending on how much gain reduction is applied. Yin focuses on low frequencies. Yang covers the high.

Inertia mode causes the compressor to react faster when more gain reduction is applied and slower when less is applied. It also limits GR to 16dB. This mode is similar to opto-couplers.[^1] This could make Kotelnikov useful in a vocal chain.

### Presets
1176 bass

```
<TDRKotelnikovGE thresholdParam="-15.5" peakCrestParam="Peak" softKneeParam="3.1" maxGRParam="12.0" maxGROnParam="Off" ratioParam="4.0" attackParam="2.7" releasePeakParam="33" releaseRMSParam="220" inertiaParam="Intertia" makeUpParam="2.6" dryMixParam="off" dryWetParam="0.0" dryMixModeParam="Dry Mix" outGainParam="0.0" keyHPFrequencyParam="150" keyHPSlopeParam="3.0" keyStereoDiffParam="0" keyStereoLinkParam="Advanced" keyStereoBalanceParam="Center" fdrVisibleParam="Off" fdrActiveParam="On" fdrTypeParam="Shelf B" fdrFrequencyParam="120" fdrAmountParam="62" yingParam="On" yangParam="Off" deltaParam="Off" bypassParam="Off" equalLoudParam="Off" qualityParam="Precise" modeParam="Stereo" grDispScaleParam="2" grDispModeParam="Gain Reduction" sidechainModeParam="INT SC"/>
```

1176 snare

```
<TDRKotelnikovGE thresholdParam="-21.8" peakCrestParam="Peak" softKneeParam="3.1" maxGRParam="12.0" maxGROnParam="Off" ratioParam="4.0" attackParam="0.99" releasePeakParam="201" releaseRMSParam="220" inertiaParam="Intertia" makeUpParam="8.5" dryMixParam="off" dryWetParam="0.0" dryMixModeParam="Dry Mix" outGainParam="0.0" keyHPFrequencyParam="150" keyHPSlopeParam="3.0" keyStereoDiffParam="100" keyStereoLinkParam="Advanced" keyStereoBalanceParam="Center" fdrVisibleParam="Off" fdrActiveParam="Off" fdrTypeParam="Bell A" fdrFrequencyParam="1000" fdrAmountParam="0" yingParam="On" yangParam="Off" deltaParam="Off" bypassParam="Off" equalLoudParam="Off" qualityParam="Precise" modeParam="Stereo" grDispScaleParam="3" grDispModeParam="Gain Reduction" sidechainModeParam="INT SC"/>
```

![[kotelnikov-ge-compressor-presets.pdf]]

## CPU
0.3% in Eco mode, 0.4% in Precise, 0.6% in Insane, 0.2% in Live.

## Oversampling IR
Insane mode
![[kotelnikov impulse.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Settings maxed
![[kotelnikov sine sweep settings maxed.png]]

With yin and yang enabled too
![[kotelnikov sine sweep settings maxed yin yang.png]]

## CPU handling
~0.3 in eco mode

## Hammerstein test
I don't think these analyses are accurate.

### Yin
![[kotelnikov hammerstein yin.png]]

### Yang
![[kotelnikov hammerstein yang.png]]

### Yin and yang
![[kotelnikov hammerstein yin and yang.png]]

[^1]: [Advanced Trickery with TDR Kotelnikov](https://docs.tokyodawn.net/advanced-trickery-with-tdr-kotelnikov/?utm_source=pocket_mylist)