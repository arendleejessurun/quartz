---
tags: 
created: 2022-12-20, 14:45
modified: 2022-12-28, 13:14
---

# Presswerk

## Tips and tricks
The LA comp preset has a nice mid scoop sound with a low-mid bump.

I like that it has a phase rotator. This may supplant [[MJUC]] for [[Compressing acoustic guitar]]. The DPR consists of an all-pass that goes before the compression, as well as one that follows.

The MS features are really great, especially in the easy view. This sounds beautiful on the mix bus.

The warmth control seems useful, like a low slew rate saturation. This could be useful for [[Controlling harsh high end]].

The expand button (which enables downward expansion on the dry signal) seems like a lot of fun to mess with. The manual says it can make things sound more lively.

The delay feature may be useful for transparency on bass instruments. Delay is different than lookahead. The attack envelope is not softened as it is in [[Pro-C 2]]'s lookahead. [[ReaComp]] acts like Presswerk too.[^1]

Dial the non-lin knob to the left to emulate classic compressors.[^2] Apparently inertia in [[Kotelnikov GE]] does something similar.[^3] I need to look into this to understand it better.

HQ enables 4x oversampling.[^4]

It can be easy to overdo it with the saturation, so be careful.[^5] After 30dB of saturation, it starts to break, even with HQ on.

## CPU
~0.2%, HQ induces ~0.5%. Comparable to [[MJUC]].

## Oversampling IR
![[presswerk impulse signal os on.png]]

## Sine sweep test at -18, spectrograph readings at -130dB, OS on
Oversampling is great when just compressing. Careful with the saturation though.

Saturation at 31dB, warmth at 0dB
![[presswerk sine sweept saturation 31db.png]]

Saturation at 12dB, warmth cranked
![[presswerk sine sweept saturation 12db warmth cranked.png]]

## Hammerstein test
Just saturation, no compression
![[presswerk saturation 0db.png]]

Same, but with warmth cranked
![[presswerk saturation 0db warmth cranked.png]]

Now with warmth back at 0 and dynamics cranked
![[presswerk saturation 0db dynamics cranked.png]]

With compression and pre saturation
![[presswerk ratio 2 thresh 30db pre saturation 0db.png]]

With compression and post saturation
![[presswerk ratio 2 thresh 30db post saturation 0db.png]]

[^1]: [The Least Exciting Compressor Feature - YouTube](https://youtube.com/watch?feature=share&utm_source=pocket_saves&v=p7Ol5FPvHfs)
[^2]: [Some Praise For U-He Presswerk! - Effects Forum - KVR Audio](https://www.kvraudio.com/forum/viewtopic.php?p=7312206&sid=1e0307c7a54b93037f1e5fa5f88718b8#p7312206)
[^3]: [Some Praise For U-He Presswerk! - Page 2 - Effects Forum - KVR Audio](https://www.kvraudio.com/forum/viewtopic.php?p=7315441&sid=5dd7c0a0742f467a48ea54030d73559d#p7315441)
[^4]: [u-he Presswerk review | MusicRadar](https://www.musicradar.com/reviews/tech/u-he-presswerk-619103)
[^5]: [u-he Presswerk review, u-he Presswerk article, Download u-he Presswerk](https://www.pluginboutique.com/articles/721-U-he-Presswerk-review-at-Resident-Advisor)