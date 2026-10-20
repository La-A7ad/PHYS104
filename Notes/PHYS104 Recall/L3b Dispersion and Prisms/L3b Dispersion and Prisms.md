---
lecture: "L3b Dispersion and Prisms"
slides: "Lecture 4 PDF (its title slide says Lecture 3), slides 1 to 17"
textbook: "10th ed. section 34.4 Example 34.5 (p. 910) and section 34.6 (pp. 912 to 914); the course numbers this chapter 35"
tags: [PHYS104, recall]
---
# L3b Dispersion and Prisms

[[PHYS104 Recall/Index|Course map]] · [[Recall Log]] · [[Glossary]] · Previous: [[L3a Polarization]]

Every section starts with a question: answer it before you open anything. How it works: [[PHYS104 Recall/Index#How to use it|see the Index]].

## Goals
- [ ] Tell monochromatic from polychromatic light and give an example of each.
- [ ] Explain why a prism separates white light, and predict which colour is bent most.
- [ ] Derive the prism relations for the inside angles and the total deviation.
- [ ] Trace a ray through a prism at a given angle of incidence, including the check at the second face.
- [ ] Find a prism's index from its minimum deviation.
- [ ] Calculate angular dispersion, dispersive power and the Abbe number, and classify a glass.
- [ ] Explain the rainbow's colour order using angles measured from the antisolar direction.

## Warm-up
Two questions from [[L3a Polarization|L3a]].

> [!question] L3b-W1 · Calculation (L3a slide 18)
> Find the polarizing angle for glass with n = 1.52 in air.

> [!success]- Answer
> tan⁻¹(1.52) = 56.7°.

> [!question] L3b-W2 · Calculation (L3a slide 11)
> Polarized light meets an analyzer at 50° to its polarization. What fraction is transmitted?

> [!success]- Answer
> cos² 50° = 0.413.

## One colour or many
> [!question] L3b-Q1 · Comparison (L3b slide 2)
> Sort these sources into monochromatic and polychromatic: a laser pointer, sunlight, a sodium vapour street lamp, an incandescent bulb. Which of them would a prism spread into a band of colours?

*Think first: sort all four before opening the hint.*

> [!tip]- Hint
> Monochromatic means a single wavelength. Ask which sources look like one pure colour.

> [!success]- Answer
> - **Monochromatic** light has one specific wavelength and one pure colour: the laser and the sodium vapour lamp.
> - **Polychromatic** light mixes many wavelengths and often looks white: sunlight and the incandescent bulb.
>
> A prism spreads only the polychromatic sources into a band of colours. A monochromatic beam is bent, but stays one colour.

> [!note]- Why it works
> A prism separates colours because each wavelength bends by a different amount, which the next section explores. A source with a single wavelength has nothing to separate.

> [!question] L3b-Q1x · [Extension] Prediction
> You pass white light through a prism, use a slit to keep only the green part, and send that green light through a second prism. Does it split into more colours?

> [!success]- Extension answer
> No. The second prism bends the green light again but cannot create new colours: the colours were already in the white light, and the first prism only sorted them.
>
> > [!quote] Textbook note
> > Textbook p. 913: Newton showed that each colour has its own angle of deviation, and that the colours can be recombined to form the original white light.

## Colour inside glass
> [!question] L3b-Q2 · Prediction (L3b slides 3 to 5)
> In ordinary glass, is the index of refraction for violet light larger or smaller than for red light? Use that to predict which colour travels faster inside the glass, and which one a prism bends more.

*Think first: commit to an answer for each of the three parts.*

> [!tip]- Hint
> Look at how n changes with wavelength on the slide 3 graph, then use $v = c/n$ and Snell's law. Stuck? Read [[Dispersion]] first.
>
> ![[L3b-s03-n-vs-lambda.png]]
> *Figure (L3b slide 3): index of refraction against vacuum wavelength for six transparent materials.*

> [!success]- Answer
> Over the visible range, n **decreases** as the wavelength increases (slide 4): $n_V > n_B > n_G > n_Y > n_R$. This dependence of n on wavelength is **dispersion**, $n = n(\lambda)$ (slide 3).
> - Speed: $v = c/n$, and violet has $\lambda_V < \lambda_R$ and so $n_V > n_R$. Violet is slower: $v_V < v_R$.
> - Bending: at each face violet refracts more, with a smaller refraction angle inside the glass, so the prism deviates violet more than red: $\delta_V > \delta_R$ (slide 5).
>
> White light therefore fans out into a spectrum, red deviated least and violet most.
>
> ![[L3b-s05-prism-dispersion.png]]
> *Figure (L3b slide 5): white light spread by a prism. Violet is deviated most and red least; θ = δ_V − δ_R measures the spread.*

> [!note]- Why it works
> In vacuum all colours travel at c; inside matter the speed depends on the wavelength, so n does too (slide 3). Snell's law turns a slightly larger n into a slightly larger bend, and the colours separate.

> [!question] L3b-Q2x · [Extension] Comparison
> On the slide 3 graph, fused quartz has a much flatter n(λ) curve than silicate flint glass. Which would make a better single-element camera lens, if you want all the colours to focus together?
>
> ![[L3b-s03-n-vs-lambda.png]]
> *Figure (L3b slide 3).*

> [!success]- Extension answer
> Fused quartz. A flatter curve means the colours' indices differ less, so they bend almost equally and focus closer together.
>
> > [!quote] Textbook note
> > Textbook p. 914 (Quick Quiz 34.4) asks the same question for crown glass, acrylic and fused quartz, using a graph of n against wavelength.

## Deriving the prism relations
> [!question] L3b-D1 · Derivation (L3b slides 6 to 7)
> A ray enters face AB of a **prism** with apex angle A at angle of incidence $i_1$, refracts to $r_1$, crosses the prism, meets face AC at $r_2$, and leaves at $i_2$. The normals drawn at the two faces meet at a point O inside the prism. Find how $r_1 + r_2$ relates to A, and find the total deviation δ in terms of $i_1$, $i_2$ and A.
>
> ![[L3b-s07-prism-geometry-masked.png]]
> *Figure (L3b slides 6 to 7), with the slide's two results hidden: the ray, the normals meeting at O, and the angles i₁, r₁, r₂, i₂ and δ.*

*Think first: sketch the prism, both normals and the point O.*

> [!tip]- Hint
> Look at the four-sided figure made by the apex, the two points where the ray crosses the faces, and O. Then look at the triangle formed by the ray inside the prism and the two normals. Stuck? Read [[Prism deviation]] first.

> [!question] Step 1
> In that four-sided figure, what are the angles at the two faces, and what does that make the angle at O?

> [!success]- Step 1 result
> The normals meet the faces at 90°, so two of the angles are 90°. The four angles add to 360°: $A + 90^\circ + 90^\circ + \angle O = 360^\circ$, so $\angle O = 180^\circ - A$.

> [!question] Step 2
> Use the triangle formed by the ray inside the prism and the two normals to relate $r_1$, $r_2$ and A.

> [!success]- Step 2 result
> That triangle has angles $r_1$, $r_2$ and $180^\circ - A$, so $r_1 + r_2 + (180^\circ - A) = 180^\circ$, which gives $r_1 + r_2 = A$.

> [!question] Step 3
> How much does each face turn the ray, and what is the total?

> [!success]- Step 3 result
> Face 1 turns it by $i_1 - r_1$ and face 2 by $i_2 - r_2$, in the same sense. Total: $\delta = (i_1 - r_1) + (i_2 - r_2) = i_1 + i_2 - (r_1 + r_2) = i_1 + i_2 - A$.

> [!success]- Full derivation
> 1. Four-sided figure (apex, entry point, exit point, O): $A + 90^\circ + 90^\circ + \angle O = 360^\circ$, so $\angle O = 180^\circ - A$.
> 2. Triangle (ray inside, two normals): $r_1 + r_2 + (180^\circ - A) = 180^\circ$, so $r_1 + r_2 = A$.
> 3. **Angle of deviation**: $\delta = (i_1 - r_1) + (i_2 - r_2) = i_1 + i_2 - A$.
>
> Together with Snell's law at each face for a prism in air, $\sin i_1 = n\sin r_1$ and $n\sin r_2 = \sin i_2$, these relations trace any ray through any prism.
>
> ![[L3b-s07-prism-geometry.png]]
> *Figure (L3b slide 7): the full slide figure, with both results written in.*

> [!note]- Why it works
> The **apex angle** A has to be shared between the two inside angles, because the two normals are tilted relative to each other by the same angle as the two faces. Both faces bend the ray the same way, toward the prism's base in the slide figures, so the two deviations add instead of cancelling.

> [!question] L3b-D1x · [Extension] Calculation
> A ray enters a 30.0° prism (n = 1.50) along the normal to the first face, so $i_1 = 0$. Find $r_1$, $r_2$, $i_2$ and δ.

> [!success]- Extension answer
> $r_1 = 0$, so $r_2 = A = 30.0^\circ$. Then $\sin i_2 = 1.50\sin 30.0^\circ = 0.750$, so $i_2 = 48.6^\circ$, and $\delta = 0 + 48.6^\circ - 30.0^\circ = 18.6^\circ$.

## Tracing a ray through a prism
> [!question] L3b-Q3 · Calculation (L3b slide 7; same method as Assignment 1, Q4)
> A ray strikes an equilateral prism (A = 60.0°, n = 1.50) at $i_1 = 45.0^\circ$. Find $r_1$, $r_2$, $i_2$ and the deviation δ. Does the ray leave through the second face?

*Think first: list the steps you will take before opening Hint 1.*

> [!tip]- Hint 1
> You need Snell's law at each face plus the two relations $r_1 + r_2 = A$ and $\delta = i_1 + i_2 - A$.

> [!tip]- Hint 2
> Start at face 1: $\sin r_1 = \sin i_1/n$. Before using Snell's law at face 2, compare $r_2$ with the critical angle.

> [!success]- Answer
> 1. Face 1: $\sin r_1 = \sin 45.0^\circ/1.50 = 0.471$, so $r_1 = 28.1^\circ$.
> 2. Geometry: $r_2 = 60.0^\circ - 28.1^\circ = 31.9^\circ$.
> 3. Check: $\theta_c = \sin^{-1}(1/1.50) = 41.8^\circ$, larger than 31.9°, so the ray **does** leave.
> 4. Face 2: $\sin i_2 = 1.50\sin 31.9^\circ = 0.792$, so $i_2 = 52.4^\circ$.
> 5. Deviation: $\delta = 45.0^\circ + 52.4^\circ - 60.0^\circ = 37.4^\circ$.

> [!note]- Why it works
> Each step uses one rule, so mistakes stay visible: Snell's law at a face, geometry inside. The critical-angle check matters because $r_2$ is fixed by A and $r_1$, not by you; if it exceeds θc, there is no $i_2$ to find.

> [!question] L3b-Q3x · [Extension] Prediction
> Send a ray into the same prism at 52.4°, through the face the first ray left by. At what angle do you predict it leaves, and why?

> [!success]- Extension answer
> At 45.0°, with the same deviation of 37.4°. Light paths are reversible (L1 slide 11), so the ray retraces the first path backward.

## Getting the ray out of the prism
> [!question] L3b-Q4 · Prediction (L3b slide 8)
> Glass with n = 1.50 has a critical angle of 41.8°. For prisms of this glass with apex angles of 40°, 70° and 90°, predict: does every ray get out of the second face, only some, or none?

*Think first: commit to an answer for each prism.*

> [!tip]- Hint
> Inside the prism $r_1 + r_2 = A$, and neither inside angle can be larger than θc: $r_1$ can't, because $\sin r_1 = \sin i_1/n \le 1/n$, and $r_2$ mustn't, if the ray is to escape.

> [!success]- Answer
> - **A = 40°**, at most θc: $r_2 = A - r_1 \le 40^\circ < 41.8^\circ$, so every ray gets out.
> - **A = 70°**, between θc and 2θc = 83.6°: only rays with a large enough $i_1$ get out. The limit is $r_2 = \theta_c$, so $r_1 = 70^\circ - 41.8^\circ = 28.2^\circ$, and $\sin i_{1,min} = 1.50\sin 28.2^\circ = 0.709$, giving $i_{1,min} = 45.1^\circ$. Below that, the ray is totally reflected at the second face.
> - **A = 90°**, more than 2θc: 90° cannot be split into two angles that are each at most 41.8°, so **no** ray gets out.

> [!note]- Why it works
> The apex angle has to be shared between $r_1$ and $r_2$, and each share is capped at θc. A small A always fits; an A above 2θc never fits; in between, the ray needs a large enough $r_1$, which means a large enough $i_1$.

> [!question] L3b-Q4x · [Extension] Calculation
> Can the 90° prism of n = 1.50 pass light if it is submerged in water (n = 1.33)? If so, what is the smallest angle of incidence, measured in the water, that works?

> [!success]- Extension answer
> In water $\theta_c = \sin^{-1}(1.33/1.50) = 62.5^\circ$, so $2\theta_c = 124.9^\circ$, more than 90°: yes. The limit is $r_2 = 62.5^\circ$, so $r_1 = 27.5^\circ$. At the first face, $1.33\sin i_1 = 1.50\sin r_1$: $\sin i_1 = \frac{1.50}{1.33}\sin 27.5^\circ = 0.521$, so $i_1 = 31.4^\circ$.

## How deviation changes with incidence
> [!question] L3b-Q5 · Prediction (L3b slide 9)
> For a 60° prism with n = 1.52, imagine raising $i_1$ from the smallest value that lets light out (about 29°) up to 90°. Sketch how the deviation δ changes. Where is its lowest point, and is the curve symmetric about it?

*Think first: sketch the curve before opening the hint.*

> [!tip]- Hint
> Use reversibility: a ray entering at $i_1$ and leaving at $i_2$ has the same δ as one entering at $i_2$ and leaving at $i_1$. Where could a single lowest point sit? Stuck? Read [[Minimum deviation]] first.

> [!success]- Answer
> δ starts high, at 59.4° when $i_1 = 29.4^\circ$ (the ray then grazes the second face), falls to a minimum, then rises again to 59.4° at grazing incidence, $i_1 = 90^\circ$. The **minimum deviation**, $\delta_{min} = 38.9^\circ$, occurs at $i_1 = i_2 = 49.5^\circ$, where the ray passes through the prism symmetrically.
> The curve is **not** symmetric: it falls steeply on the left and rises gently on the right. Fifteen degrees below the minimum δ = 44.3°; fifteen degrees above it δ = 41.9°. (Slide 9 claims symmetry; see Errata.)
>
> ![[L3b-deviation-curve.png]]
> *Figure: δ against $i_1$ for A = 60°, n = 1.52, the values used on L3b slide 9.*

> [!note]- Why it works
> Reversibility pairs up incidence angles: every δ above the minimum is produced by two angles, $i_1$ and the matching $i_2$. The single lowest δ cannot belong to a pair of different angles, so there $i_1 = i_2$. Pairing angles is not the same as the graph being a mirror image, which is why the curve is lopsided.

> [!question] L3b-Q5x · [Extension] Comparison
> Using the same glass (n = 1.52), is the minimum deviation larger for a 60° prism or a 45° prism? Compute the 45° value.

> [!success]- Extension answer
> $\sin\frac{45^\circ + \delta}{2} = 1.52\sin 22.5^\circ = 0.582$, so $\frac{45^\circ + \delta}{2} = 35.6^\circ$ and $\delta_{min} = 26.1^\circ$, smaller than 38.9°. A larger apex angle gives a larger minimum deviation (slide 11).

## Deriving the minimum deviation formula
> [!question] L3b-D2 · Derivation (L3b slide 10)
> Use what you found in L3b-Q5 about the ray's path at minimum deviation to find n in terms of A and $\delta_{min}$. Then use your formula: a 60.0° prism gives $\delta_{min} = 42.0^\circ$; find n.

*Think first: write down the two prism relations from the earlier derivation.*

> [!tip]- Hint
> Feed the symmetry of the path into both prism relations, then use Snell's law at one face.

> [!question] Step 1
> At minimum deviation, how are $r_1$ and $r_2$ related, and what does that make each of them?

> [!success]- Step 1 result
> The path is symmetric, so $r_1 = r_2 = r$ and $i_1 = i_2 = i$. Then $r_1 + r_2 = A$ gives $2r = A$, so $r = A/2$.

> [!question] Step 2
> Find i from $\delta = i_1 + i_2 - A$.

> [!success]- Step 2 result
> $\delta_{min} = 2i - A$, so $i = \dfrac{A + \delta_{min}}{2}$.

> [!question] Step 3
> Apply Snell's law at the first face.

> [!success]- Step 3 result
> $\sin i = n\sin r$, so $n = \dfrac{\sin\frac{A + \delta_{min}}{2}}{\sin\frac{A}{2}}$.

> [!success]- Full derivation
> 1. Symmetry in $r_1 + r_2 = A$: $r = A/2$.
> 2. Symmetry in $\delta = i_1 + i_2 - A$: $i = (A + \delta_{min})/2$.
> 3. Snell's law at face 1, $n = \sin i/\sin r$:
> $$n = \frac{\sin\left(\frac{A + \delta_{min}}{2}\right)}{\sin\left(\frac{A}{2}\right)}$$
> For A = 60.0° and $\delta_{min} = 42.0^\circ$: $n = \dfrac{\sin 51.0^\circ}{\sin 30.0^\circ} = \dfrac{0.777}{0.500} = 1.55$.
>
> Slide check: L3b-Ex1 (60°, 37°) gives $\sin 48.5^\circ/\sin 30^\circ = 0.749/0.500 = 1.50$, as the slide says.

> [!note]- Why it works
> Symmetry removes two unknowns at once and leaves one Snell's-law equation that links n to two things you can measure, A and $\delta_{min}$. Inside an isosceles prism the symmetric ray runs parallel to the base. Because δ hardly changes near its minimum, small errors in setting the incidence barely affect $\delta_{min}$, which is why spectrometers measure n this way (slide 10).

> [!question] L3b-D2x · [Extension] Calculation
> A hollow 60° prism made of thin glass is filled with water (n = 1.33). Predict its minimum deviation.

> [!success]- Extension answer
> $\sin\frac{60^\circ + \delta}{2} = 1.33\sin 30^\circ = 0.665$, so $\frac{60^\circ + \delta}{2} = 41.7^\circ$ and $\delta_{min} = 23.4^\circ$.
>
> > [!quote] Textbook note
> > Textbook p. 910 (Example 34.5): a hollow prism lets the same method measure the index of a liquid.

## Thin prisms and colour spread
> [!question] L3b-Q6 · Calculation (L3b slides 11 to 13)
> A thin prism with an apex angle of 5.0° is made of glass with $n_R = 1.514$ and $n_V = 1.532$. Find the deviation of red light, the deviation of violet light, and the angle between them.

*Think first: decide which shortcut a thin prism allows before opening Hint 1.*

> [!tip]- Hint 1
> For a **thin prism** ($A \lesssim 10^\circ$) the deviation does not depend on the angle of incidence: $\delta = (n - 1)A$. Stuck? Read [[Dispersive power and Abbe number]] first.

> [!tip]- Hint 2
> Compute $(n - 1)A$ for each colour, then subtract.

> [!success]- Answer
> - Red: $\delta_R = (1.514 - 1)(5.0^\circ) = 2.57^\circ$
> - Violet: $\delta_V = (1.532 - 1)(5.0^\circ) = 2.66^\circ$
> - **Angular dispersion**: $\theta = \delta_V - \delta_R = (n_V - n_R)A = (0.018)(5.0^\circ) = 0.090^\circ$
>
> ![[L3b-s12-angular-dispersion.png]]
> *Figure (L3b slides 12 to 13): red and violet rays leaving a prism with deviations δ_R and δ_V; the angle between them is the angular dispersion.*

> [!note]- Why it works
> For small angles the sines in Snell's law can be replaced by the angles themselves: $i_1 = n r_1$ and $i_2 = n r_2$. Then $\delta = i_1 + i_2 - A = n(r_1 + r_2) - A = (n - 1)A$ (slide 11). The colour spread is the difference between two such deviations.

> [!question] L3b-Q6x · [Extension] Prediction
> Double the apex angle to 10.0°. What happens to the angular dispersion? Does the glass's dispersive power change?

> [!success]- Extension answer
> The angular dispersion doubles, to 0.18°, since $\theta = (n_V - n_R)A$. The dispersive power does not change: $\omega = (n_V - n_R)/(n_Y - 1)$ has no A in it, so it describes the glass, not the prism.

## Rating glass by dispersion
> [!question] L3b-Q7 · Calculation (L3b slides 14 and 16, L3b-Ex2 with new numbers)
> A 60.0° prism of a flint glass with $n_R = 1.6150$, $n_Y = 1.6200$ and $n_V = 1.6330$ is used at minimum deviation. Find $\delta_R$, $\delta_V$, the angle of dispersion θ, the dispersive power ω and the Abbe number V. Is this a low- or a high-dispersion glass?

*Think first: write the formula for each of the five quantities.*

> [!tip]- Hint 1
> At minimum deviation, $\sin\frac{A + \delta}{2} = n\sin\frac{A}{2}$ for each colour. Then $\omega = \frac{n_V - n_R}{n_Y - 1}$ and $V = 1/\omega$.

> [!tip]- Hint 2
> With A = 60.0°, $\sin(A/2) = 0.500$, so $\frac{60^\circ + \delta}{2} = \sin^{-1}(n/2)$.

> [!success]- Answer
> - Red: $\sin^{-1}(1.6150/2) = 53.85^\circ$, so $\delta_R = 2(53.85^\circ) - 60^\circ = 47.70^\circ$.
> - Violet: $\sin^{-1}(1.6330/2) = 54.74^\circ$, so $\delta_V = 49.47^\circ$.
> - $\theta = \delta_V - \delta_R = 1.77^\circ$
> - **Dispersive power**: $\omega = \dfrac{1.6330 - 1.6150}{1.6200 - 1} = \dfrac{0.0180}{0.620} = 0.0290$
> - **Abbe number**: $V = 1/\omega = 34.4$
>
> V is below 50, so this is a **high-dispersion**, flint-type glass.
> Slide check: L3b-Ex2 (BK7) recomputes to $\delta_R = 38.43^\circ$, $\delta_V = 39.14^\circ$, θ = 0.71°, ω = 0.0157 and V = 63.8; the slide's own figures are slightly off (see Errata).

> [!note]- Why it works
> θ grows with the prism angle, so on its own it cannot rate a glass. Dividing the colour spread by the mean (yellow) deviation cancels A for a thin prism and leaves ω, a property of the material. A high Abbe number V = 1/ω means little colour spread for a given amount of bending: **crown glass** (V > 50) has low dispersion, **flint glass** (V < 50) high (slide 14).

> [!question] L3b-Q7x · [Extension] Comparison
> Two glasses have V = 64 (crown) and V = 34 (flint). Thin prisms of each are made to give the same deviation of yellow light. Which spreads the colours more, and by roughly what factor?

> [!success]- Extension answer
> θ = ωδ_Y, so with the same δ_Y the spread is proportional to ω = 1/V. The flint prism spreads the colours about 64/34 = **1.9 times** as much.

## The rainbow
> [!question] L3b-Q8 · Explanation (L3b slide 17)
> You stand with the Sun behind you, facing a rain shower. Light leaving a raindrop makes 40° with the incoming sunlight for violet and 42° for red. From a drop high in the sky, which colour reaches your eye? Which colour forms the outer edge of the bow? Which colour does a drop turn through the larger angle?

*Think first: answer all three parts before opening the hint.*

> [!tip]- Hint
> Measure every angle from the **antisolar direction**: the direction pointing straight away from the Sun, through your head toward the shadow of your head. A drop seen higher in the sky lies at a larger angle from that line. Stuck? Read [[Rainbow]] first.

> [!success]- Answer
> The light reaching your eye from a drop travels along your line of sight to that drop. Sunlight arrives along the antisolar direction, so the angle between the incoming sunlight and the returning ray equals the angle between the antisolar direction and your line of sight.
> - A drop seen 42° from the antisolar direction sends you **red**; its violet, leaving at 40°, passes over your head. A drop seen 40° away sends you **violet**; its red passes below your eye.
> - Every drop 42° from the antisolar point looks red, so red forms a circle of radius 42° and violet a circle of radius 40°. **Red is the outer edge** of the **rainbow**, violet the inner edge.
> - Turning angle: violet is turned through 180° − 40° = **140°**, red through 180° − 42° = 138°. Violet is deviated **more**, just as in a prism. The slide's sentence saying red reaches you because it is "deviated the most" has this backwards (see Errata).
>
> ![[L3b-rainbow-angles.png]]
> *Figure: (a) one drop with the slide's 40° and 42°; (b) the bow as circles of 40° and 42° around the antisolar point (L3b slide 17). Schematic: the Sun's 10° height and the drawing's proportions were chosen for illustration [approximate].*
>
> ![[L3b-s17-rainbow.png]]
> *Figure (L3b slide 17, a textbook figure): left, the path of sunlight through one raindrop; right, the observer, with red reaching the eye from higher drops and violet from lower ones.*
>
> > [!quote] Textbook note
> > Textbook p. 913: from a high drop the most intense red light reaches the observer "because it is deviated the least", while the most intense violet light passes over the observer because it is deviated the most. Light actually leaves a drop over a range of angles from 0° to 42°; 40° to 42° is where the most intense light exits (Pitfall Prevention 34.5).

> [!note]- Why it works
> Sunlight arrives as parallel rays, so every drop sends its colours out at the same angles to the antisolar direction. Your eye collects one colour from each drop, and the drops at a fixed angle around the antisolar point form a circle. Dispersion inside the drop sets the two radii.

> [!question] L3b-Q8x · [Extension] Calculation
> On a summer noon the Sun is 60° above the horizon. Where is the top of the red arc? Can you see a rainbow from flat ground?

> [!success]- Extension answer
> The antisolar point is 60° below the horizon, so the top of the red arc is at 42° − 60° = −18°, below the horizon. From flat ground you cannot see the bow: the Sun has to be lower than 42° for any of it to appear above the horizon.

## Mixed set
No hints. Six questions across L3b.

> [!question] L3b-M1 · Calculation (Assignment 1, Q4, new numbers)
> The index of a glass is 1.53 for violet light and 1.51 for red light. Find the angular separation of the emerging colours for an equilateral prism (A = 60.0°) when the angle of incidence is 50.0°.

> [!success]- Answer
> Violet: sin r₁ = sin 50.0°/1.53, so r₁ = 30.05°; r₂ = 29.95°; sin i₂ = 1.53 sin 29.95°, so i₂ = 49.81°.
> Red: r₁ = 30.49°; r₂ = 29.51°; i₂ = 48.06°.
> Separation: 49.81° − 48.06° = **1.75°**.

> [!question] L3b-M2 · Calculation (L3b slide 15)
> A 60.0° prism gives δmin = 30.0°. Find n.

> [!success]- Answer
> n = sin 45.0°/sin 30.0° = **1.41**.

> [!question] L3b-M3 · Explanation (L3b slide 10)
> Why is the minimum-deviation setting the best one for measuring a prism's index?

> [!success]- Answer
> δ is nearly flat around its minimum, so small errors in the angle of incidence barely change the measured δmin; and at the minimum, n follows from A and δmin alone.

> [!question] L3b-M4 · Comparison (L3b slide 14)
> Glass A has V = 58 and glass B has V = 36. Which disperses more? Which is crown-type and which flint-type?

> [!success]- Answer
> B disperses more, since a lower V means a higher ω. A (V > 50) is crown-type; B (V < 50) is flint-type.

> [!question] L3b-M5 · Prediction (L3b slide 17)
> Which colour is on the top edge of the primary rainbow, and why?

> [!success]- Answer
> Red. Red leaves the drops at 42° to the sunlight and violet at 40°, so the red circle around the antisolar point is the larger one.

> [!question] L3b-M6 · Calculation (L3b slide 8)
> A 60.0° prism has n = 1.70. Find the smallest angle of incidence for which light leaves the second face.

> [!success]- Answer
> θc = sin⁻¹(1/1.70) = 36.0°. The limit is r₂ = 36.0°, so r₁ = 24.0°; sin i₁ = 1.70 sin 24.0° = 0.691, so i₁,min = **43.7°**.

## Practice
Everything needed is here: the slide examples and the assignment question are written out in full. Answer first, then open the boxes. All tutorial and assignment questions, in sheet order, are also collected in [[Tutorials and Assignment]].

### Lecture examples

#### L3b-Ex1
> [!question] L3b-Ex1 · Calculation (L3b slide 15)
> A prism of apex angle 60° gives a minimum deviation of 37°. Find its index of refraction n.

*Think first: write the formula before substituting.*

> [!tip]- Hint
> At minimum deviation, $n = \sin\frac{A+\delta_{min}}{2}\big/\sin\frac{A}{2}$.

> [!success]- Answer
> $$n = \frac{\sin\frac{60^\circ + 37^\circ}{2}}{\sin\frac{60^\circ}{2}} = \frac{\sin 48.5^\circ}{\sin 30^\circ} = \frac{0.7490}{0.5000} = 1.50$$
> **n = 1.50.**

#### L3b-Ex2
> [!question] L3b-Ex2 · Calculation (L3b slide 16)
> A 60° prism of BK7 glass ($n_R = 1.5143$, $n_V = 1.5224$, $n_Y = 1.5170$) is used at minimum deviation. Find $\delta_R$, $\delta_V$, the angle of dispersion θ, the dispersive power ω and the Abbe number V.

*Think first: write the formula for each of the five quantities.*

> [!tip]- Hint
> With A = 60°, $\sin\frac{60^\circ + \delta}{2} = n\sin 30^\circ = n/2$ for each colour. Then $\omega = \frac{n_V - n_R}{n_Y - 1}$ and $V = 1/\omega$.

> [!success]- Answer
> - Red: $\sin\frac{60^\circ + \delta_R}{2} = \frac{1.5143}{2} = 0.75715$, so $\frac{60^\circ + \delta_R}{2} = 49.21^\circ$ and **δ_R = 38.43°**
> - Violet: $\sin\frac{60^\circ + \delta_V}{2} = \frac{1.5224}{2} = 0.76120$, so $\frac{60^\circ + \delta_V}{2} = 49.57^\circ$ and **δ_V = 39.14°**
> - Angle of dispersion: θ = 39.14° − 38.43° = **0.71°**
> - Dispersive power: $\omega = \dfrac{1.5224 - 1.5143}{1.5170 - 1} = \dfrac{0.0081}{0.5170} = $ **0.0157**
> - Abbe number: $V = 1/\omega = $ **63.8**, above 50, so BK7 is a low-dispersion (crown) glass.
>
> The slide's own figures (38.44°, 0.70°, 0.0156, 64.1) contain small slips; see [[L3b Dispersion and Prisms#Errata|L3b errata]].

### Tutorial and assignment questions

#### Assignment 1, Q4
> [!question] A1-Q4 · Calculation (Assignment 1, Q4)
> The index of refraction for violet light in silica flint glass is 1.66 and that for red light is 1.62. What is the angular separation of visible light passing through an equilateral prism of apex angle 60.0° if the angle of incidence is 50.0°?

*Think first: list the steps you will repeat for each colour.*

> [!tip]- Hint
> Trace each colour separately: Snell's law at face 1, then $r_2 = 60^\circ - r_1$, check $r_2$ against the critical angle, then Snell's law at face 2. The separation is the difference between the two exit angles. Keep four figures until the end. Stuck? Revisit [[L3b Dispersion and Prisms#Tracing a ray through a prism|L3b, tracing a ray]].

> [!success]- Answer
> With $\sin 50.0^\circ = 0.7660$:
>
> | Step | Violet, n = 1.66 | Red, n = 1.62 |
> |---|---|---|
> | $\sin r_1 = 0.7660/n$ | 0.4615, so $r_1 = 27.48^\circ$ | 0.4729, so $r_1 = 28.22^\circ$ |
> | $r_2 = 60.0^\circ - r_1$ | $32.52^\circ$ | $31.78^\circ$ |
> | critical angle, $\sin^{-1}(1/n)$ | $37.04^\circ$, so it exits | $38.12^\circ$, so it exits |
> | $\sin i_2 = n\sin r_2$ | 0.892, so $i_2 = 63.17^\circ$ | 0.853, so $i_2 = 58.56^\circ$ |
> | deviation, $\delta = i_1 + i_2 - A$ | $53.17^\circ$ | $48.56^\circ$ |
>
> **Angular separation: 63.17° − 58.56° = 4.61°**, the same as $\delta_V - \delta_R$.

## Errata
> [!bug]- Slide 17, rainbow wording
> The slide says red light from a high drop reaches the observer because it is "deviated the most", and violet passes over because it is "deviated the least". This is reversed. The 40° and 42° are angles between the incoming sunlight and the returning ray, which equal the angles of your line of sight from the antisolar direction. Violet is turned through 140° and red through 138°, so violet is deviated more. Red reaches you from a drop 42° from the antisolar direction because it leaves at the larger angle and so heads down more steeply; that drop's violet, at 40°, passes overhead. Textbook p. 913 gives the corrected wording.

> [!bug]- Slide 9, "symmetric" curve
> The slide says the δ versus $i_1$ curve is symmetric about its minimum. Its own plot is lopsided: for n = 1.52 and A = 60°, δ = 44.3° at 15° below the minimum's incidence but 41.9° at 15° above it. Reversibility pairs each $i_1$ with an $i_2$ that gives the same δ; it does not make the graph a mirror image.

> [!bug]- Slide 16, L3b-Ex2
> (a) The first line should read $\sin\frac{A+\delta_{min}}{2} = n\sin 30^\circ = n/2$; the sine is missing. (b) The red line writes $\delta_V$ where it means $\delta_R$, and rounds 49.214° up to 49.22°; correct values are $\frac{60^\circ+\delta_R}{2} = 49.21^\circ$ and $\delta_R = 38.43^\circ$. (c) θ = 39.14° − 38.43° = 0.71°, not 0.70°. (d) ω = 0.0081/0.517 = 0.0157, not 0.0156. (e) V is written as 1/0.015 = 64.1, but 1/0.015 = 66.7; the correct value is V = 1/0.01567 = 63.8. The conclusion (V > 50, low dispersion) stands.

> [!bug]- Slide 4, spelling
> "$n_{yello}$" should be $n_{yellow}$.

> [!bug]- File naming
> This lecture's file is named "Lecture 4", but its title slide says "Lecture 3". Its content (dispersion, prisms, rainbow) is what these notes call L3b.

## Self-check
Timed run: about 6 minutes, no notes.

> [!question] L3b-S1 · Calculation (L3b slide 10)
> A 60.0° prism gives δmin = 48.0°. Find n.

> [!success]- Answer
> n = sin 54.0°/sin 30.0° = **1.62**.

> [!question] L3b-S2 · Calculation (L3b slide 14)
> A glass has $n_V = 1.5280$, $n_R = 1.5180$ and $n_Y = 1.5220$. Find ω and V, and classify the glass.

> [!success]- Answer
> ω = 0.0100/0.5220 = **0.0192**; V = **52.2**, above 50, so crown-type, low dispersion.

> [!question] L3b-S3 · Explanation (L3b slide 17)
> Which colour does a raindrop turn through the larger angle, and by how much more?

> [!success]- Answer
> Violet: 180° − 40° = 140°, against red's 180° − 42° = 138°, so 2° more.

## Review
Spaced questions from earlier lectures.

> [!question] L3b-R1 · Calculation (from L2, slide 11)
> Find the critical angle for glass with n = 1.60 in air.

> [!success]- Answer
> sin⁻¹(1/1.60) = **38.7°**.

> [!question] L3b-R2 · Calculation (from L3a, slide 15)
> Unpolarized light of intensity I passes three polarizers with axes at 0°, 45° and 90°. What comes out?

> [!success]- Answer
> (I/2)(cos² 45°)(cos² 45°) = **I/8**.

> [!question] L3b-R3 · Calculation (from L3a, slide 18)
> Find the polarizing angle for glass with n = 1.60 in air.

> [!success]- Answer
> tan⁻¹(1.60) = **58.0°**.

> [!question] L3b-R4 · Calculation (from L1, slide 14)
> Two mirrors meet at 90°. A ray hits the first at 35° from its normal. What angle does it make with the second mirror's normal, and which way does it travel afterward?

> [!success]- Answer
> 90° − 35° = 55° from M1's surface; 55° + 90° + x = 180° gives x = 35°; so **55°** from M2's normal. The total turn is 180°, so it travels back parallel to its original path.
