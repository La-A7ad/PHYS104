---
lecture: "L2 Refraction"
slides: "Lecture 2 PDF, slides 1 to 21"
textbook: "10th ed. sections 34.4, 34.5 and 34.7, pp. 905 to 917 (the course numbers this chapter 35)"
tags: [PHYS104, recall]
---
# L2 Refraction

[[PHYS104 Recall/Index|Course map]] · [[Recall Log]] · [[Glossary]] · Previous: [[L1 Nature of Light]] · Next: [[L3a Polarization]]

Every section starts with a question: answer it before you open anything. How it works: [[PHYS104 Recall/Index#How to use it|see the Index]].

## Goals
- [ ] Predict which way a ray bends when it crosses into a new medium.
- [ ] Relate the index of refraction to the speed of light in a medium.
- [ ] Use Snell's law in both directions across a boundary, including through parallel layers.
- [ ] Find the speed, wavelength and frequency of light inside a medium.
- [ ] Decide whether a ray can escape a medium, and calculate the angle where that changes.
- [ ] Use Huygens' principle to derive the laws of reflection and refraction.

## Warm-up
Two questions from [[L1 Nature of Light|L1]].

> [!question] L2-W1 · Calculation (L1 slide 10)
> A ray strikes a mirror at 25° from the mirror's surface. What is the angle of reflection, measured the way optics measures it?

> [!success]- Answer
> 90° − 25° = 65° from the normal. Optics measures angles from the normal, not from the surface.

> [!question] L2-W2 · Comparison (L1 slide 7)
> Which photon carries more energy: green light at 5.6 × 10¹⁴ Hz or infrared at 3.0 × 10¹⁴ Hz? By what factor?

> [!success]- Answer
> E = hf, so the green photon, by a factor 5.6/3.0 = 1.87.

## Crossing a boundary
> [!question] L2-Q1 · Prediction (L2 slides 3 to 5)
> Light travels from air into glass, where it moves more slowly. Predict whether the refracted ray bends toward or away from the normal. Then predict the reverse trip, from glass into air.

*Think first: commit to "toward" or "away" for each direction before opening the hint.*

> [!tip]- Hint
> L2 slide 3 links the two angles to the two speeds through their sines. Which angle must be smaller when the second speed is smaller? Stuck? Read [[Index of refraction]] first.

> [!success]- Answer
> **Refraction** is the change of direction at a boundary; the **angle of refraction** θ₂ is measured from the normal, like θ₁. The refraction rule (L2 slide 3) is
> $$\frac{\sin\theta_1}{\sin\theta_2} = \frac{v_1}{v_2}$$
> where $v_1$ and $v_2$ are the speeds in the first and second medium.
> - Air to glass: $v_2 < v_1$, so $\sin\theta_2 < \sin\theta_1$ and $\theta_2 < \theta_1$. The ray bends **toward** the normal.
> - Glass to air: $v_2 > v_1$, so $\theta_2 > \theta_1$. The ray bends **away** from the normal.
>
> The **index of refraction** $n = c/v$ (no unit, with $c = 3\times10^8$ m/s) packages the speed: slower light means larger n. The course takes n = 1 for air; every other medium has n > 1 (slide 4). So entering a higher n, bend toward the normal; entering a lower n, bend away. The relative index ${}_1n_2 = n_2/n_1$ compares the two media (slide 5). The angle between the refracted ray and the extended incident ray is the **deviation**, $\beta = \lvert\theta_1 - \theta_2\rvert$ (slide 4). The incident, reflected and refracted rays and the normal all lie in one plane.
>
> At a boundary, part of the light's energy is reflected and part enters the second medium (slide 3).
>
> ![[L2-s03-refraction.png]]
> *Figure (L2 slide 3): incident, reflected and refracted rays at an air-glass surface. Light slows in the glass ($v_2 < v_1$) and bends toward the normal.*
>
> ![[L2-s05-bending.png]]
> *Figure (L2 slide 5): (a) into a higher index the ray bends toward the normal; (b) into a lower index it bends away.*

> [!note]- Why it works
> When a wave front reaches the boundary at a slant, one edge enters the slow medium first and falls behind, so the front swings around. The sine rule is the exact form of that swing; slides 20 to 21 derive it from Huygens' principle, and the last section of this note walks through it.

> [!question] L2-Q1x · [Extension] Prediction
> A ray enters a glass block along the normal (θ₁ = 0). Does it bend? Does its speed change?

> [!success]- Extension answer
> It does not bend: $\sin\theta_2 = (v_2/v_1)\sin 0 = 0$, so θ₂ = 0. Its speed still drops, to c/n. Bending needs an angle; slowing down does not.

## Finding n from two angles
> [!question] L2-Q2 · Calculation (L2 slide 9, L2-Ex2 with new numbers)
> A beam of 600 nm light travelling in air strikes a transparent slab at 50.0° from the normal. The refracted beam travels at 30.5° from the normal. Find the slab's index of refraction, the speed of light inside it, and the angle of deviation.

*Think first: write the equation you would start from before opening Hint 1.*

> [!tip]- Hint 1
> Use Snell's law with $n_1 = 1$ for air. Stuck? Read [[Snell's law]] first.

> [!tip]- Hint 2
> Solve for $n_2 = \sin\theta_1/\sin\theta_2$ first. The speed then follows from $n = c/v$.

