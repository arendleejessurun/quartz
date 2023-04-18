---
tags: 
created: 2022-07-05, 20:48
modified: 2022-11-06, 19:33
---

# Dolby A mod trick
The Dolby A is a 4-band compressor with a low-pass at 80Hz, a band-pass from 80Hz to 3kHz, a high-pass at 3kHz, and another high-pass at 9kHz.

The mod removes the low and mid bands, leaving just the high-mid and high band plus a little notch cut between 1kHz and 2kHz.

[[Satin]] models this with the A-type mod encoder. Bypass the tape sim and set decoder to "none" to use this trick.

Or emulate this with a dynamic EQ. For the high-mids, use a high-shelving boost of 10db at 3kHz with enough Q to make a dip below the corner frequency, a threshold of -45dB, -10dB range, medium attack, fast release. For the highs, use a high-shelving boost of 5db at 9kHz, a threshold of -45dB, -5dB range, medium attack, fast release.[^1]

[^1]: [Mixing Tips the "John Lennon" Dolby A Trick Effect. - YouTube](https://www.youtube.com/watch?v=iVPTqQRnkMI)