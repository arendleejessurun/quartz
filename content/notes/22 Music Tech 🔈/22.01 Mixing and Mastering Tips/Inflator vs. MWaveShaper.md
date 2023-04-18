---
tags:
created: 2022-01-02, 13:33
modified: 2022-09-26, 13:43
---

# Inflator vs. MWaveShaper
[This video](https://www.youtube.com/watch?v=7gMcL26Hr4A) compares the two in a null test, with MWaveShaper emulating the curves of Inflator.

Gearspace user tviler figured it out.

> The waveshaping function of Inflator is:
>
> f(x) = A⋅x + B⋅x² + C⋅x³ - D⋅(x² - 2⋅x³ + x⁴)
>
> where the coefficients A, B, C and D are given by the Curve parameter:
>
> A(curve) = 1 + (curve + 50)/100
> B(curve) = - curve/50
> C(curve) = (curve - 50)/100
> D(curve) = ¹⁄₁₆ - curve/400 + curve²/(4⋅10⁴)
>
> This gives us the following resulting curves:
>
> At +50:
> 2⋅x - x²
>
> at 0:
> ³⁄2⋅x - ¹⁄₁₆⋅x² - ³⁄₈⋅x³ - ¹⁄₁₆⋅x⁴
>
> At -50:
> x + ³⁄₄⋅x² - ¹⁄₂⋅x³ - ¹⁄₄⋅x⁴
>
> The Clip 0 dB off mode:
> In this mode Inflator takes overshooting samples and maps them back under 0 dB. It uses the curve according to the shape parameter for levels up to 0 dB. The overshooting samples are mapped back down below 0 dB according to a curve similar to the +50 curve, ie. 2⋅x - x², regardless of what curve is set to.
>
> I didn't investigate the multiband mode. According to the manual it splits the signal into three bands, which are processed independently.[^1]

MWaveShaper has an edge over Inflator in that it can be oversampled.

[^1]: [Gearspace.com - View Single Post - Sony Oxford Inflator - Please Demistify?](https://gearspace.com/board/showpost.php?p=15125058&postcount=118)