> [!success]- Answer
> 1. **Snell's law** (L2 slide 6): $n_1\sin\theta_1 = n_2\sin\theta_2$, with $n_1 = 1$ for air.
> 2. $n_2 = \dfrac{\sin 50.0^\circ}{\sin 30.5^\circ} = \dfrac{0.7660}{0.5075} = 1.51$
> 3. Speed: $v = \dfrac{c}{n} = \dfrac{3.00\times10^8}{1.509} = 1.99\times10^8$ m/s
> 4. Deviation: $\beta = 50.0^\circ - 30.5^\circ = 19.5^\circ$
>
> The 600 nm is extra information: n comes from the angles alone. Slide check: L2-Ex2 (40°, 26°) gives $\sin 40^\circ/\sin 26^\circ = 1.47$, as the slide says.

> [!note]- Why it works
> Snell's law is slide 3's rule with each speed written as $c/n$: $\frac{\sin\theta_1}{\sin\theta_2} = \frac{c/n_1}{c/n_2} = \frac{n_2}{n_1}$. Two measured angles therefore fix the ratio of the indices, and with air on one side, the index itself.

> [!question] L2-Q2x · [Extension] Calculation
> Light passes from water (n = 1.33) into glass (n = 1.50), meeting the boundary at 40.0°. Find the angle of refraction.

> [!success]- Extension answer
> $\sin\theta_2 = \dfrac{1.33\sin 40.0^\circ}{1.50} = 0.570$, so $\theta_2 = 34.7^\circ$. It bends toward the normal, because it enters the higher index.

## Speed, wavelength and frequency in a medium
> [!question] L2-Q3 · Explanation (L2 slides 6 to 8; same skills as Tutorial 1, Q2)
> Yellow light with a vacuum wavelength of 589 nm enters water (n = 1.33). Of its speed, wavelength and frequency, which change, and to what values? Then explain why the one that stays fixed cannot change.

*Think first: decide which quantity stays fixed and why before opening the hint.*

> [!tip]- Hint
> Think about the wave crests arriving at the boundary each second, and the crests leaving it each second. Stuck? Read [[Wavelength in a medium]] first.

> [!success]- Answer
> The **frequency** stays the same; the speed and the **wavelength** both drop by the factor n (L2 slide 8). For any wave $v = \lambda f$ (slide 6).
> - Speed: $v = c/n = (3.00\times10^8)/1.33 = 2.26\times10^8$ m/s
> - Wavelength: $\lambda_m = \lambda_{air}/n = 589/1.33 = 443$ nm
> - Frequency: $f = c/\lambda = (3.00\times10^8)/(589\times10^{-9}) = 5.09\times10^{14}$ Hz, in air and in water
>
> Check with $v = \lambda f$: $(443\times10^{-9})(5.09\times10^{14}) = 2.26\times10^8$ m/s.
>
> For the same light in two media, $n_1\lambda_1 = n_2\lambda_2$, so the index is inversely proportional to the wavelength in that medium: $n \propto 1/\lambda$ (slide 8).
>
> ![[L2-s08-wavelength.png]]
> *Figure (L2 slide 8): the crests bunch up in the slower medium 2, so λ₂ < λ₁, while the frequency stays the same.*
>
> > [!quote] Textbook note
> > Textbook p. 907: the number of crests passing an observer each second must be the same on both sides of the boundary. Otherwise waves would pile up or disappear at the boundary, and nothing there can do that. So f is set by the source and carried across unchanged.

> [!note]- Why it works
> Frequency is a count per second, fixed where the light was made. Since $v = \lambda f$ holds in every medium and v falls to c/n, the wavelength must fall by the same factor. That gives slide 8's chain $\frac{n_1}{n_2} = \frac{v_2}{v_1} = \frac{\lambda_2}{\lambda_1}$.

> [!question] L2-Q3x · [Extension] Calculation
> Light has a wavelength of 450 nm in water (n = 1.33). It passes into diamond (n = 2.42). What is its wavelength in the diamond?

> [!success]- Extension answer
> $n_1\lambda_1 = n_2\lambda_2$, so $\lambda_2 = 450 \times 1.33/2.42 = 247$ nm. Both products equal the vacuum wavelength, about 599 nm.

## Leaving water at steeper and steeper angles
> [!question] L2-Q4 · Prediction (L2 slides 10 to 11)
> A ray goes from water into air. Does it always bend away from the normal? What changes as the angle of incidence gets larger and larger?

*Think first: sketch rays leaving the water at 10°, 30° and 60° before opening the hint.*

> [!tip]- Hint
> A refraction angle can never be more than 90°. Find the angle of incidence in the water that would need exactly 90° in the air. Stuck? Read [[Critical angle and TIR]] first.

> [!success]- Answer
> While a refracted ray exists, it bends away from the normal, since water has the higher index. As θ₁ grows, θ₂ grows faster: from Snell's law, $\sin\theta_2 = 1.33\sin\theta_1$. At one angle of incidence the refracted ray reaches 90° and skims along the surface. That angle is the **critical angle**:
> $$\sin\theta_c = \frac{n_2}{n_1} = \frac{1.00}{1.33} \;\Rightarrow\; \theta_c = 48.8^\circ$$
> Beyond 48.8° there is no refracted ray at all: every bit of the light is reflected back into the water. This is **total internal reflection** (TIR, L2 slides 10 to 11).
>
> ![[L2-snell-curve.png]]
> *Figure: Snell's law at a water surface, n = 1.33 (L2 slides 6 and 11). The red water-to-air curve stops at 48.8°; past it no refraction angle exists. The blue air-to-water curve continues all the way to 90°.*
>
> ![[L2-s10-tir-rays.png]]
> *Figure (L2 slide 10): rays from one source under water. Small angles refract out (I, J); at the critical angle the ray skims the surface (K); beyond it the ray is totally reflected (L).*
>
> ![[L2-s11-tir-panels.png]]
> *Figure (L2 slide 11): (a) partial refraction and reflection; (b) at the critical angle the refracted ray is at 90°; (c) total internal reflection.*

