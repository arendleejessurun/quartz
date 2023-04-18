---
tags:
created: 2022-01-11, 12:56
modified: 2022-12-13, 17:14
---

# Feedback compression
In short, a feedback compressor listens to its output rather than its input.[^1] The detection circuit follows the gain-reduction circuit.[^2] A feedback compressor turns down the volume when it starts getting too loud, without anticipating the volume.[^3]

In a feedback design, the detector comes after the component that changes the level. This results in two things:
1. More transients,
2. Smoother compression since the detector is reacting to an already compressed signal.[^2]

Feedback compression can be helpful for [[Shaping transients to create depth]], bringing elements forward. Feedforward compression can be used for the opposite.

The 1176, LA2A, and SSL Bus Compressor are feedback compressors.[^4]

[[Molot GE]] can switch between feedback and feedforward. [[DC8C3]] can blend between feedback and feedforward.

Feedback can be more forgiving and musical than [[Feed-forward compression]].[^5]

[[Fabulous fake feedback trick]]

[^1]: [Introduction to Molotok and Molot GE](https://www.youtube.com/watch?v=JxVnt21eJV0)
[^2]: [Feedback Vs. Feed-Forward Compression: The Differences You Need to Know](https://sonicscoop.com/2018/11/07/feedback-vs-feed-forward-compression-differences-need-know/)
[^3]: [Feed-back and feed-forward compressor topology explained | blog:analog](https://blog.mixanalog.com/compressor-topology-explained)
[^4]: [Molot GE Manual](https://docs.tokyodawn.net/molot-ge-manual/)
[^5]: [U-He Presswerk compressor plug-in - Gearjunkies Review - Gearjunkies - Music tech news, Reviews, Videos, Synthesizers, Studio, Recording](https://www.gearjunkies.com/2015/06/u-he-presswerk-compressor-plug-in-gearjunkies-review/)