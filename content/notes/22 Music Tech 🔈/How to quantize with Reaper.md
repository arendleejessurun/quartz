---
tags: 
created: 2022-03-20, 19:23
modified: 2022-05-21, 18:52
---

# How to quantize with Reaper
Use [[MK Slicer]] with shift+q.[^1]

Another method is to split items by the measure.[^2] I can use tab-to-transient to split and then quantize downbeats.

The traditional method is to quantize with auto-crossfade and trim content behind turned off from the options drop-down.[^3] Then follow this with [[Fill gaps between selected items]].

To double-check that [[Dynamic split]] and [[Fill gaps between selected items]] has done right, [[Zooming|Zoom]] in and adjust crossfade as needed. Use cmd+] to cycle forward to next split item.[^4]

A workflow for quantizing an entire band would be to get a drum quantization that sits right then render it to [[How to create a tempo map with Melodyne|Create a tempo map with Melodyne]]. I can then hard-quantize all instruments to this new tempo map, which creates a tight groove with a human feel.

[^1]: [MK Slicer 2.0 - lua script for quick slicing, quantizing and more](https://forum.cockos.com/showthread.php?p=2255547)
[^2]: [Lock or Quantize Audio to Grid with Reaper](https://www.youtube.com/watch?v=PXCbvjU9t6Q)
[^3]: [Beat Detective Tutorial in Reaper (faster and easier than Pro Tools)](https://www.youtube.com/watch?v=N47FLgTkZyY&t=11s)
[^4]: [Drum Editing without Stretch Markers in REAPER](https://www.youtube.com/watch?v=8bCnk5kPkKA)