> [!note]- Why it works
> Snell's law asks for $\sin\theta_2 = (n_1/n_2)\sin\theta_1$. When $n_1 > n_2$ that product passes 1 before θ₁ reaches 90°, and no angle has a sine above 1. When $n_1 < n_2$ it stays below 1 for every θ₁, so TIR can only happen going from a higher index to a lower one.

> [!question] L2-Q4x · [Extension] Prediction
> A fish in a still pond looks up. It sees the whole world above the water squeezed into a cone. What is the half-angle of that cone, and what does the fish see when it looks outside the cone?

> [!success]- Extension answer
> 48.8°, the critical angle. By reversibility, light from anywhere above the surface, even light skimming along it, enters the water within 48.8° of the vertical (the top of the blue curve in the figure). Outside the cone the fish sees light from inside the pond, totally reflected at the surface, such as the bottom of the pond.
>
> > [!quote] Textbook note
> > Textbook p. 916 (Example 34.6, What If?): a fish looking up at 40° sees out of the water, at the critical angle it can in principle see the whole shore, and at 60° it sees a reflection of the bottom of the pond.

## Gems in air and in water
> [!question] L2-Q5 · Calculation (L2 slides 12 to 13, L2-Ex3 with new numbers)
> Light travelling inside cubic zirconia (n = 2.20) meets the surface at 30.0°. (a) Does any of it leave into the air? (b) Repeat with the gem placed in water (n = 1.33). If light leaves, at what angle?

*Think first: decide which angle you need to compare 30.0° with before opening Hint 1.*

> [!tip]- Hint 1
> Find the critical angle for each surrounding medium, $\sin\theta_c = n_2/n_1$.

> [!tip]- Hint 2
> For air, $\sin\theta_c = 1.00/2.20$. Then compare θc with 30.0°: TIR needs the angle of incidence to be larger than θc.

> [!success]- Answer
> (a) $\theta_c = \sin^{-1}(1.00/2.20) = 27.0^\circ$. Since $30.0^\circ > 27.0^\circ$, the light is **totally reflected**; none of it enters the air.
> (b) $\theta_c = \sin^{-1}(1.33/2.20) = 37.2^\circ$. Now $30.0^\circ < 37.2^\circ$, so part of the light refracts into the water and part reflects. Refraction angle: $\sin\theta_2 = \dfrac{2.20\sin 30.0^\circ}{1.33} = 0.827$, so $\theta_2 = 55.8^\circ$.
>
> Slide check: L2-Ex3 (diamond, n = 2.42) gives θc = 24.4° in air and 33.3° in water, as the slides say.

> [!note]- Why it works
> Surrounding the gem with water raises $n_2$, which raises $\sin\theta_c = n_2/n_1$. A larger critical angle means more of the rays inside the gem arrive below it and escape, so the same 30° ray switches from trapped to transmitted.

> [!question] L2-Q5x · [Extension] Explanation
> Use your two critical angles to explain why a gem sparkles less when it sits in water than when it sits in air.

> [!success]- Extension answer
> The sparkle comes from light trapped by repeated total internal reflection and then sent out through the top faces. In water the critical angle grows (here from 27.0° to 37.2°), so more rays leak out through the back faces instead of being reflected, and less light comes back to your eye.
>
> > [!quote] Textbook note
> > Textbook p. 915: a diamond's small critical angle (about 24°) traps light through many internal reflections. Cubic zirconia placed in corn syrup loses its sparkle because the index difference is small, so the critical angle is large and rays escape sooner.

## Turning light with a glass prism
> [!question] L2-Q6 · Comparison (L2 slides 14 to 16)
> A 45°-90°-45° prism of glass (n = 1.50) turns a beam through 90° because the beam meets the long face at 45° and does not get out there. Compare that with (a) the same prism made of a plastic with n = 1.38, and (b) the glass prism used under water (n = 1.33). Does the trick still work in each case?
>
> ![[L2-s14-prisms.png]]
> *Figure (L2 slide 14): (a) a beam turned through 90° at the long face, (b) through 180° by two reflections, (c) the prisms inside binoculars.*

*Think first: write down the single comparison that decides each case.*

> [!tip]- Hint
> The beam always meets the long face at 45°. Compare 45° with the critical angle in each case.

> [!success]- Answer
> TIR at the long face needs 45° to be larger than θc.
> - Glass in air: $\theta_c = \sin^{-1}(1/1.50) = 41.8^\circ$, and 45° > 41.8°, so it works (L2 slide 14).
> - (a) Plastic in air: $\theta_c = \sin^{-1}(1/1.38) = 46.4^\circ$. Now 45° < 46.4°, so part of the beam **leaks out** of the long face. It fails.
> - (b) Glass in water: $\theta_c = \sin^{-1}(1.33/1.50) = 62.5^\circ$. 45° is far below that, so it **fails**.

> [!note]- Why it works
> The prism's shape fixes the angle at 45°, so success depends only on θc. Lowering the prism's index, or raising the index around it, pushes θc above 45°. Binoculars use such prisms to fold the light path (slide 15). An **optical fiber** uses the same rule: a core of high index inside a cladding of lower index, so light hitting the cladding beyond θc stays in the core (slide 16).
>
> Optical fibers are hair-thin threads of glass or plastic, and the light zigzags along the core by repeated total internal reflection. In medicine, endoscopes use them to see inside the body. The same reflecting prisms appear in periscopes and telescopes (slides 14 to 16).
>
> ![[L2-s16-fiber.png]]
> *Figure (L2 slide 16): light guided along the core of an optical fiber by total internal reflection at the cladding.*

