---
parent: "[[L2 Refraction]]"
lecture: "L2 Refraction"
source_slides: "L2 slides 10 to 16"
tags: [PHYS104, recall, subnote]
---
Back to [[L2 Refraction]]

# Critical angle and TIR

**Definition.** Total internal reflection (TIR) happens when light in a higher-index medium meets a lower-index medium at an angle of incidence larger than the critical angle $\theta_c$, where $\sin\theta_c = n_2/n_1$. No light is refracted; all of it reflects (L2 slides 10 to 11).

## Explanation
Set θ₂ = 90° in Snell's law: $n_1\sin\theta_c = n_2\sin 90^\circ$, so $\sin\theta_c = n_2/n_1$. This only has a solution when $n_1 > n_2$, which is why TIR never happens from air into water. The larger the ratio $n_1/n_2$, the smaller θc, and the more rays are trapped.

Uses (slides 14 to 16):
- A 45°-90°-45° glass prism turns a beam through 90° (or 180° with two reflections), because 45° is above glass's 41.8°. Binoculars and periscopes use this.
- An optical fiber has a high-index core inside a lower-index cladding, so light keeps reflecting along the core.

![[L2-critical-angle.png]]
*Figure: critical angle against the index of the medium the light starts in, into air and into water. The marked points use slide values: water 1.33, glass 1.50, diamond 2.42 (L2 slides 11 to 14).*

## Worked detail: L2-Ex3 recomputed
Light inside diamond (n = 2.42) meets the surface at 28°.
- Into air: $\theta_c = \sin^{-1}(1/2.42) = 24.4^\circ$. Since 28° > 24.4°, it is totally reflected.
- Into water: $\theta_c = \sin^{-1}(1.33/2.42) = 33.3^\circ$. Since 28° < 33.3°, part refracts into the water and part reflects.

Both match the slides.

## Recall
> [!question] Recall 1 · Calculation (L2 slide 11)
> Find the critical angle for crown glass (n = 1.52) in air.

> [!success]- Answer
> θc = sin⁻¹(1/1.52) = 41.1°.

> [!question] Recall 2 · Explanation (L2 slide 16)
> What would happen to light in an optical fiber if the cladding had a higher index than the core?

> [!success]- Answer
> There would be no TIR at the core-cladding surface, since TIR needs a drop in index. The light would refract into the cladding and leak away instead of being guided.
