---
parent: "[[L3a Polarization]]"
lecture: "L3a Polarization"
source_slides: "L3a slides 10 to 15"
tags: [PHYS104, recall, subnote]
---
Back to [[L3a Polarization]]

# Malus's law

**Definition.** When polarized light of intensity $I_0$ meets an analyzer whose transmission axis makes angle θ with the light's polarization, the transmitted intensity is $I = I_0\cos^2\theta$ (L3a slide 11).

## Explanation
The field amplitude $E_0$ splits into $E_0\cos\theta$ along the analyzer's axis, which passes, and $E_0\sin\theta$ across it, which is absorbed. Intensity goes as amplitude squared, so the fraction transmitted is $\cos^2\theta$ (slides 10 to 11). As θ goes from 0° to 90° the output falls from $I_0$ to 0, passing $I_0/2$ at 45° (slide 12).

For a stack of sheets:
1. If the incoming light is unpolarized, halve it at the first sheet.
2. Multiply by $\cos^2$ of the angle between each pair of **consecutive** axes.

![[L3a-malus-curve.png]]
*Figure: $I/I_0 = \cos^2\theta$ for light that is already polarized (L3a slides 11 to 14).*

## Worked detail: L3a-Ex7 recomputed
Unpolarized light $I_b$; axes at 0°, 30° and 75° (slide 15).
- Sheet 1: $I_1 = I_b/2$
- Sheet 2, 30° from sheet 1: $I_2 = \frac{I_b}{2}\cos^2 30^\circ = \frac{I_b}{2}\cdot\frac34 = \frac38 I_b$
- Sheet 3, 75° − 30° = 45° from sheet 2: $I_3 = \frac38 I_b\cos^2 45^\circ = \frac38 I_b\cdot\frac12 = \frac{3}{16}I_b$

The slide's middle step drops the $\cos^2 45^\circ$ factor; see [[L3a Polarization#Errata|L3a errata]].

## Recall
> [!question] Recall 1 · Calculation (Tutorial 2, Q2 style)
> Polarized light of intensity $I_0$ meets an analyzer at 25° to its polarization. What fraction gets through?

> [!success]- Answer
> cos² 25° = 0.821, so 0.821 I₀ gets through.

> [!question] Recall 2 · Calculation (Assignment 1, Q2 style)
> Unpolarized light passes sheets at 0°, 30° and 75° and comes out at 12 W/m². What would come out with the 30° sheet removed?

> [!success]- Answer
> All three sheets: $\frac{I}{2}\cos^2 30^\circ\cos^2 45^\circ = 12$. Without the middle one: $\frac{I}{2}\cos^2 75^\circ$. Dividing, the new output is $12 \times \dfrac{\cos^2 75^\circ}{\cos^2 30^\circ\cos^2 45^\circ} = 12 \times \dfrac{0.0670}{0.375} = 2.1$ W/m².