> [!question] L2-Q6x · [Extension] Calculation
> What is the smallest index a 45°-90°-45° prism can have and still turn light by total internal reflection in air?

> [!success]- Extension answer
> TIR at 45° needs θc ≤ 45°: $\sin\theta_c = 1/n \le \sin 45^\circ$, so $n \ge 1/\sin 45^\circ = 1.41$.

## Building the next wave front
> [!question] L2-Q7 · Prediction (L2 slides 17 to 18)
> You know where a wave front is now. Using Huygens' construction, predict where it will be a short time Δt later for (a) a plane wave and (b) a spherical wave spreading from a lamp. What sets how far it moves?

*Think first: draw the old front with a few dots on it.*

> [!tip]- Hint
> Treat every point on the old front as a tiny new source. Draw a small circle around each dot, then draw the surface that just touches all the circles. Stuck? Read [[Huygens' principle]] first.

> [!success]- Answer
> **Huygens' principle** (L2 slide 17): every point on a wave front acts as a source of spherical secondary waves, called **wavelets**, which travel forward at the wave speed of the medium. After a time Δt, the new wave front is the surface tangent to all the wavelets. (A wave front is a surface through points of the wave that have the same phase.)
> (a) Every wavelet has radius vΔt, so the tangent surface is a new plane, parallel to the old one and vΔt ahead.
> (b) The tangent surface is a larger sphere, its radius increased by vΔt.
>
> The distance is set by the wave speed in the medium: cΔt in vacuum, (c/n)Δt in a medium of index n. Plane waves come from very distant sources such as the Sun; spherical waves from nearby sources such as a lamp (slide 18).
>
> ![[L2-s18-huygens.png]]
> *Figure (L2 slide 18): Huygens' construction for (a) a plane wave and (b) a spherical wave. The new front is tangent to wavelets of radius cΔt.*

> [!note]- Why it works
> The tangent surface to a row of equal circles has the same shape as the row, shifted outward by the radius. Change the wavelet radius from place to place, by changing the medium, and the front changes direction. That is the idea behind the next two derivations.

> [!question] L2-Q7x · [Extension] Prediction
> A plane wave front arrives at a slant at a glass surface. Its left end has entered the glass while its right end is still in air. Using wavelets, which way does the front swing, and what does that do to the direction of travel?

> [!success]- Extension answer
> Wavelets in the glass grow more slowly, with radius (c/n)Δt instead of cΔt, so the part already in the glass falls behind. The front swings so that its direction of travel turns toward the normal: refraction into a slower medium.

## Deriving the reflection law from wavelets
> [!question] L2-D1 · Derivation (L2 slide 19)
> A plane wave front AB approaches a mirror, and point A has just touched it. In the time ray 2 travels from B to the mirror at C, the wavelet sent out from A grows to radius AD, and the reflected wave front runs from D to C. Use this construction to prove how the angle of reflection compares with the angle of incidence.
>
> ![[L2-s19-reflection-derivation.png]]
> *Figure (L2 slide 19): the construction. Ray 1 reaches the mirror at A; in the same time ray 2 travels from B to C while A's wavelet grows to D.*

*Think first: sketch A, B, C and D before opening the hint.*

> [!tip]- Hint
> Look for two right triangles that share a side. What do you know about the lengths AD and BC?

> [!question] Step 1
> How do the lengths AD and BC compare, and why?

> [!success]- Step 1 result
> Both are covered in the same time Δt at the same speed v, since the incident and reflected light are in the same medium. So $AD = BC = v\Delta t$.

> [!question] Step 2
> Triangle ABC has its right angle at B, and triangle ADC has its right angle at D. What do they share, and what does that say about the angle γ (at C) and the angle γ' (at A)?

> [!success]- Step 2 result
> They share the hypotenuse AC and have one equal side (AD = BC), so they are congruent. Then $\cos\gamma = \dfrac{BC}{AC} = \dfrac{AD}{AC} = \cos\gamma'$, so $\gamma = \gamma'$.

> [!question] Step 3
> γ is the angle between the incident ray and the mirror, and γ' the angle between the reflected ray and the mirror. Turn the result into a statement about θ₁ and θ₁'.

> [!success]- Step 3 result
> $\gamma = 90^\circ - \theta_1$ and $\gamma' = 90^\circ - \theta_1'$, so $\gamma = \gamma'$ gives $\theta_1' = \theta_1$.

> [!success]- Full derivation
> 1. In time Δt ray 2 travels $BC = v\Delta t$, and the wavelet from A grows to $AD = v\Delta t$. So $AD = BC$.
> 2. Right triangles ABC and ADC share the hypotenuse AC and have AD = BC, so they are congruent: $\cos\gamma = \frac{BC}{AC} = \frac{AD}{AC} = \cos\gamma'$, giving $\gamma = \gamma'$.
> 3. With $\gamma = 90^\circ - \theta_1$ and $\gamma' = 90^\circ - \theta_1'$, this becomes $\theta_1' = \theta_1$: the law of reflection.

> [!note]- Why it works
> The incident and reflected waves travel in the same medium, so their wavelets grow at the same rate. Equal distances in equal times force the two triangles to be copies of each other, and copies have equal angles.

> [!question] L2-D1x · [Extension] Explanation
> Which step of this derivation would fail if the reflected wave somehow travelled at a different speed from the incident wave? What would the angles do then?

> [!success]- Extension answer
> Step 1: AD would no longer equal BC, so the triangles would not be congruent, and γ' would differ from γ. That is exactly the situation in refraction, where the two speeds differ and the two angles are no longer equal.

## Deriving the refraction law from wavelets
> [!question] L2-D2 · Derivation (L2 slides 20 to 21)
> Ray 1 reaches the boundary at A first. During the next Δt, ray 1 travels from A to B inside medium 2 at speed $v_2$, while ray 2 travels from A' to C in medium 1 at speed $v_1$. A and C both lie on the boundary. Derive a relation between θ₁, θ₂, n₁ and n₂.
>
> ![[L2-s20-refraction-derivation.png]]
> *Figure (L2 slide 20): the construction. Ray 2 travels A′C in medium 1 while ray 1 travels AB in medium 2.*

*Think first: mark the two right triangles before opening the hint.*

> [!tip]- Hint
> Both right triangles have the segment AC, along the boundary, as their hypotenuse.

> [!question] Step 1
> Use triangle AA'C, which has its right angle at A', to write sin θ₁ in terms of AC.

> [!success]- Step 1 result
> The angle of the triangle at A equals θ₁, and the side opposite it is A'C. So $\sin\theta_1 = \dfrac{A'C}{AC} = \dfrac{v_1\Delta t}{AC}$.

> [!question] Step 2
> Use triangle ABC, which has its right angle at B, to write sin θ₂ in terms of AC.

> [!success]- Step 2 result
> The angle of the triangle at C equals θ₂, and the side opposite it is AB. So $\sin\theta_2 = \dfrac{AB}{AC} = \dfrac{v_2\Delta t}{AC}$.

> [!question] Step 3
> Divide the two results, then replace each speed using the index of refraction.

> [!success]- Step 3 result
> $\dfrac{\sin\theta_1}{\sin\theta_2} = \dfrac{v_1}{v_2}$. With $v_1 = c/n_1$ and $v_2 = c/n_2$ (slide 21 writes $v_1$ twice in this step; see Errata): $\dfrac{\sin\theta_1}{\sin\theta_2} = \dfrac{c/n_1}{c/n_2} = \dfrac{n_2}{n_1}$, so $n_1\sin\theta_1 = n_2\sin\theta_2$.

> [!success]- Full derivation
> 1. Triangle AA'C: $\sin\theta_1 = \dfrac{A'C}{AC} = \dfrac{v_1\Delta t}{AC}$
> 2. Triangle ABC: $\sin\theta_2 = \dfrac{AB}{AC} = \dfrac{v_2\Delta t}{AC}$
> 3. Divide; Δt and AC cancel: $\dfrac{\sin\theta_1}{\sin\theta_2} = \dfrac{v_1}{v_2}$
> 4. Substitute $v_1 = c/n_1$ and $v_2 = c/n_2$: $n_1\sin\theta_1 = n_2\sin\theta_2$, which is Snell's law.

