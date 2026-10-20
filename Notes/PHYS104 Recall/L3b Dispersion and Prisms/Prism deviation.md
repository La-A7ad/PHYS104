---
parent: "[[L3b Dispersion and Prisms]]"
lecture: "L3b Dispersion and Prisms"
source_slides: "L3b slides 6 to 8"
tags: [PHYS104, recall, subnote]
---
Back to [[L3b Dispersion and Prisms]]

# Prism deviation

**Definition.** The angle of deviation δ is the angle between the ray leaving a prism and the ray that entered it. For a prism of apex angle A in air: $\sin i_1 = n\sin r_1$, $n\sin r_2 = \sin i_2$, $r_1 + r_2 = A$ and $\delta = i_1 + i_2 - A$ (L3b slides 6 to 7).

## Explanation
Symbols: $i_1$ is the angle of incidence at the first face and $r_1$ the angle of refraction there; $r_2$ is the angle of incidence at the second face, inside the prism; $i_2$ is the angle of emergence; A is the apex (refracting) angle between the two faces.

Geometry: the normals at the two faces meet at a point O, where they make an angle of $180^\circ - A$, so $r_1 + r_2 = A$. Each face turns the ray the same way, by $i_1 - r_1$ and $i_2 - r_2$, and these add to $\delta = i_1 + i_2 - A$.

![[L3b-s07-prism-geometry.png]]
*Figure (L3b slide 7).*

Emergence (slide 8): $r_1$ can never exceed θc, and $r_2$ must not if the ray is to leave.
- $A \le \theta_c$: every ray leaves.
- $\theta_c < A < 2\theta_c$: only rays with $i_1$ above $i_{1,min}$ leave, where $\sin i_{1,min} = n\sin(A - \theta_c)$.
- $A > 2\theta_c$: no ray leaves.

## Worked detail
A = 60.0°, n = 1.50, $i_1 = 40.0^\circ$:
1. $\sin r_1 = \sin 40.0^\circ/1.50$, so $r_1 = 25.4^\circ$
2. $r_2 = 60.0^\circ - 25.4^\circ = 34.6^\circ$, below $\theta_c = 41.8^\circ$, so the ray leaves
3. $\sin i_2 = 1.50\sin 34.6^\circ$, so $i_2 = 58.5^\circ$
4. $\delta = 40.0^\circ + 58.5^\circ - 60.0^\circ = 38.5^\circ$

## Recall
> [!question] Recall 1 · Calculation (L3b slide 7)
> A ray enters a 60° prism at 50° and leaves at 52°. What is its deviation?

> [!success]- Answer
> δ = 50° + 52° − 60° = 42°.

> [!question] Recall 2 · Prediction (L3b slide 8)
> A prism of glass with n = 1.50 has an apex angle of 85°. Will any ray get through it?

> [!success]- Answer
> No. θc = 41.8°, so 2θc = 83.6°, less than 85°: the two inside angles cannot both stay at or below θc.
