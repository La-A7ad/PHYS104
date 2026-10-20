---
lecture: "L1 Nature of Light"
slides: "Lecture 1 PDF, slides 1 to 15 (content from slide 5)"
textbook: "10th ed. sections 34.1 to 34.3, pp. 898 to 905 (the course numbers this chapter 35)"
tags: [PHYS104, recall]
---
# L1 Nature of Light

[[PHYS104 Recall/Index|Course map]] · [[Recall Log]] · [[Glossary]] · Next: [[L2 Refraction]]

New here? Read [[PHYS104 Recall/Index#How to use it|how to use these notes]] first. Every section starts with a question: answer it before you open anything.

## Goals
- [ ] Explain which observations pushed scientists toward a wave model of light, and which toward photons.
- [ ] Calculate the energy of a photon from its frequency or wavelength.
- [ ] Decide whether the ray approximation holds for an opening of a given size.
- [ ] Apply the law of reflection, measuring angles the way optics does.
- [ ] Predict who can see light reflected from smooth and from rough surfaces.
- [ ] Trace a ray through two mirrors and find its final direction.
- [ ] Predict where light goes after hitting two mirrors that meet at 90°.

## Warm-up
L1 opens the chapter, so these two questions check background the chapter relies on rather than an earlier lecture.

> [!question] L1-W1 · Calculation (background; formula used on L2 slide 6)
> A wave on a rope has crests 0.50 m apart, and 4 crests pass a fixed point every second. Find its wavelength, frequency and speed.

> [!success]- Answer
> Wavelength is the crest-to-crest distance: λ = 0.50 m. Frequency counts complete cycles per second: f = 4.0 Hz. Speed: v = λf = (0.50 m)(4.0 Hz) = 2.0 m/s.

> [!question] L1-W2 · Prediction (background for L1 slide 5)
> Two equal water waves meet. At one spot, a crest of the first arrives together with a trough of the second. What does the water do there? Could two streams of tennis balls ever produce an empty spot that way?

> [!success]- Answer
> The crest and the trough add to zero, so the water stays level: the waves cancel there. Tennis balls cannot cancel; two balls arriving at one spot always deliver more, never nothing. Cancellation is a signature of waves, and the first recall section builds on it.

## Particles or waves
> [!question] L1-Q1 · Explanation (L1 slides 5 to 6)
> Newton treated light as a stream of particles. In 1801 Thomas Young saw light do something particles cannot do. What kind of behaviour was it, and why does it rule out a pure particle picture?

*Think first: write two sentences on paper before opening the hint.*

> [!tip]- Hint
> Use the warm-up: what happens when a crest of one wave meets a trough of another, and what happens when two particles land on the same spot?

> [!success]- Answer
> Young showed that light rays **interfere**: where two beams overlap, they can strengthen each other in some places and cancel to darkness in others. Cancellation is natural for waves, because a crest and a trough add to zero. Particles cannot do it: two particles arriving at one spot always bring more energy, never zero. So interference was the first clear evidence that light behaves as a wave.
> During the 19th century the wave picture firmed up: Maxwell identified light as a high-frequency electromagnetic wave, and Hertz confirmed Maxwell's predictions experimentally.
>
> Background (L1 slide 5): until about 1800 most scientists pictured light as a stream of particles emitted by the object being viewed, which stimulated sight on entering the eye. Newton was the chief architect of that particle model; Huygens argued that light might instead be a wave.

> [!note]- Why it works
> Wave disturbances add with sign, so a positive and a negative displacement can cancel. Particle arrivals only add. Any experiment that makes darkness by adding two beams together is therefore evidence for waves.

> [!question] L1-Q1x · [Extension] Explanation
> Newton's particle model could already explain reflection and refraction. Why couldn't a good explanation of refraction settle the particle versus wave debate on its own?

> [!success]- Extension answer
> Because the wave model explains reflection and refraction too, so both models pass that test. Deciding between them needs a result that only one model predicts, and interference was that result.
>
> > [!quote] Textbook note
> > Textbook p. 899: Newton used his particle model to explain reflection and refraction, and Huygens (1678) showed that a wave model could explain both as well.

## Energy carried by light
> [!question] L1-Q2 · Calculation (L1 slide 7; frequencies from L3a slide 6)
> Visible light runs from about 4.00 × 10¹⁴ Hz (red) to 7.50 × 10¹⁴ Hz (violet). Find the energy of one red photon and of one violet photon. If you make the red light twice as bright, does each red photon carry more energy?

*Think first: write the formula you would use and a rough answer before opening Hint 1.*

> [!tip]- Hint 1
> Einstein's photon model gives each photon an energy fixed by one property of the light, multiplied by Planck's constant. Stuck? Read [[Photon energy]] first.

> [!tip]- Hint 2
> Multiply h = 6.63 × 10⁻³⁴ J·s by each frequency. Then look at the formula: does brightness appear in it anywhere?

> [!success]- Answer
> Photon energy (L1 slide 7): $E = hf$, with $h = 6.63\times10^{-34}$ J·s, $f$ in hertz and $E$ in joules.
> - Red: $E = (6.63\times10^{-34})(4.00\times10^{14}) = 2.65\times10^{-19}$ J
> - Violet: $E = (6.63\times10^{-34})(7.50\times10^{14}) = 4.97\times10^{-19}$ J
>
> A violet photon carries 7.50/4.00 = 1.9 times the energy of a red one. Making the red beam brighter does **not** change the energy of each red photon: brightness does not appear in $E = hf$, so a brighter beam at the same frequency must carry more photons, not bigger ones.

> [!note]- Why it works
> In the photon picture, light's energy comes in lumps (quanta) whose size is set by frequency. In 1905 Einstein used this idea, built on Max Planck's quantization of 1900, to explain the photoelectric effect (L1 slide 7), whose puzzle was that the ejected electrons' kinetic energy does not depend on the light's intensity (slide 6). Light shows wave behaviour in some experiments and particle behaviour in others: its dual nature.

> [!question] L1-Q2x · [Extension] Comparison
> An FM radio station broadcasts at 100 MHz. How many of its photons carry the same total energy as a single violet photon (7.50 × 10¹⁴ Hz)?

> [!success]- Extension answer
> Energy per photon is proportional to f, so the ratio is $\dfrac{7.50\times10^{14}}{1.00\times10^{8}} = 7.5\times10^{6}$. It takes about 7.5 million radio photons to match one violet photon.

## Waves meeting an opening
> [!question] L1-Q3 · Prediction (L1 slides 8 to 9)
> A plane wave of wavelength λ reaches a barrier with an opening of width d. Sketch what the wave looks like beyond the opening when (a) d is much larger than λ, (b) d is about equal to λ, (c) d is much smaller than λ. In which case can you draw the light as straight rays?

*Think first: make three quick sketches before opening the hint.*

> [!tip]- Hint
> A ray is drawn perpendicular to the wave fronts. Ask when the wave fronts coming through the opening stay flat. Stuck? Read [[Ray approximation]] first.

> [!success]- Answer
> (a) λ ≪ d: the wave passes through and keeps going straight, apart from small edge effects. Straight rays describe it well.
> (b) λ ≈ d: the wave spreads out after the opening.
> (c) λ ≫ d: the opening behaves like a point source, sending out spherical waves.
>
> The spreading in (b) and (c) is **diffraction**. Only case (a) can be drawn with straight rays. That is the **ray approximation**: in a uniform medium light travels in straight lines, changing direction only where the medium changes (L1 slide 8). The rest of the chapter assumes λ ≪ d.
>
> ![[L1-s08-rays.png]]
> *Figure (L1 slide 8): rays are straight lines perpendicular to the wave fronts. They spread from a point source (left) and run parallel for a plane wave (right).*
>
> ![[L1-s09-barrier.png]]
> *Figure (L1 slide 9): a plane wave meeting an opening of width d, for λ ≪ d, λ ≈ d and λ ≫ d.*

> [!note]- Why it works
> Rays point the way the wave travels, perpendicular to its wave fronts (slide 8). A wide opening lets a long, flat stretch of wave front through, so the rays stay parallel. A narrow opening lets through only a short piece, which acts like a new source and curves outward.

> [!question] L1-Q3x · [Extension] Comparison
> Visible light (λ ≈ 500 nm) and a sound wave with λ = 0.90 m both pass through a doorway 0.90 m wide. Which one can be treated with straight rays?

> [!success]- Extension answer
> Light: d/λ = 0.90/(5.0 × 10⁻⁷) = 1.8 × 10⁶, so λ ≪ d and the ray approximation holds. Sound: λ ≈ d, so it spreads out after the doorway instead of travelling as a straight beam.

## Bouncing off a flat mirror
> [!question] L1-Q4 · Prediction (L1 slides 10 to 11)
> (a) A ray hits a flat mirror making 30° with the mirror's surface. What is its angle of reflection? (b) A second ray hits the mirror head-on. Where does it go? (c) A third ray is sent backward along a reflected path. What path does it take?

*Think first: draw each case before opening the hint.*

> [!tip]- Hint
> Optics measures every angle from the normal, the line perpendicular to the surface, not from the surface itself. Stuck? Read [[Law of reflection]] first.

> [!success]- Answer
> (a) 30° from the surface is 90° − 30° = 60° from the normal. So the **angle of incidence** is 60°, and the **angle of reflection** is also 60° from the normal, on the other side of it (again 30° from the surface).
> (b) Head-on means along the normal: the angle of incidence is 0°, so the angle of reflection is 0° and the ray comes straight back on itself.
> (c) It retraces the original incident path in reverse: light paths are reversible.
>
> In every case the incident ray, the reflected ray and the normal lie in one plane. Together with $\theta_1' = \theta_1$, that is the **law of reflection** (L1 slide 10).
>
> **Reflection** itself is light rebounding when it meets a reflecting surface (slide 10).
>
> ![[L1-s10-reflection.png]]
> *Figure (L1 slide 10): the angle of incidence θ₁ and the angle of reflection θ₁′, both measured from the normal.*

> [!note]- Why it works
> The law compares angles measured from the normal. Swapping the incident and reflected rays leaves $\theta_1' = \theta_1$ unchanged, which is why paths are reversible. Mixing up surface angles and normal angles is the most common slip in mirror problems.

> [!question] L1-Q4x · [Extension] Calculation
> A laser beam hits a mirror at 40° from the normal. Through what angle has the beam's direction of travel turned after it reflects?

> [!success]- Extension answer
> The incident and reflected rays are each 40° from the normal, so the angle between them is 80°. The direction of travel has turned by 180° − 80° = 100°. In general a single reflection turns a ray by 180° − 2θ.

## Smooth and rough surfaces
> [!question] L1-Q5 · Comparison (L1 slides 12 to 13)
> A laser beam hits a polished mirror, and then a sheet of white paper. In which case can people standing at many different positions see the reflected light? Does the paper obey the law of reflection?

*Think first: decide, then sketch the surface normals for both surfaces.*

> [!tip]- Hint
> Zoom in on each surface and draw the normal at several points where light lands.

> [!success]- Answer
> On the smooth mirror all the normals point the same way, so parallel incoming rays leave parallel. This is **specular** reflection, and only an eye in that one direction sees the light. On the rough paper the normals point in many directions, so the reflected rays scatter in many directions. This is **diffuse** reflection, visible from almost anywhere.
> The paper still obeys $\theta_1' = \theta_1$ at every tiny patch. The patches just face different ways.
>
> ![[L1-s12-specular.png]]
> *Figure (L1 slide 12): specular reflection from a smooth surface. Parallel rays stay parallel, so only an eye in the right place sees the light.*
>
> ![[L1-s13-diffuse.png]]
> *Figure (L1 slide 13): diffuse reflection from a rough surface. Rays leave in all directions, so eyes in many positions see the light.*

> [!note]- Why it works
> The law of reflection is local: it holds at each point, relative to that point's own normal. A rough surface is a collection of tiny mirrors tilted at different angles, so one law produces many outgoing directions.

> [!question] L1-Q5x · [Extension] Explanation
> At night a wet road is hard to see in your own headlights, but a dry road is easy to see. Explain using the two kinds of reflection.

> [!success]- Extension answer
> A film of water makes the road surface smooth, so your headlight beam reflects specularly, forward and away from you, and little comes back to your eyes. A dry road is rough, so it reflects diffusely and sends some of the light back toward you.
>
> > [!quote] Textbook note
> > Textbook p. 902 gives this example. It also gives the condition for "smooth": a surface acts as a mirror when its bumps are much smaller than the wavelength of the light.

## Two mirrors at an angle
> [!question] L1-Q6 · Calculation (L1 slide 14, L1-Ex1 with new numbers; same skill as Tutorial 1, Q1)
> Two mirrors meet at 110°. A ray hits mirror M1 at 50° from its normal, reflects, and then hits mirror M2. What angle does the ray make with M2's normal?

*Think first: sketch the two mirrors and the ray before opening Hint 1.*

> [!tip]- Hint 1
> The ray between the mirrors forms a triangle with them, and the triangle's angles add to 180°.

> [!tip]- Hint 2
> Start at M1: the reflected ray is 50° from M1's normal, so how many degrees is it from M1's surface? Stuck? Read [[Mirror pairs and retroreflection]] first.

> [!success]- Answer
> 1. Law of reflection at M1: the ray leaves at 50° from the normal, which is 90° − 50° = 40° from M1's surface.
> 2. Triangle formed by the ray and the two mirrors: 40° + 110° + x = 180°, so x = 30° between the ray and M2's surface.
> 3. Convert to M2's normal: 90° − 30° = **60°**. The ray also reflects from M2 at 60°.
>
> Check: each reflection turns the ray by 180° − 2θ, so the two turns add to (180° − 100°) + (180° − 120°) = 140°.
> Slide check: with L1-Ex1's numbers (120°, 65°) the same steps give 25°, then 35°, then 55° from M2's normal, as the slide says.

> [!note]- Why it works
> Each reflection obeys θ' = θ at its own mirror, and the triangle converts the angle leaving M1 into the angle arriving at M2. Every step switches between "from the normal" and "from the surface", which is where most errors come from.

> [!question] L1-Q6x · [Extension] Calculation
> Two mirrors meet at 60°. A ray hits M1 at 40° from the normal. Find the angle it makes with M2's normal, and the total angle through which the two reflections turn it.

> [!success]- Extension answer
> At M1: 90° − 40° = 50° from the surface. Triangle: 50° + 60° + x = 180°, so x = 70° from M2's surface, which is **20°** from M2's normal. Total turn: (180° − 80°) + (180° − 40°) = 240°.

## Mirrors at right angles
> [!question] L1-Q7 · Prediction (L1 slide 15)
> Two mirrors meet at exactly 90°. A ray hits the first mirror at angle θ from its normal and reflects from both mirrors. Predict the direction of the outgoing ray compared with the incoming one. Does your answer depend on θ?

*Think first: predict, then test your prediction with θ = 30° before opening the hint.*

> [!tip]- Hint
> Use the triangle method from the previous section with θ = 30°, then add up how much each reflection turns the ray.

> [!success]- Answer
> With θ = 30°: the ray leaves M1 at 60° from its surface. The triangle gives 60° + 90° + x = 180°, so x = 30° from M2's surface, or 60° from M2's normal. The turns are 180° − 60° = 120° at M1 and 180° − 120° = 60° at M2, a total of 180°. The ray goes back exactly parallel to the way it came.
> For any θ the turns are (180° − 2θ) + (180° − 2(90° − θ)) = 180°, so the result does **not** depend on θ. This is **retroreflection**.
>
> > [!quote] Textbook note
> > Textbook p. 903 proves the general rule: two reflections turn a ray by 360° − 2φ, where φ is the angle between the mirrors. For φ = 90° that is 180°. For L1-Q6 it gives 360° − 220° = 140°, matching the check there.

> [!note]- Why it works
> With mirrors at 90°, the angle at the second mirror's normal is always the complement of θ, so the two turns always add to 180°. That is why corner reflectors return light toward its source without careful aiming; L1 slide 15 shows a panel on the Moon, car taillights and road signs.
>
> ![[L1-s15-retroreflection.png]]
> *Figure (L1 slide 15): retroreflectors on the Moon, in a car taillight, a transparent sphere, and a stop sign covered in tiny spheres.*

> [!question] L1-Q7x · [Extension] Explanation
> A reflector panel on the Moon returns a laser pulse to the observatory on Earth that sent it, even though nobody aimed it precisely. Two mirrors at 90° only do this for rays travelling in one plane. What does the panel need to work for rays arriving from any direction?

> [!success]- Extension answer
> A third mirror, perpendicular to the other two, so that the three form the corner of a cube. The panel is an array of these corner cubes, so it returns light from any direction.
>
> > [!quote] Textbook note
> > Textbook p. 904: adding a third mirror perpendicular to the first two makes a cube corner, and retroreflection then works in three dimensions. The Apollo 11 panel used many of them.

## Mixed set
No hints. Answer all five, then check.

> [!question] L1-M1 · Calculation (L1 slide 7)
> Find the energy of one photon of light with wavelength 600 nm.

> [!success]- Answer
> f = c/λ = (3.00 × 10⁸)/(600 × 10⁻⁹) = 5.00 × 10¹⁴ Hz, then E = hf = (6.63 × 10⁻³⁴)(5.00 × 10¹⁴) = **3.32 × 10⁻¹⁹ J**.

> [!question] L1-M2 · Prediction (L1 slide 9)
> Sunlight (λ ≈ 500 nm) passes through a 1.0 cm hole in a curtain. Does it continue as a straight beam or spread widely?

> [!success]- Answer
> λ/d = (5.0 × 10⁻⁷ m)/(1.0 × 10⁻² m) = 5 × 10⁻⁵, so λ ≪ d. It continues as a straight beam; the ray approximation holds.

> [!question] L1-M3 · Calculation (Tutorial 1, Q1, new numbers)
> Two plane mirrors meet at right angles. A beam strikes the first mirror 10.0 cm from the corner and must then hit the second mirror 25.0 cm from the corner. What angle of incidence is needed at the first mirror?

> [!success]- Answer
> After reflection the ray covers 10.0 cm along the first mirror's direction and 25.0 cm along the second mirror, which is parallel to the first mirror's normal. Measured from that normal, tan θ = 10.0/25.0, so θ = **21.8°**. The angle of incidence equals this angle of reflection.

> [!question] L1-M4 · Explanation (L1 slide 11)
> Why does a ray that strikes a mirror along its normal come straight back?

> [!success]- Answer
> Along the normal the angle of incidence is 0°. The law of reflection makes the angle of reflection 0° as well, so the reflected ray lies along the normal, pointing back the way the ray came.

> [!question] L1-M5 · Comparison (L1 slides 13 and 15)
> At night your headlights shine on a road sign covered in tiny glass spheres and on a sheet of white paper beside it. Which sends more of your own light back toward you, and why?

> [!success]- Answer
> The sign. Its spheres retroreflect, returning light toward its source (L1 slide 15). The paper reflects diffusely, spreading light in all directions, so only a small part comes back to you.

## Practice
Everything needed is here: the slide's worked example and the tutorial question are written out in full, with their figures. Answer first, then open the boxes. All tutorial and assignment questions, in sheet order, are also collected in [[Tutorials and Assignment]].

### Lecture examples

#### L1-Ex1
> [!question] L1-Ex1 · Calculation (L1 slide 14)
> Two mirrors meet at an angle of 120°. A ray strikes mirror M1 at 65° from the normal. Find the angle the ray makes with the normal to mirror M2 after it has reflected from both mirrors.

*Think first: sketch the two mirrors and the ray before opening the hint.*

> [!tip]- Hint
> Turn the angle leaving M1 into an angle with M1's surface, then use the triangle formed by the ray and the two mirrors.

> [!success]- Answer
> 1. Law of reflection at M1: the ray leaves at 65° from the normal, which is 90° − 65° = 25° from M1's surface.
> 2. Triangle formed by the ray and the two mirrors: 25° + 120° + x = 180°, so x = 35° between the ray and M2's surface.
> 3. From M2's normal: 90° − 35° = **55°**. The ray also reflects from M2 at 55°.
>
> Check: the two reflections turn the ray by (180° − 130°) + (180° − 110°) = 120°, which equals 360° − 2(120°).
>
> ![[L1-two-mirror.png]]
> *Figure: L1-Ex1 drawn to scale from the slide's values (L1 slide 14). Black arcs are angles from normals, blue arcs angles from surfaces.*

### Tutorial and assignment questions

#### Tutorial 1, Q1
> [!question] T1-Q1 · Calculation (Tutorial 1, Q1)
> Two plane mirrors intersect at right angles. A laser beam strikes the first of them at a point 11.5 cm from their point of intersection, as shown in the figure. For what angle of incidence at the first mirror will this ray strike the midpoint of the second mirror (which is 28.0 cm long) after reflecting from the first mirror?
>
> ![[L1-T1Q1-mirrors.png]]
> *Figure: Tutorial 1, Q1.*

*Think first: mark the midpoint of the second mirror, then sketch the reflected ray.*

> [!tip]- Hint
> The midpoint is half the second mirror's length from the corner. The first mirror's normal runs parallel to the second mirror, so the reflected ray's run along each mirror gives the angle through one tangent. Stuck? Revisit [[L1 Nature of Light#Two mirrors at an angle|L1, two mirrors]].

> [!success]- Answer
> 1. Midpoint of the 28.0 cm mirror: 14.0 cm from the corner.
> 2. After reflection the ray covers 11.5 cm along the first mirror and 14.0 cm along the second mirror, which is parallel to the first mirror's normal.
> 3. Angle from the normal: $\tan\theta = \dfrac{11.5}{14.0} = 0.821$, so $\theta = 39.4^\circ$.
> 4. Law of reflection: the angle of incidence equals this angle of reflection.
>
> **Answer: 39.4°.**

## Errata
> [!bug]- L1 slides: nothing to correct
> Every number on the L1 slides was recomputed, including L1-Ex1 (55°), and no errors were found. The energy-versus-wavelength error sometimes attributed to Lecture 1 is on the L3a spectrum slide (slide 6); see [[L3a Polarization#Errata|L3a errata]].

## Self-check
Timed run: about 6 minutes for all three, no notes.

> [!question] L1-S1 · Calculation (L1 slide 14)
> Two mirrors meet at 130°. A ray hits M1 at 70° from its normal. What angle does it make with M2's normal?

> [!success]- Answer
> At M1: 90° − 70° = 20° from the surface. Triangle: 20° + 130° + x = 180°, so x = 30°, giving **60°** from M2's normal. Check: turns of 40° + 60° = 100° = 360° − 2(130°).

> [!question] L1-S2 · Calculation (L1 slide 7)
> A photon carries 3.00 × 10⁻¹⁹ J. Find its frequency and its wavelength. Is it visible?

> [!success]- Answer
> f = E/h = (3.00 × 10⁻¹⁹)/(6.63 × 10⁻³⁴) = **4.52 × 10¹⁴ Hz**. λ = c/f = (3.00 × 10⁸)/(4.52 × 10¹⁴) = 6.63 × 10⁻⁷ m = **663 nm**: inside the visible range on L3a slide 6 (400 to 750 nm), toward the red end.

> [!question] L1-S3 · Explanation (L1 slides 6 to 7)
> State the photoelectric observation that the wave model could not explain, and the idea Einstein used to explain it.

> [!success]- Answer
> The kinetic energy of the electrons ejected from a metal does not depend on the light's intensity. Einstein explained it with photons: light's energy comes in lumps of size E = hf, set by the frequency rather than by the brightness.