> [!note]- Why it works
> The shared hypotenuse AC links the two media: the same stretch of boundary is crossed by a fast leg in medium 1 and a slow leg in medium 2. The ratio of the legs is the ratio of the speeds, and the sines of the angles must match it.

> [!question] L2-D2x · [Extension] Calculation
> The same construction works for any wave. Sound travels at 343 m/s in air and 1850 m/s in concrete. A sound wave in air meets a concrete wall at 10.0° from the normal. Which way does it bend, and at what angle does it travel in the concrete? Beyond what angle in the air can no sound enter at all?

> [!success]- Extension answer
> From step 3, $\sin\theta_2 = \dfrac{v_2}{v_1}\sin\theta_1 = \dfrac{1850}{343}\sin 10.0^\circ = 0.937$, so θ₂ = 69.5°. It bends **away** from the normal, because sound is faster in concrete. No sound can enter once $\sin\theta_2$ would pass 1, at $\sin\theta_1 = 343/1850$, which is θ₁ = 10.7°. For sound, the "slow" side is the air.
>
> > [!quote] Textbook note
> > The two speeds come from textbook problem 34.29 (p. 921), which asks for this critical angle for sound at a concrete-air boundary.

## Mixed set
No hints. Six questions across L2.

> [!question] L2-M1 · Calculation (Tutorial 1, Q4, new numbers)
> Light passes through parallel slabs with n = 1.60 (top), 1.40 and 1.20, and then into air. In the top slab the beam travels at 20.0° from the normal. (a) At what angle does it leave into the air? (b) What angle in the top slab would give total internal reflection at the surface between the n = 1.20 slab and the air?

> [!success]- Answer
> Across parallel boundaries $n\sin\theta$ stays the same, so only the first and last media matter.
> (a) $\sin\theta = 1.60\sin 20.0^\circ = 0.547$, so θ = **33.2°**.
> (b) TIR at the last surface needs $1.60\sin\theta_1 \ge 1.00$: θ₁ ≥ **38.7°**. The earlier boundaries would need 48.6° (1.40 to 1.20) and 61.0° (1.60 to 1.40), so they do not reflect first.

> [!question] L2-M2 · Calculation (Tutorial 1, Q5, new numbers)
> The critical angle at a liquid-air surface is 45.0°. (a) A ray in the liquid meets the surface at 30.0°: what is its angle in the air? (b) A ray in the air meets the surface at 30.0°: what is its angle in the liquid?

> [!success]- Answer
> n = 1/sin 45.0° = 1.414. (a) sin θ = 1.414 sin 30.0° = 0.707, θ = **45.0°**. (b) sin θ = sin 30.0°/1.414 = 0.354, θ = **20.7°**.

