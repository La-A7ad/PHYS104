---
parent: "[[L3b Dispersion and Prisms]]"
lecture: "L3b Dispersion and Prisms"
source_slides: "L3b slides 11 to 16"
tags: [PHYS104, recall, subnote]
---
Back to [[L3b Dispersion and Prisms]]

# Dispersive power and Abbe number

**Definition.** The angle of dispersion is $\theta = \delta_V - \delta_R$. The dispersive power is $\omega = \frac{\delta_V - \delta_R}{\delta_Y}$, which for a thin prism equals $\frac{n_V - n_R}{n_Y - 1}$. The Abbe number is $V = 1/\omega$ (L3b slides 13 to 14).

## Explanation
For a thin prism ($A \lesssim 10^\circ$), $\delta = (n - 1)A$ for every colour (slide 11), so $\theta = (n_V - n_R)A$. That grows with A, so θ is not a pure material constant (slide 13). Dividing by the mean deviation $\delta_Y = (n_Y - 1)A$ cancels A and leaves ω (slide 14), which:
1. has no unit,
2. depends on the material only,
3. is positive for normal dispersion,
4. is larger when there is more colour spread per unit of bending.

A high V (crown glass, V > 50) means low dispersion; a low V (flint glass, V < 50) means high dispersion.

![[L3b-s12-angular-dispersion.png]]
*Figure (L3b slides 12 to 13): the angular dispersion between the red and violet rays.*

## Worked detail: L3b-Ex2 recomputed
A 60.0° BK7 prism at minimum deviation, with $n_R = 1.5143$, $n_V = 1.5224$, $n_Y = 1.5170$ (slide 16):
- $\frac{60^\circ + \delta_R}{2} = \sin^{-1}(0.75715) = 49.21^\circ$, so $\delta_R = 38.43^\circ$
- $\frac{60^\circ + \delta_V}{2} = \sin^{-1}(0.76120) = 49.57^\circ$, so $\delta_V = 39.14^\circ$
- $\theta = 0.71^\circ$, $\omega = 0.0081/0.5170 = 0.0157$, $V = 63.8$: above 50, so low dispersion

The slide's 38.44°, 0.70°, 0.0156 and 64.1 are small slips; see [[L3b Dispersion and Prisms#Errata|L3b errata]].

## Recall
> [!question] Recall 1 · Calculation (L3b slide 14)
> A glass has $n_V = 1.6280$, $n_R = 1.6100$ and $n_Y = 1.6170$. Find ω and V, and classify the glass.

> [!success]- Answer
> ω = 0.0180/0.6170 = 0.0292; V = 34.3, below 50, so flint-type, high dispersion.

> [!question] Recall 2 · Explanation (L3b slide 14)
> Why does ω, unlike θ, not depend on the prism's apex angle?

> [!success]- Answer
> For a thin prism both θ = (n_V − n_R)A and δ_Y = (n_Y − 1)A are proportional to A, so A cancels in their ratio.
