---
parent: "[[L2 Refraction]]"
lecture: "L2 Refraction"
source_slides: "L2 slides 3, 6 and 9"
tags: [PHYS104, recall, subnote]
---
Back to [[L2 Refraction]]

# Snell's law

**Definition.** At a boundary between a medium of index $n_1$ (the side the light comes from) and one of index $n_2$, the angles measured from the normal satisfy $n_1\sin\theta_1 = n_2\sin\theta_2$ (L2 slide 6). An equivalent form is $\sin\theta_1/\sin\theta_2 = v_1/v_2$ (slide 3).

## Explanation
Three habits make Snell's law reliable:
1. Measure both angles from the normal.
2. Put the medium the light comes from on the left-hand side.
3. Through parallel slabs, the product $n\sin\theta$ is the same in every layer. The middle layers cancel out, so only the first and last media decide the final angle.

The law also tells you when no answer exists. If $(n_1/n_2)\sin\theta_1$ comes out larger than 1, there is no refraction angle: the light is totally reflected, as in the water-to-air section of [[L2 Refraction#Leaving water at steeper and steeper angles|L2]].

![[L2-snell-curve.png]]
*Figure: θ₂ against θ₁ at a water surface, n = 1.33 (L2 slides 6 and 11).*

## Worked detail: three slabs
Light in a slab of index 1.60 travels at 25.0° from the normal, then passes through slabs of index 1.40 and 1.20 into air. Since $n\sin\theta$ is the same in every layer:
$$1.00\sin\theta_{air} = 1.60\sin 25.0^\circ = 0.676 \;\Rightarrow\; \theta_{air} = 42.5^\circ$$
The 1.40 and 1.20 slabs only shift the beam sideways; they do not change the final angle.

## Recall
> [!question] Recall 1 · Calculation (L2 slide 6)
> Light in air meets crown glass (n = 1.52) at 40.0°. Find the angle of refraction.

> [!success]- Answer
> sin θ₂ = sin 40.0°/1.52 = 0.423, so θ₂ = 25.0°.

> [!question] Recall 2 · Prediction (Tutorial 1, Q4)
> Light passes through several parallel slabs into air. If you swap the order of the middle slabs, does the final angle in the air change?

> [!success]- Answer
> No. n sin θ is the same in every layer, so the final angle depends only on the first medium's index and angle.