> [!question] L2-M3 · Explanation (L2 slide 16)
> Why is an optical fiber's cladding made of glass with a lower index than the core?

> [!success]- Answer
> Total internal reflection only happens when light meets a lower index. Light in the core that hits the cladding beyond the critical angle is totally reflected, so it zigzags along the core instead of escaping.

> [!question] L2-M4 · Comparison (L2 slides 12 to 14)
> Which has the smaller critical angle in air, diamond (n = 2.42) or glass (n = 1.50)? Which traps light more easily?

> [!success]- Answer
> Diamond: θc = 24.4°; glass: 41.8°. Diamond, with the smaller critical angle, totally reflects a much wider range of rays, so it traps light more easily.

> [!question] L2-M5 · Calculation (Assignment 1, Q1, new numbers)
> Use the geometry of Assignment 1, Q1 (a ray enters normal to one face of a 30°-60°-90° prism and meets the long face at P), but take a prism with n = 1.55 in air. (a) Is the ray totally reflected at P? (b) If so, at what angle does it leave the bottom face? (c) What surrounding index would end total reflection at P?

> [!success]- Answer
> Normal entry means no bending, so the ray meets the long face at 60°, the prism's angle at that corner.
> (a) θc = sin⁻¹(1/1.55) = 40.2°, less than 60°: yes, TIR at P.
> (b) The reflected ray meets the bottom face at 30.0°: sin θ₃ = 1.55 sin 30.0° = 0.775, so θ₃ = **50.8°**.
> (c) TIR stops when θc reaches 60°: n₂ = 1.55 sin 60° = **1.34**.

> [!question] L2-M6 · Explanation (L2 slide 8)
> A classmate says: "Light slows down in glass because its frequency drops." Correct the statement.

> [!success]- Answer
> The frequency does not change at a boundary; it is set by the source. Light slows to v = c/n because of the medium, and since v = λf with f fixed, the wavelength shrinks by the factor n.

## Practice
Everything needed is here: the slide examples and the tutorial and assignment questions are written out in full, with their figures. Answer first, then open the boxes. All tutorial and assignment questions, in sheet order, are also collected in [[Tutorials and Assignment]].

### Lecture examples

#### L2-Ex2
> [!question] L2-Ex2 · Calculation (L2 slide 9)
> A beam of light of wavelength 550 nm travels in air and strikes a slab of transparent material. The incident beam makes an angle of 40° with the normal, and the refracted beam makes an angle of 26° with the normal. Find the index of refraction of the material.

*Think first: write the equation you would start from.*

> [!tip]- Hint
> Snell's law with $n_1 = 1$ for air. Decide whether you need the wavelength at all.

> [!success]- Answer
> 1. Snell's law: $n_1\sin\theta_1 = n_2\sin\theta_2$, with $n_1 = 1$, $\theta_1 = 40^\circ$, $\theta_2 = 26^\circ$.
> 2. $n_2 = \dfrac{\sin 40^\circ}{\sin 26^\circ} = \dfrac{0.6428}{0.4384} = $ **1.47**
>
> The wavelength is not needed for n. It does tell you what happens inside the slab: $\lambda = 550/1.466 = 375$ nm and $v = c/n = 2.05\times10^8$ m/s, with the frequency unchanged.

#### L2-Ex3
> [!question] L2-Ex3 · Calculation (L2 slides 12 to 13)
> A beam of light travelling in diamond ($n_1 = 2.42$) meets a diamond-air surface at an angle of incidence of 28°.
> (a) Will part of the beam enter the air ($n_2 = 1$), or will the beam be totally reflected at the surface?
> (b) Repeat part (a) with the diamond surrounded by water ($n_2 = 1.33$) instead of air.

*Think first: decide which angle you need to compare 28° with.*

> [!tip]- Hint
> Find the critical angle for each surrounding medium, $\sin\theta_c = n_2/n_1$, and compare it with 28°.

> [!success]- Answer
> (a) $\theta_c = \sin^{-1}\dfrac{1}{2.42} = 24.4^\circ$. Since 28° > 24.4°, there is no refraction: the light is **totally reflected** back into the diamond.
> (b) $\theta_c = \sin^{-1}\dfrac{1.33}{2.42} = 33.3^\circ$. Since 28° < 33.3°, the beam is **partly refracted** into the water and partly reflected. The refracted ray travels at $\sin^{-1}\dfrac{2.42\sin 28^\circ}{1.33} = 58.7^\circ$ from the normal.

### Tutorial and assignment questions

#### Tutorial 1, Q2
> [!question] T1-Q2 · Calculation (Tutorial 1, Q2)
> A beam of light has a wavelength of 650 nm in vacuum.
> (a) What is the speed of this light in a liquid whose index of refraction at this wavelength is 1.47?
> (b) What is the wavelength of these waves in the liquid?

*Think first: decide which quantities change in the liquid.*

