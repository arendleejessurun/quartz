---
tags: mixing-secrets-for-the-small-studio level-rodeo 
created: 2022-04-02, 17:43
modified: 2022-12-19, 22:06
---

# Use RMS compression to retain more of the attack
Using RMS compression in tandem with a longer attack time can keep the original attack envelope of the performance.[^1] [[Kotelnikov GE]], [[DC8C3]], and [[ReaComp]] all have RMS detection styles.

Opto styles generally have an RMS window of about 50ms or more.[^2]

Keep in mind that changing to RMS effectively changes how the threshold interacts with the signal, since RMS is quieter than peak.[^2]

[^1]: [Chapter 9: Compressing For A Reason](https://cambridge-mt.com/ms/ch9/)
[^2]: [[Level Rodeo]] pg. 15