---
tags: 
created: 2022-01-06, 02:02
modified: 2023-01-03, 21:00
---

# The case for not worrying about oversampling
Usually, one adds saturation in subtle amounts, which wouldn't cause much aliasing. Moreover, real-world audio signals have much less energy in the high frequencies.[^1] This led me to create [[A better sine sweep test]].

Also worth asking, [[At what decibel level does a signal become inaudible?]] If the aliasing is quiet enough, it may be imperceptible.

It's also important to weigh the benefits of oversampling with [[The hazards of oversampling]].

Counterpoint, stack enough nonlinearities, and tons of crazy aliasing can happen, without oversampling. The moral of the story is still: use nonlinearities with care.

[^1]: [Linear, Logarithmic, Exponential & Perspective](https://www.youtube.com/watch?v=rw-7fkEDmDw)