> [!tip]- Hint
> Only the speed and the wavelength change, and both are divided by n. Stuck? Revisit [[L2 Refraction#Speed, wavelength and frequency in a medium|L2, speed, wavelength and frequency]].

> [!success]- Answer
> (a) $v = \dfrac{c}{n} = \dfrac{3.00\times10^8}{1.47} = $ **2.04 × 10⁸ m/s**
> (b) $\lambda_n = \dfrac{\lambda_0}{n} = \dfrac{650\ \text{nm}}{1.47} = $ **442 nm**
>
> Check: the frequency is the same inside and outside. Outside, $f = c/\lambda_0 = 4.62\times10^{14}$ Hz; inside, $v/\lambda_n = (2.04\times10^8)/(442\times10^{-9}) = 4.62\times10^{14}$ Hz.

#### Tutorial 1, Q3
> [!question] T1-Q3 · Derivation (Tutorial 1, Q3)
> A beam of light both reflects and refracts at the surface between air and glass, as shown in the figure. If the refractive index of the glass is $n_g$, find the angle of incidence $\theta_1$ in the air that would result in the reflected ray and the refracted ray being perpendicular to each other.
>
> ![[L2-T1Q3-perpendicular.png]]
> *Figure: Tutorial 1, Q3.*

*Think first: mark every angle you can at the point where the rays meet the surface.*

> [!tip]- Hint
> The reflected ray leaves at θ₁ from the normal. Use the 90° between the two rays to write θ₂ in terms of θ₁, then apply Snell's law. Stuck? Revisit [[L3a Polarization#Deriving Brewster's law|L3a, Brewster's law]].

> [!success]- Answer
> 1. Law of reflection: the reflected ray is at θ₁ from the normal.
> 2. Perpendicular rays: $\theta_1 + 90^\circ + \theta_2 = 180^\circ$, so $\theta_2 = 90^\circ - \theta_1$.
> 3. Snell's law with $n_{air} = 1$: $\sin\theta_1 = n_g\sin(90^\circ - \theta_1) = n_g\cos\theta_1$.
> 4. Divide by $\cos\theta_1$: $\tan\theta_1 = n_g$.
>
> **Answer: $\theta_1 = \tan^{-1}(n_g)$.** This is Brewster's polarizing angle (L3a slide 18).

#### Tutorial 1, Q4
> [!question] T1-Q4 · Calculation (Tutorial 1, Q4)
> The figure below shows the path of a light beam through several slabs with different indices of refraction.
> (a) If $\theta_1 = 30.0^\circ$, what is the angle $\theta_2$ of the emerging beam? (The sheet prints "θ₁" here; the figure and the intended question use θ₂.)
> (b) What must the incident angle $\theta_1$ be to have total internal reflection at the surface between the medium with n = 1.20 and the medium with n = 1.00?
>
> ![[L2-T1Q4-slabs.png]]
> *Figure: Tutorial 1, Q4.*

*Think first: decide whether the middle slabs change the final answer.*

> [!tip]- Hint
> Across parallel boundaries $n\sin\theta$ never changes, so the middle slabs drop out. For (b), total internal reflection at the last surface starts when the refraction angle in the air reaches 90°. Stuck? Revisit [[L2 Refraction#Leaving water at steeper and steeper angles|L2, total internal reflection]].

> [!success]- Answer
> (a) Snell's law at each boundary gives $1.60\sin\theta_1 = 1.40\sin\theta_a = 1.20\sin\theta_b = 1.00\sin\theta_2$, with $1.60\sin 30.0^\circ = 0.800$:
> - in the 1.40 slab: $\sin\theta_a = 0.800/1.40 = 0.571$, $\theta_a = 34.8^\circ$
> - in the 1.20 slab: $\sin\theta_b = 0.800/1.20 = 0.667$, $\theta_b = 41.8^\circ$
> - in air: $\sin\theta_2 = 0.800$, so **θ₂ = 53.1°**
>
> (b) TIR at the 1.20 to 1.00 surface needs $1.20\sin\theta_b \ge 1.00$, and $1.20\sin\theta_b = 1.60\sin\theta_1$. So $\sin\theta_1 \ge 1/1.60 = 0.625$: **θ₁ ≥ 38.7°**.
> Check: TIR at the earlier boundaries would need $\theta_1 \ge 61.0^\circ$ (1.60 to 1.40) or $\theta_1 \ge 48.6^\circ$ (1.40 to 1.20), so the last surface is the first to reflect totally.

#### Tutorial 1, Q5
> [!question] T1-Q5 · Calculation (Tutorial 1, Q5)
> The critical angle for total internal reflection at a liquid-air interface is 42.5°.
> (a) If a ray of light traveling in the liquid has an angle of incidence at the interface of 35.0°, what angle does the refracted ray in the air make with the normal?
> (b) If a ray of light traveling in air has an angle of incidence at the interface of 35.0°, what angle does the refracted ray in the liquid make with the normal?

*Think first: decide what the critical angle tells you about the liquid.*

> [!tip]- Hint
> Turn the critical angle into the liquid's index first: $\sin\theta_c = 1/n$. Stuck? Revisit [[L2 Refraction#Gems in air and in water|L2, critical angle calculations]].

> [!success]- Answer
> Index: $n = \dfrac{1}{\sin 42.5^\circ} = 1.48$.
> (a) Liquid to air. 35.0° is below the critical angle, so the ray gets out: $\sin\theta = 1.48\sin 35.0^\circ = 0.849$, so **θ = 58.1°**.
> (b) Air to liquid: $\sin\theta = \dfrac{\sin 35.0^\circ}{1.48} = 0.388$, so **θ = 22.8°**. Going from a low to a high index there is no critical angle to worry about.

#### Tutorial 1, Q6
> [!question] T1-Q6 · Calculation (Tutorial 1, Q6)
> The light beam in the figure strikes surface 2 at the critical angle. Determine the angle of incidence $\theta_1$.
>
> ![[L2-T1Q6-prism.png]]
> *Figure: Tutorial 1, Q6.*

*Think first: list what the 42.0° and the 60.0° each tell you.*

> [!tip]- Hint
> The critical angle gives n. Inside the prism, the two angles measured from the normals add up to the angle between the faces: $r_1 + r_2 = A$. Stuck? Revisit [[L3b Dispersion and Prisms#Deriving the prism relations|L3b, prism relations]].

> [!success]- Answer
> 1. Critical angle: $\sin 42.0^\circ = 1/n$, so $n = 1.494$.
> 2. Geometry: surfaces 1 and 2 meet at 60.0°, and the beam meets surface 2 at $r_2 = 42.0^\circ$, so $r_1 = 60.0^\circ - 42.0^\circ = 18.0^\circ$.
> 3. Snell's law at surface 1: $\sin\theta_1 = 1.494\sin 18.0^\circ = 0.462$, so **θ₁ = 27.5°**.

#### Assignment 1, Q1
> [!question] A1-Q1 · Calculation (Assignment 1, Q1)
> As shown in the figure, a light ray is incident normal to one face of a 30°-60°-90° prism of flint glass (n = 1.66) that is immersed in water.
> (a) Determine the exit angle $\theta_3$ of the ray.
> (b) A substance is dissolved in the water to increase the index of refraction $n_2$. At what value of $n_2$ does total internal reflection cease at point P?
>
> ![[L2-A1Q1-prism-water.png]]
> *Figure: Assignment 1, Q1. Water has $n_2 = 1.33$, the value the slides use.*

*Think first: trace the ray to P and decide whether it can get out there.*

> [!tip]- Hint
> Entering along the normal, the ray doesn't bend, so it meets the long face at the 60° corner angle. Compare that with the glass-to-water critical angle, then follow the reflected ray to the bottom face. Stuck? Revisit [[L2 Refraction#Turning light with a glass prism|L2, prisms and TIR]].

> [!success]- Answer
> (a)
> 1. The ray enters along the normal and does not bend, so it meets the long face at P at θ₁ = 60.0°.
> 2. Critical angle, glass to water: $\sin\theta_c = \dfrac{1.33}{1.66} = 0.801$, so $\theta_c = 53.2^\circ$. Since 60.0° > 53.2°, the ray is totally reflected at P.
> 3. The ray arrives parallel to the bottom face and the long face is tilted 30° to it, so the reflected ray leaves at 30° + 30° = 60° below the horizontal. It meets the bottom face at θ₂ = 30.0° from the normal.
> 4. Snell's law at the bottom face: $1.66\sin 30.0^\circ = 1.33\sin\theta_3$, so $\sin\theta_3 = 0.624$ and **θ₃ = 38.6°**.
>
> (b) Total reflection at P stops once the critical angle reaches 60.0°: $\sin 60.0^\circ = n_2/1.66$, so **n₂ = 1.66 sin 60.0° = 1.44**.

## Errata
> [!bug]- Slide 21, step (4)
> The slide writes $v_1 = c/n_1$ and then $v_1 = c/n_2$. The second one is $v_2 = c/n_2$. With that fix, $\frac{\sin\theta_1}{\sin\theta_2} = \frac{n_2}{n_1}$ follows (textbook p. 912 has the same step written correctly).

> [!bug]- Slide 10, figure reference
> The text refers to "Figure c", but the panels (a) to (c) are on slide 11.

> [!bug]- Slide 4, air and vacuum
> Using n = 1 for air is the course convention and is fine for every calculation here. Strictly, air has n = 1.000293 (textbook p. 907), so the speed of light in air is very slightly less than c.

> [!bug]- Tutorial 1, Q4(a)
> It asks for "the angle θ₁ of the emerging beam". The figure labels the emerging angle θ₂, and textbook problem 34.45, the same question, asks for θ₂.

## Self-check
Timed run: about 6 minutes, no notes.

> [!question] L2-S1 · Calculation (L2 slide 9)
> Light in air meets a block at 45.0° and refracts to 28.0°. Find n.

> [!success]- Answer
> n = sin 45.0°/sin 28.0° = 0.7071/0.4695 = **1.51**.

> [!question] L2-S2 · Calculation (L2 slide 11)
> Find the critical angle for crown glass (n = 1.52) under water (n = 1.33).

> [!success]- Answer
> θc = sin⁻¹(1.33/1.52) = sin⁻¹(0.875) = **61.0°**.

> [!question] L2-S3 · Explanation (L2 slide 11)
> State the two conditions needed for total internal reflection.

> [!success]- Answer
> The light must travel from a higher-index medium toward a lower-index one, and its angle of incidence must be larger than the critical angle, $\sin\theta_c = n_2/n_1$.

## Review
Spaced questions from earlier lectures.

> [!question] L2-R1 · Calculation (from L1, slide 14)
> Two mirrors meet at 120°. A ray hits M1 at 50° from the normal. What angle does it make with M2's normal?

> [!success]- Answer
> 90° − 50° = 40° from M1; 40° + 120° + x = 180° gives x = 20°; so **70°** from M2's normal.

> [!question] L2-R2 · Calculation (from L1, slide 7)
> Find the energy of a photon of wavelength 450 nm.

> [!success]- Answer
> f = c/λ = 6.67 × 10¹⁴ Hz; E = hf = **4.42 × 10⁻¹⁹ J**.

> [!question] L2-R3 · Prediction (from L1, slide 9)
> Light with λ = 600 nm passes through a slit 2.0 mm wide. Can it be treated with the ray approximation?

> [!success]- Answer
> d/λ = (2.0 × 10⁻³)/(6.0 × 10⁻⁷) ≈ 3300, so λ ≪ d: yes, straight rays work.

> [!question] L2-R4 · Explanation (from L1, slides 12 to 13)
> Why can everyone in a cinema see the picture on the screen, whatever their seat?

> [!success]- Answer
> The screen is rough, so it reflects diffusely: each patch sends light in many directions, and some reaches every seat. A mirror-smooth screen would reflect specularly, toward one direction only.
