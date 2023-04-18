---
tags: 
created: 2022-01-03, 00:47
modified: 2022-11-06, 20:55
---

# Creating a multiband linear phase crossover
- On the original track, uncheck "Master send" in Reaper's routing options.
- Send it to an aux.
- On this aux, create your crossover filters with linear phase filters.
	- With one instance of [[Pro-Q 3]], create a low-pass and route it to channels 5 and 6.
	- In another instance of the same, create a high-pass and route it to channels 3 and 4.
- Send the low-pass to an aux track for lows.
- Send the high-pass to an aux track for highs.
- Send the full range signal to an aux track for mids, then route the lows and highs with their polarity inverted, which will null those bands.
- Season each band to taste.[^1]

I use a two-band crossover for bass processing.

To create a matrix for bass DI and amp do the following:
- Have the DI route to channels 1 and 2 to the crossover then out on the same channels.
- Route the amp to channels 3 and 4 on the crossover then out the same.
- For the DI, send channels 1 and 2 to the low band.
- For the amp, send channels 3 and 4 with their polarity inverted to the high band, along with the full-range signal.

[^1]: [Reaper Tip: Make a 3 Band Linear Phase Crossover - YouTube](https://youtu.be/951MnO8M1Qs)