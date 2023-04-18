---
tags: level-rodeo 
created: 2022-04-06, 12:10
modified: 2022-12-19, 22:30
---

# Parallel compression
Parallel compression can add energy.[^1] It produces a very similar effect to [[Upward compression]].[^2] Hugh Robjohns breaks down the differences and dubs parallel compression "uplift compression."[^3]

One approach is to use a fast attack time and boost highs and lows (the latter takes advantage of the [[Fletcher-Munson curve]]). This makes kick and cymbals, for instance, consistent. I've heard this called New York compression.

For a transparent approach, as outlined by Bob Katz in his book *Mastering Audio*, set a low threshold, low ratio (about 2.5:1), fast attack, medium release (250-350ms), peak-sensing, 20ms lookahead.[^4]

For a tone-shaping approach, also outlined by Bob, set the threshold around the [[Action range]] (going for at most 5-7dB of reduction), use a relatively soft knee to avoid artifacts, use a medium attack (about 125ms) to let the transients through—we're only focusing on low-level stuff, RMS-sensing.[^5] 

Slower attack times may increase the transient information when blended with the dry signal.[^6] When parallel compressing for "punch" like this, make sure the release is not too quick, otherwise everything else will come up.[^7] [[VCA compression]] is good for parallel compression. In general, [[Feedback compression]] works well in this case. Negative compression can be useful too for just bringing out more transient.[^8] [[Molot GE]] can do this, as can [[DC8C3]] and [[DC1A]].

Parallel compression lets you add more body without increasing the peak level. Use this when a client asks for more drums.[^9] Sara Carter uses two parallel compression tracks as well as a parallel distortion track.[^10]

Parallel compression is also useful for [[Controlling harsh high end]]. A [[Nonlinear process]] usually works on the low end first (see [[Use EQ before saturation]]).

[^1]: [Parallel Compression / Free Multitracks and Settings - YouTube](https://www.youtube.com/watch?v=Vm8dtXAfE6k)
[^2]: [[Level Rodeo]] pg. 28
[^3]: [Parallel Compression](https://www.soundonsound.com/techniques/parallel-compression)
[^4]: [[Level Rodeo]] pg. 29
[^5]: [[Level Rodeo]] pg. 30
[^6]: [Two "Secrets" to Effective Parallel Compression](https://www.youtube.com/watch?v=3i-cY4EQMoU&list=PL1sNd-gBgKcokKS0v14HYieHxmHsQS38V&index=9)
[^7]: [WHY NOBODY USES IT RIGHT!? 🤔 - YouTube](https://youtu.be/SZqNzKjPNWc)
[^8]: [Colin's Corner (In the Office) EP#10 - Feedback, Feedforward and Negative Compression - YouTube](https://youtube.com/watch?feature=share&utm_source=pocket_saves&v=gOIyzMIjmlQ)
[^9]: [Worst Mixing Mistakes Music Producers Make - YouTube](https://youtu.be/wM6mYSuaq2g)
[^10]: [Mixing Kick and Bass (for a full yet tight low end mix) - YouTube](https://youtu.be/j0wMg3ZgItM)