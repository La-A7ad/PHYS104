---
parent: "[[L2 Refraction]]"
lecture: "L2 Refraction"
source_slides: "L2 slides 17 to 21"
tags: [PHYS104, recall, subnote]
---
Back to [[L2 Refraction]]

# Huygens' principle

**Definition.** Every point on a wave front acts as a source of spherical secondary waves, called wavelets, which travel forward at the wave speed of the medium. After a time Δt, the new wave front is the surface tangent to all the wavelets (L2 slide 17).

## Explanation
A wave front is a surface through the points of a wave that have the same phase and amplitude. Huygens treated light as a wave and used this construction to find where a front will be next:
- **Plane wave** (very distant source, such as the Sun): the new front is a parallel plane, vΔt ahead.
- **Spherical wave** (nearby source, such as a lamp): the new front is a larger sphere (slide 18).

![[L2-s18-huygens.png]]
*Figure (L2 slide 18).*

At a boundary the construction proves both laws of ray optics (slides 19 to 21):
- **Reflection**: the incident and reflected wavelets travel at the same speed, so two right triangles sharing a hypotenuse are congruent, and θ₁' = θ₁.
- **Refraction**: the wavelets travel at different speeds, so the triangles share the hypotenuse but have different legs, giving $\sin\theta_1/\sin\theta_2 = v_1/v_2$ and then Snell's law.

## Worked detail: one time step
Take Δt = 1.0 ns. In air each wavelet's radius is
$$c\Delta t = (3.00\times10^8)(1.0\times10^{-9}) = 0.30\ \text{m}$$
In glass with n = 1.50 it is $(c/n)\Delta t = 0.20$ m. A front entering the glass at a slant therefore falls behind on the glass side and turns toward the normal.

## Recall
> [!question] Recall 1 · Explanation (L2 slide 17)
> In Huygens' construction, what does each point on a wave front do, and how is the new front found?

> [!success]- Answer
> Each point sends out a spherical wavelet at the medium's wave speed; after Δt the new front is the surface tangent to all the wavelets.

> [!question] Recall 2 · Calculation (L2 slide 18)
> A spherical wave front from a lamp has a radius of 2.00 m. Where is it 1.0 ns later, in air?

> [!success]- Answer
> Each wavelet has radius cΔt = 0.30 m, so the new front is a sphere of radius 2.30 m.
