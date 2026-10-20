---
lecture: "L3a Polarization"
slides: "Lecture 3 PDF (title slide: Lecture 3), slides 1 to 18"
textbook: "10th ed. section 34.6, p. 914 (mirage paragraph) only; apparent depth and polarization are outside this textbook chapter"
tags: [PHYS104, recall]
---
# L3a Polarization

[[PHYS104 Recall/Index|Course map]] · [[Recall Log]] · [[Glossary]] · Previous: [[L2 Refraction]] · Next: [[L3b Dispersion and Prisms]]

Every section starts with a question: answer it before you open anything. How it works: [[PHYS104 Recall/Index#How to use it|see the Index]].

## Goals
- [ ] Explain the "wet road" illusion on a hot day using how the air's index of refraction varies.
- [ ] Calculate the apparent depth of an object viewed from directly above.
- [ ] Describe the structure of an electromagnetic wave.
- [ ] Order regions of the electromagnetic spectrum by wavelength, frequency and photon energy.
- [ ] Explain what polarized light is and what a polarizer does to unpolarized light.
- [ ] Derive Malus's law and use it for one or more polarizers.
- [ ] Find the polarizing angle for reflection and derive Brewster's law.

## Warm-up
Two questions from [[L2 Refraction|L2]].

> [!question] L3a-W1 · Calculation (L2 slide 11)
> Find the critical angle for light in water (n = 1.33) meeting air.

> [!success]- Answer
> sin θc = 1.00/1.33, so θc = 48.8°.

> [!question] L3a-W2 · Calculation (L2 slide 8)
> Light with a wavelength of 600 nm in air enters glass (n = 1.50). Find its wavelength and its frequency in the glass.

> [!success]- Answer
> λ = 600/1.50 = 400 nm. f = c/λ_air = (3.00 × 10⁸)/(600 × 10⁻⁹) = 5.00 × 10¹⁴ Hz, unchanged by the glass.

## The puddle on a hot road
> [!question] L3a-Q1 · Explanation (L3a slide 2)
> On a hot day the road far ahead seems to hold a puddle that disappears as you drive closer. Air touching the hot road has a smaller index of refraction than the cooler air above it. What are you really seeing?

*Think first: write one sentence about where the light in the "puddle" actually comes from.*

> [!tip]- Hint
> Use Huygens' wavelets: in which layer of air do they grow fastest, and which way does that tilt a wave front heading down toward the road?

> [!success]- Answer
> You are seeing the sky. Light from the sky heading down toward the road at a shallow angle passes into warmer, lower-index air, where it travels faster. The lower part of each wave front gets ahead, so the front tilts and the ray curves upward before it reaches the road. It arrives at your eye from below, and your eye traces it back in a straight line to the road surface. A patch of sky seen "on the road" looks like water reflecting the sky. This illusion is a **mirage**.
>
> ![[L3a-s02-mirage.png]]
> *Figure (L3a slide 2): a mirage photograph; wave fronts tilting because light is fastest in the hot air near the ground; rays from a palm tree curving up to an observer, who sees an inverted image as if reflected in water.*
>
> > [!quote] Textbook note
> > Textbook p. 914: light from the sky reaching the hot roadway at a shallow angle refracts continuously, misses the road, and curves back upward into your eye, so the road looks wet.

> [!note]- Why it works
> A ray always bends toward the region where light is slower (higher n), as at every boundary in L2. Here the index changes gradually with height, so the bend is a smooth curve instead of a sharp kink. The slide's lower figure labels the turning point "total internal reflection"; treating the smooth turn as that limiting case is an interpretation, not something the course spells out [Guessing].

> [!question] L3a-Q1x · [Extension] Prediction
> Over a very cold sea, the air touching the water is colder (higher n) than the air above it. Which way do nearly horizontal rays from a distant ship curve, and does the ship look higher or lower than it really is?

> [!success]- Extension answer
> Rays bend toward the slower, higher-index layer, so they curve downward, following the cold water. Your eye traces each arriving ray back in a straight line, so the ship looks higher than it really is, and a ship just beyond the horizon can come into view [Guessing: the course does not cover this case; it follows from the same bending rule].

## Looking down into water
> [!question] L3a-Q2 · Calculation (L3a slides 3 to 4, L3a-Ex4 with new numbers)
> (a) A coin lies on the bottom of a fountain 1.20 m deep (n = 1.33). Looking straight down, how deep does it appear? (b) A fish looks straight up at a lamp hanging 1.50 m above the water. How far above the surface does the lamp appear to the fish?

*Think first: guess whether each object looks nearer or farther than it really is.*

> [!tip]- Hint 1
> Apparent depth for straight-down viewing (L3a slide 3): $d' = d\,\dfrac{n_2}{n_1}$. Stuck? Read [[Apparent depth]] first.

> [!tip]- Hint 2
> $n_1$ belongs to the medium the object is in, $n_2$ to the observer's medium. For the coin, $n_1 = 1.33$ and $n_2 = 1.00$.

> [!success]- Answer
> (a) Object in water, viewer in air: $d' = 1.20 \times \dfrac{1.00}{1.33} = 0.902$ m. The coin's **apparent depth** is about 30 cm less than its real depth.
> (b) Object in air, viewer in water: $d' = 1.50 \times \dfrac{1.33}{1.00} = 2.00$ m. The lamp looks farther away than it is.
>
> Slide check: L3a-Ex4 gives 3.00/1.33 = 2.26 m, as the slide says.
>
> ![[L3a-s03-apparent-depth.png]]
> *Figure (L3a slide 3): (a) a slanted view, where the apparent depth is hard to work out; (b) viewing from directly above, where d′ = d n₂/n₁.*

> [!note]- Why it works
> Rays leaving water bend away from the normal, so when your eye traces them back in straight lines they seem to come from a point nearer the surface. For a fish looking up the bending is reversed, so things above the water seem farther away. The formula holds only for viewing nearly straight down; slide 3 notes that a slanted view is much harder to work out.

> [!question] L3a-Q2x · [Extension] Calculation
> A 0.10 m layer of oil (n = 1.45) floats on 0.50 m of water (n = 1.33). Looking straight down from the air, how deep does the bottom appear?

> [!success]- Extension answer
> Work up from the bottom. Seen from inside the oil, the bottom lies $0.50 \times \frac{1.45}{1.33} = 0.545$ m below the oil-water surface, so $0.10 + 0.545 = 0.645$ m below the oil's top. Seen from the air: $0.645 \times \frac{1.00}{1.45} = 0.445$ m. This equals $\frac{0.10}{1.45} + \frac{0.50}{1.33}$: each layer contributes its thickness divided by its index.

## What an electromagnetic wave is made of
> [!question] L3a-Q3 · Explanation (L3a slide 5)
> An electromagnetic wave travels along +x, and its electric field oscillates along y. Along which axis does its magnetic field oscillate? Is the wave transverse or longitudinal, and what kind of source produces such waves?

*Think first: draw the three axes before opening the hint.*

> [!tip]- Hint
> The electric field, the magnetic field and the direction of travel are all perpendicular to one another.

> [!success]- Answer
> The magnetic field oscillates along **z**: E along y, B along z and travel along x are mutually perpendicular, and the wave travels in the direction of $\vec{E}\times\vec{B}$ (slide 5's figure). Both fields oscillate across the direction of travel, so an **electromagnetic wave** is **transverse**. Such waves are produced by accelerating charges, such as electrons or protons. In vacuum they travel at $c = 3\times10^8$ m/s; in a medium they are slower. Light is an electromagnetic wave.
>
> ![[L3a-s05-em-wave.png]]
> *Figure (L3a slide 5): E along y and B along z, with the wave travelling along x, the direction of E × B.*

> [!note]- Why it works
> Because the electric field oscillates sideways, there is a choice of sideways direction for it: up-down, left-right, or anything in between. Choosing one of those directions is what polarization means (slides 7 to 8), which is where this lecture goes next.

> [!question] L3a-Q3x · [Extension] Prediction
> Sound in air is longitudinal: the air moves back and forth along the direction the wave travels. Could a filter like a polarizer select one direction of oscillation for sound?

> [!success]- Extension answer
> No. Polarizing means choosing among sideways directions of oscillation. A longitudinal wave oscillates only along its direction of travel, so there is no sideways direction to choose.

## Ordering the spectrum
> [!question] L3a-Q4 · Comparison (L3a slide 6)
> Rank radio waves, visible light and X-rays by wavelength, by frequency and by photon energy. Then read the two arrow statements under the spectrum on L3a slide 6: is each one right?

*Think first: write the three rankings before opening the hint.*

> [!tip]- Hint
> Two relations connect everything: $c = \lambda f$ in vacuum, and $E = hf$ for one photon (L1 slide 7). Stuck? Read [[Electromagnetic spectrum]] first.

> [!success]- Answer
> - Wavelength: radio > visible > X-rays.
> - Frequency: X-rays > visible > radio, since $f = c/\lambda$.
> - Photon energy: the same order as frequency, since $E = hf$.
>
> The **electromagnetic spectrum** runs from radio waves through microwaves, infrared, visible light and ultraviolet to X-rays and gamma rays. Visible light spans about $7.5\times10^{-7}$ m (red, $f = c/\lambda = 4.0\times10^{14}$ Hz) to $4.0\times10^{-7}$ m (violet, $7.5\times10^{14}$ Hz).
> On slide 6 the first line is right: shorter λ means higher f and more energy. The second line is **wrong**: longer λ means lower f and **less** energy. See Errata.
>
> ![[L3a-s06-spectrum.png]]
> *Figure (L3a slide 6): the spectrum by wavelength and frequency; the visible band runs from 7.5 × 10⁻⁷ m (red, 4 × 10¹⁴ Hz) to 4.0 × 10⁻⁷ m (violet, 7.5 × 10¹⁴ Hz). The slide's two arrow statements are left out of this crop because the second is wrong.*

> [!note]- Why it works
> In vacuum every electromagnetic wave travels at c, so wavelength and frequency are locked together inversely. Photon energy follows frequency, so long-wavelength radio photons carry the least energy and X-ray photons far more.

> [!question] L3a-Q4x · [Extension] Calculation
> Compare one photon of 100 MHz radio with one X-ray photon of frequency 1.0 × 10¹⁸ Hz. What is the ratio of their energies?

> [!success]- Extension answer
> $E \propto f$, so the ratio is $\dfrac{1.0\times10^{18}}{1.0\times10^{8}} = 1.0\times10^{10}$: the X-ray photon carries ten billion times more energy.

## Ropes and slots
> [!question] L3a-Q5 · Prediction (L3a slides 7 to 8)
> A rope is shaken up and down, and the wave passes through a vertical slot in a fence. A second slot, turned horizontal, stands further along. Predict what passes each slot. What is the light version of this experiment?

*Think first: predict both slots before opening the hint.*

> [!tip]- Hint
> Ask in which direction the rope moves, and whether each slot lets it move that way. Stuck? Read [[Polarization and polarizers]] first.

> [!success]- Answer
> The rope vibrates vertically, so the wave is **polarized** in the vertical direction. The vertical slot lets that motion through. The horizontal slot blocks it, because the rope cannot move up and down inside a horizontal gap. Nothing passes the second slot.
> For light: in **linearly polarized** light the electric field vibrates in one direction only, while in **unpolarized** light it vibrates in all directions across the beam (slide 7). A **polarizer** passes the field component along its **transmission axis**. Two polarizers with axes at 90° ("crossed") pass nothing.
> Slide 8's statement (b) says the opposite for the perpendicular slot; see Errata.
>
> ![[L3a-s07-polarized.png]]
> *Figure (L3a slide 7): the electric field of unpolarized light points every way across the beam; in polarized light it points one way.*
>
> ![[L3a-s08-slots.png]]
> *Figure (L3a slide 8): (a) a vertically vibrating rope passes a vertical slot; (b) a horizontally vibrating rope is blocked by it.*
>
> ![[L3a-s08-ropes.png]]
> *Figure (L3a slide 8): rope waves. Warning: the slide's labels are swapped. The rope vibrating up and down is vertically polarized; the side-to-side rope is horizontally polarized.*

> [!note]- Why it works
> A slot transmits only motion along its length. For light, the transmission axis plays the slot: the field component along it passes and the perpendicular component is absorbed.

> [!question] L3a-Q5x · [Extension] Prediction
> The rope is now shaken in a circle. What comes through a vertical slot?

> [!success]- Extension answer
> Only the up-and-down part of the motion passes, so beyond the slot the rope vibrates vertically: the circular motion has become a vertically polarized wave.

## Unpolarized light meets a polarizer
> [!question] L3a-Q6 · Prediction (L3a slide 9)
> Unpolarized light of intensity 8.0 W/m² falls on a single polarizer. What intensity comes out? Does it change if you rotate the polarizer about the beam?

*Think first: commit to a number before opening the hint.*

> [!tip]- Hint
> Unpolarized light has no preferred direction of vibration. What does that say about rotating the polarizer?

> [!success]- Answer
> **4.0 W/m²**. A polarizer passes half the intensity of unpolarized light (L3a slide 9), and rotating it changes nothing, because unpolarized light has no special direction to line up with. The light that comes out is polarized along the polarizer's axis.
>
> The slides call the polarizing sheet a **Polaroid**. It works by selective absorption: it passes the field component along its transmission axis and absorbs the perpendicular component (slide 9).
>
> ![[L3a-s09-polarizer.png]]
> *Figure (L3a slide 9): unpolarized light of intensity I₀ leaves the polarizer polarized, with intensity ½I₀.*

> [!note]- Why it works
> The slides state the factor ½ without deriving it. Since unpolarized light is an even mix of every vibration direction, no orientation of the polarizer is special, so the result cannot depend on the angle.

> [!question] L3a-Q6x · [Extension] Prediction
> The 4.0 W/m² beam now passes a second polarizer with the same axis as the first. What comes out, and why isn't it halved again?

> [!success]- Extension answer
> 4.0 W/m². The light is already polarized along that axis, so the angle between its polarization and the second axis is 0°, and nothing is lost. Halving applies only to unpolarized light.

## Deriving Malus's law
> [!question] L3a-D1 · Derivation (L3a slides 10 to 11)
> Polarized light with field amplitude $E_0$ and intensity $I_0$ reaches a second polarizer, the **analyzer**, whose transmission axis makes angle θ with the light's polarization. Find the transmitted intensity I as a function of θ.

*Think first: draw $E_0$ as an arrow and the analyzer's axis as a line at angle θ to it.*

> [!tip]- Hint
> Split the arrow into a part along the axis and a part across it. Stuck? Read [[Malus's law]] first.

> [!question] Step 1
> Which component of $E_0$ passes the analyzer, and which is absorbed?

> [!success]- Step 1 result
> The component along the axis, $E = E_0\cos\theta$, passes. The perpendicular component, $E_0\sin\theta$, is absorbed.
>
> ![[L3a-s11-components.png]]
> *Figure (L3a slide 11): E₀ resolved along the analyzer's axis (E₀ cos θ, transmitted) and across it (absorbed).*

> [!question] Step 2
> How does intensity depend on field amplitude?

> [!success]- Step 2 result
> Intensity is proportional to the square of the amplitude: $I_0 \propto E_0^2$ and $I \propto (E_0\cos\theta)^2$.

> [!question] Step 3
> Combine the two results into a ratio.

> [!success]- Step 3 result
> $\dfrac{I}{I_0} = \left(\dfrac{E_0\cos\theta}{E_0}\right)^2 = \cos^2\theta$

> [!success]- Full derivation
> 1. Resolve $E_0$ along and across the analyzer's axis: $E_0\cos\theta$ passes, $E_0\sin\theta$ is absorbed.
> 2. Intensity goes as amplitude squared: $I_0 \propto E_0^2$ and $I \propto E_0^2\cos^2\theta$.
> 3. Divide: $I = I_0\cos^2\theta$, **Malus's law**.
>
> Special cases (slide 12): θ = 0° gives $I_0$ (maximum), θ = 45° gives $I_0/2$, θ = 90° gives 0 (minimum). Between 0° and 90° the output falls steadily.
>
> ![[L3a-s10-setup.png]]
> *Figure (L3a slide 10): the setup. Unpolarized light, polarizer, polarized light of amplitude E₀, analyzer at angle θ, transmitted amplitude E₀ cos θ, then a photocell that measures the intensity.*
>
> ![[L3a-s12-special-cases.png]]
> *Figure (L3a slide 12): two polarizing sheets with parallel axes (bright), at an angle (dimmer) and crossed (dark).*

> [!note]- Why it works
> The analyzer keeps only the projection of the field onto its axis. Squaring turns that amplitude into intensity, which is why the fall-off is $\cos^2\theta$ rather than $\cos\theta$.

> [!question] L3a-D1x · [Extension] Calculation
> At what angle does an analyzer pass exactly one quarter of the polarized light reaching it?

> [!success]- Extension answer
> $\cos^2\theta = \frac14$, so $\cos\theta = \frac12$ and θ = **60°**.

## Polarizer and analyzer
> [!question] L3a-Q7 · Calculation (L3a slides 13 to 14, L3a-Ex5 and L3a-Ex6 with new numbers)
> Unpolarized light of average intensity 2.0 W/m² passes a polarizer and then an analyzer whose axis is at 30° to the polarizer's. (a) What intensity reaches the photocell? (b) What angle between the axes would make the final intensity one-eighth of the unpolarized intensity?

*Think first: write down which factor applies at each sheet.*

> [!tip]- Hint 1
> Two different rules apply: one for unpolarized light at the first sheet, Malus's law at the second.

> [!tip]- Hint 2
> After the polarizer the intensity is 2.0/2 = 1.0 W/m². For (b), set $\frac12\cos^2\theta = \frac18$ and solve for $\cos^2\theta$ first.

> [!success]- Answer
> (a) Polarizer: $I_1 = 2.0/2 = 1.0$ W/m². Analyzer, by Malus's law: $I_2 = 1.0\cos^2 30^\circ = 1.0 \times 0.75 = 0.75$ W/m².
> (b) $\frac12\cos^2\theta = \frac18$, so $\cos^2\theta = \frac14$. Take the square root before the inverse cosine: $\cos\theta = \frac12$, θ = **60°**.
>
> Slide checks: L3a-Ex5 gives $\frac12\cos^2 45^\circ = 0.25$ W/m². L3a-Ex6 gives $\cos^2\theta = \frac15$, so $\cos\theta = 1/\sqrt5$ and θ = 63.4°.
>
> ![[L3a-malus-curve.png]]
> *Figure: Malus's law $I/I_0 = \cos^2\theta$ for light that is already polarized (L3a slides 11 to 14). Marked: 30° (0.75), 45° (0.50), 60° (0.25), 63.4° (0.20, from L3a-Ex6), 90° (0).*

> [!note]- Why it works
> Unpolarized light loses half at the first sheet whatever its orientation. After that the light is polarized along the first axis, so only the angle between the two axes matters. Undoing $\cos^2$ needs a square root first: $\cos^{-1}(1/5)$ would give 78.5° instead of 63.4°.

> [!question] L3a-Q7x · [Extension] Calculation
> In L3a-Ex6 the analyzer sits at 63.4°, letting through one-tenth of the unpolarized intensity. You slide a third polarizer between them at half that angle, 31.7° from the first. What fraction of the unpolarized intensity reaches the photocell now?

> [!success]- Extension answer
> Two steps of 31.7° each: $\frac12\cos^2 31.7^\circ\cos^2 31.7^\circ = \frac12(0.7236)^2 = 0.262$. Adding a sheet raises the output from 10% to 26%.

## Stacks of polarizers
> [!question] L3a-Q8 · Calculation (L3a slide 15, L3a-Ex7 with new numbers; same skills as Assignment 1, Q2 and Tutorial 2, Q3)
> Unpolarized light of intensity $I_b$ passes three polarizers: the first vertical, the second at 20° and the third at 70°, both measured from the first. (a) Find the intensity after each polarizer. (b) Find the final intensity if the middle polarizer is removed.

*Think first: list the angle that matters at each sheet before opening Hint 1.*

> [!tip]- Hint 1
> The first sheet halves unpolarized light; after that, apply Malus's law between **consecutive** sheets.

> [!tip]- Hint 2
> The angle between the second and third axes is 70° − 20°, not 70°.

> [!success]- Answer
> (a)
> - After sheet 1: $I_1 = I_b/2 = 0.500\,I_b$
> - After sheet 2 (20° from sheet 1): $I_2 = 0.500\,I_b\cos^2 20^\circ = 0.442\,I_b$
> - After sheet 3 (50° from sheet 2): $I_3 = 0.442\,I_b\cos^2 50^\circ = 0.182\,I_b$
>
> (b) Without the middle sheet, sheets 1 and 3 are 70° apart: $I = 0.500\,I_b\cos^2 70^\circ = 0.0585\,I_b$. Removing the middle sheet cuts the output to about a third.
>
> ```mermaid
> flowchart LR
>   A["unpolarized: I_b"] -->|"sheet 1: x 1/2"| B["0.500 I_b"]
>   B -->|"sheet 2: x cos² 20°"| C["0.442 I_b"]
>   C -->|"sheet 3: x cos² 50°"| D["0.182 I_b"]
> ```
>
> Slide check: L3a-Ex7 (axes at 30° and 75°) gives $\frac12\cos^2 30^\circ = \frac38 I_b$, then $\frac38 I_b\cos^2 45^\circ = \frac{3}{16}I_b$. The slide's final answer is right; its middle step is not (see Errata).

> [!note]- Why it works
> Each sheet only sees the polarization left by the sheet before it, so the angles that matter are the differences between neighbours. A middle sheet at an in-between angle passes part of the light and re-polarizes it closer to the last sheet's axis.

> [!question] L3a-Q8x · [Extension] Calculation
> Two polarizers are crossed (0° and 90°), so nothing gets through. Compare adding one middle sheet at 45° with adding two middle sheets at 30° and 60°. What fraction of the unpolarized light gets through in each case?

> [!success]- Extension answer
> One middle sheet: $\frac12\cos^2 45^\circ\cos^2 45^\circ = \frac18 = 0.125$. Two middle sheets, three 30° steps: $\frac12(\cos^2 30^\circ)^3 = \frac12(0.75)^3 = 0.211$. More, smaller steps lose less light.

## Light reflected from glass
> [!question] L3a-Q9 · Prediction (L3a slides 16 to 17)
> Unpolarized light reflects from a glass surface. As you change the angle of incidence, how does the polarization of the reflected beam change? At one special angle, what is the angle between the reflected and refracted rays?
>
> ![[L3a-s16-reflection.png]]
> *Figure (L3a slide 16): dots are field oscillations parallel to the surface (perpendicular to the page); arrows are oscillations perpendicular to those, in the page.*

*Think first: predict both parts before opening the hint.*

> [!tip]- Hint
> Treat the two vibration directions drawn on slide 16 (dots across the page, arrows in the page) separately. At one angle of incidence, one of them is missing from the reflected beam. Stuck? Read [[Brewster's angle]] first.

> [!success]- Answer
> At most angles the reflected and refracted beams are both **partially** polarized. At one angle, the **polarizing angle** $\theta_p$, the reflected beam is **completely** polarized, vibrating perpendicular to the plane of incidence (so parallel to the surface), while the refracted beam is still only partly polarized. At that angle the reflected and refracted rays are exactly **90°** apart (L3a slide 17). The plane of incidence is the plane containing the incident ray and the normal.
>
> ![[L3a-s17-brewster.png]]
> *Figure (L3a slide 17): at the polarizing angle the reflected light is 100% polarized perpendicular to the plane of incidence, and the transmitted light is partly polarized.*

> [!note]- Why it works
> The 90° condition is what pins down $\theta_p$: combined with Snell's law, it makes $\theta_p$ depend only on the two indices. The next section derives that relation.

> [!question] L3a-Q9x · [Extension] Explanation
> Glare from a calm lake is light reflected near the polarizing angle. Using the polarization of the reflected beam, explain why sunglasses with a polarizing filter cut the glare, and which way the filter's axis must point.

> [!success]- Extension answer
> The plane of incidence is vertical, so the reflected glare vibrates perpendicular to it: horizontally, parallel to the lake. A filter with a **vertical** transmission axis is crossed with that light and blocks most of it.

## Deriving Brewster's law
> [!question] L3a-D2 · Derivation (L3a slide 18)
> Light goes from a medium of index $n_1$ into one of index $n_2$. Using the geometric condition you found in L3a-Q9 for the polarizing angle, together with Snell's law, find $\theta_p$ in terms of $n_1$ and $n_2$.

*Think first: sketch the incident, reflected and refracted rays at the polarizing angle.*

> [!tip]- Hint
> Use the geometric condition to write the refraction angle in terms of $\theta_p$, then substitute into Snell's law.

> [!question] Step 1
> The reflected ray leaves at $\theta_p$ from the normal. Write the refraction angle $\theta_r$ in terms of $\theta_p$.

> [!success]- Step 1 result
> The reflected and refracted rays are perpendicular. Going from one side of the normal to the other: $\theta_p + 90^\circ + \theta_r = 180^\circ$, so $\theta_r = 90^\circ - \theta_p$.

> [!question] Step 2
> Substitute that into Snell's law.

> [!success]- Step 2 result
> $n_1\sin\theta_p = n_2\sin(90^\circ - \theta_p) = n_2\cos\theta_p$

> [!question] Step 3
> Rearrange for $\theta_p$.

> [!success]- Step 3 result
> $\tan\theta_p = \dfrac{n_2}{n_1}$. From air ($n_1 = 1$): $\tan\theta_p = n$.

> [!success]- Full derivation
> 1. Perpendicular reflected and refracted rays: $\theta_r = 90^\circ - \theta_p$.
> 2. Snell's law: $n_1\sin\theta_p = n_2\sin\theta_r = n_2\cos\theta_p$.
> 3. Divide by $n_1\cos\theta_p$: $\tan\theta_p = n_2/n_1$, **Brewster's law**. From air, $\tan\theta_p = n$, the index of the reflecting material. $\theta_p$ is also called **Brewster's angle**.

> [!note]- Why it works
> The geometry gives one equation (the rays are perpendicular) and Snell's law gives another, so a single angle satisfies both. The result depends only on the ratio $n_2/n_1$, so it works from any medium, including from inside the glass.

> [!question] L3a-D2x · [Extension] Calculation
> Light inside glass (n = 1.50) meets the glass-air surface from inside. Find the polarizing angle. Is it below the critical angle, so that a refracted ray exists there?

> [!success]- Extension answer
> $\tan\theta_p = 1.00/1.50$, so $\theta_p = 33.7^\circ$. The critical angle is $\sin^{-1}(1/1.50) = 41.8^\circ$, so yes: at 33.7° light still refracts out, and the reflected part is completely polarized.

## Mixed set
No hints. Six questions across L3a.

> [!question] L3a-M1 · Calculation (Tutorial 2, Q5, new numbers)
> Unpolarized light in air strikes a flat glass surface at 56.0°, and the reflected beam is completely linearly polarized. Find the glass's index and the angle of refraction.

> [!success]- Answer
> n = tan 56.0° = **1.48**; θr = 90.0° − 56.0° = **34.0°**.

> [!question] L3a-M2 · Calculation (Assignment 1, Q3, new numbers)
> A glass has n = 1.60. For what angle of incidence is light reflected from it completely polarized when the glass is (a) in air, (b) in water (n = 1.33)?

> [!success]- Answer
> (a) tan⁻¹(1.60) = **58.0°**. (b) tan⁻¹(1.60/1.33) = tan⁻¹(1.203) = **50.3°**.

> [!question] L3a-M3 · Calculation (Tutorial 2, Q1, new numbers)
> Unpolarized light of intensity I₀ passes two filters. The first has its axis 25° from the vertical; the second is horizontal. Find the intensity after the second filter.

> [!success]- Answer
> The axes are 90° − 25° = 65° apart. I = (I₀/2) cos² 65° = **0.0893 I₀**.

> [!question] L3a-M4 · Calculation (Tutorial 2, Q4, new numbers)
> A polarizer's axis starts along z and is rotated by α = 50° in the y-z plane. Light of 6.0 W/m² arrives travelling along x. Find the transmitted intensity if the light is (a) unpolarized, (b) polarized along z, (c) polarized along y.

> [!success]- Answer
> (a) 3.0 W/m², for any α. (b) 6.0 cos² 50° = **2.5 W/m²**. (c) The axis is now 90° − 50° = 40° from y: 6.0 cos² 40° = **3.5 W/m²**.

> [!question] L3a-M5 · Explanation (L3a slide 6)
> Why is "longer wavelength means more photon energy" wrong?

> [!success]- Answer
> E = hf and f = c/λ, so E = hc/λ: a longer wavelength means a lower frequency and less energy per photon.

> [!question] L3a-M6 · Calculation (L3a slide 3)
> Looking straight down, a coin in water (n = 1.33) appears to be 0.75 m deep. How deep is it really?

> [!success]- Answer
> d = d′ × n₁/n₂ = 0.75 × 1.33 = **1.00 m**.

## Practice
Everything needed is here: the slide examples and the tutorial and assignment questions are written out in full, with their figures. Answer first, then open the boxes. All tutorial and assignment questions, in sheet order, are also collected in [[Tutorials and Assignment]].

### Lecture examples

#### L3a-Ex4
> [!question] L3a-Ex4 · Calculation (L3a slide 4)
> A swimmer is treading water, with her head above the water, at the surface of a pool 3.00 m deep. She sees a coin on the bottom directly below her. How deep does the coin appear to be?

*Think first: guess whether it looks deeper or shallower.*

> [!tip]- Hint
> $d' = d\,n_2/n_1$, where $n_1$ belongs to the object's medium and $n_2$ to the observer's.

> [!success]- Answer
> The coin is in water ($n_1 = 1.33$) and the swimmer's eyes are in air ($n_2 = 1.00$):
> $$d' = 3.00 \times \frac{1.00}{1.33} = 2.26\ \text{m}$$
> **The coin appears 2.26 m deep.**

#### L3a-Ex5
> [!question] L3a-Ex5 · Calculation (L3a slide 13)
> The angle between a polarizer and an analyzer, used together to reduce the intensity of light, is 45°. What is the average intensity of the polarized light reaching the photocell if the average intensity of the unpolarized light is 1 W/m²?

*Think first: write the factor each sheet applies.*

> [!tip]- Hint
> The polarizer halves unpolarized light; the analyzer then applies Malus's law.

> [!success]- Answer
> $$I_2 = \frac{I_0}{2}\cos^2 45^\circ = \frac{1}{2} \times \frac{1}{2} = 0.25\ \text{W/m}^2$$
> **0.25 W/m²** reaches the photocell.

#### L3a-Ex6
> [!question] L3a-Ex6 · Calculation (L3a slide 14)
> What value of θ, the angle between the polarizer and analyzer axes, makes the average intensity of the polarized light reaching the photocell one-tenth of the average intensity of the unpolarized light?

*Think first: set up the equation before solving it.*

> [!tip]- Hint
> Set $\frac{I_0}{2}\cos^2\theta = \frac{I_0}{10}$. Take a square root before the inverse cosine.

> [!success]- Answer
> 1. $\dfrac{I_0}{2}\cos^2\theta = \dfrac{I_0}{10}$, so $\cos^2\theta = \dfrac15$.
> 2. $\cos\theta = \sqrt{1/5} = 1/\sqrt5 = 0.447$.
> 3. **θ = 63.4°.**
>
> Using $\cos\theta = 1/5$ instead would give 78.5°, which is wrong; see [[L3a Polarization#Errata|L3a errata]].

#### L3a-Ex7
> [!question] L3a-Ex7 · Calculation (L3a slide 15)
> Unpolarized light is incident on three polarizers. The first polarizer has a vertical transmission axis, the second has a transmission axis rotated 30.0° with respect to the first, and the third has a transmission axis rotated 75.0° relative to the first. If the initial intensity of the beam is $I_b$, calculate the light intensity after the beam passes through (a) the second polarizer and (b) the third polarizer.

*Think first: list the angle that matters at each sheet.*

> [!tip]- Hint
> Halve at the first sheet, then use the angle between consecutive axes: 30.0°, then 75.0° − 30.0° = 45.0°.

> [!success]- Answer
> (a) The incident intensity at the second polarizer is $I_b/2$:
> $$I_2 = \frac{I_b}{2}\cos^2 30.0^\circ = \frac{I_b}{2}\cdot\frac34 = \frac38 I_b$$
> (b) The incident intensity at the third polarizer is $\frac38 I_b$, and its axis is 45.0° from the second's:
> $$I_3 = \frac38 I_b\cos^2 45.0^\circ = \frac38 I_b \cdot \frac12 = \frac{3}{16}I_b$$
> The slide's middle step drops the $\cos^2 45^\circ$; see [[L3a Polarization#Errata|L3a errata]].

### Tutorial and assignment questions

#### Tutorial 2, Q1
> [!question] T2-Q1 · Calculation (Tutorial 2, Q1)
> Unpolarized light with intensity $I_o$ is incident on two polarizing filters. The axis of the first filter makes an angle of 60° with the vertical, and the axis of the second filter is horizontal. What is the intensity of the light after it has passed through the second filter?

*Think first: find the angle between the two axes.*

> [!tip]- Hint
> Halve at the first filter, then use the angle between the two axes, not the angle from the vertical. Stuck? Revisit [[L3a Polarization#Polarizer and analyzer|L3a, polarizer and analyzer]].

> [!success]- Answer
> 1. First filter, unpolarized light in: $I_1 = I_o/2$.
> 2. Angle between the axes: horizontal is 90° from vertical, so $90^\circ - 60^\circ = 30^\circ$.
> 3. Malus's law: $I = \dfrac{I_o}{2}\cos^2 30^\circ = \dfrac{I_o}{2}\cdot\dfrac34 = \dfrac38 I_o$.
>
> **Answer: 3I_o/8 = 0.375 I_o.**

#### Tutorial 2, Q2
> [!question] T2-Q2 · Calculation (Tutorial 2, Q2)
> Light of intensity $I_o$ and polarized parallel to the transmission axis of a polarizer is incident on an analyzer.
> a) If the transmission axis of the analyzer makes an angle of 45° with the axis of the polarizer, what is the intensity of the transmitted light?
> b) What should the angle between the transmission axes be to make $I/I_o = 1/3$?

*Think first: decide whether a factor of ½ belongs here.*

> [!tip]- Hint
> The light is already polarized along the polarizer's axis, so there is no factor ½. For (b), take the square root before the inverse cosine. Stuck? Revisit [[L3a Polarization#Polarizer and analyzer|L3a, polarizer and analyzer]].

> [!success]- Answer
> (a) $I = I_o\cos^2 45^\circ = $ **I_o/2**.
> (b) $\cos^2\theta = \dfrac13$, so $\cos\theta = 0.577$ and **θ = 54.7°**.

#### Tutorial 2, Q3
> [!question] T2-Q3 · Calculation (Tutorial 2, Q3)
> The drawing shows four sheets of polarizing material, each with its transmission axis oriented differently. Light that is polarized in the vertical direction is incident from the left and has an average intensity of 27 W/m². Determine the average intensity of the light that emerges on the right in the drawing when sheet A alone is removed, when sheet B alone is removed, when sheet C alone is removed, and when sheet D alone is removed.
>
> ![[L3a-T2Q3-four-sheets.png]]
> *Figure: Tutorial 2, Q3. Look at which side of the vertical each tilted axis lies on.*

*Think first: write the angle between every pair of neighbouring sheets.*

> [!tip]- Hint
> The incoming light is already vertically polarized, so there is no factor ½. Read the drawing carefully: B is 30° to one side of the vertical and D is 60° to the other side. Stuck? Revisit [[L3a Polarization#Stacks of polarizers|L3a, stacks of polarizers]].

> [!success]- Answer
> Angles between the sheets' axes: A to B 30°, B to C 60°, C to D 30°, A to C 90°, and B to D 30° + 60° = 90°.
> - **A removed** (B, C, D): $27\cos^2 30^\circ = 20.25$, then $20.25\cos^2 60^\circ = 5.06$, then $5.06\cos^2 30^\circ = $ **3.8 W/m²**.
> - **B removed** (A, C, D): A passes all 27 W/m², but A and C are crossed at 90°: **0**.
> - **C removed** (A, B, D): 27 W/m² becomes 20.25 W/m² after B, but B and D are crossed at 90°: **0**.
> - **D removed** (A, B, C): 27 W/m², then 20.25 W/m², then $20.25\cos^2 60^\circ = $ **5.1 W/m²**.
>
> Check your reading of the drawing: if B and D were on the same side of the vertical, removing C would give 15.2 W/m² instead of 0.

#### Tutorial 2, Q4
> [!question] T2-Q4 · Calculation (Tutorial 2, Q4)
> The drawing shows light incident on a polarizer whose transmission axis is parallel to the z axis. The polarizer is rotated clockwise through an angle α. The average intensity of the incident light is 7.0 W/m². Determine the average intensity of the transmitted light for each of the six cases shown in the table.
>
> ![[L3a-T2Q4-table.png]]
> *Figure: Tutorial 2, Q4, the table to fill in and the setup.*

*Think first: decide for each row whether the factor ½ or Malus's law applies.*

> [!tip]- Hint
> Unpolarized light always loses half. For polarized light, use the angle between its polarization and the rotated axis; the y axis is 90° from the z axis. Stuck? Revisit [[L3a Polarization#Unpolarized light meets a polarizer|L3a, unpolarized light]].

> [!success]- Answer
> | Incident light | α = 0° | α = 35° |
> |---|---|---|
> | (a) unpolarized | 3.5 W/m² | 3.5 W/m² |
> | (b) polarized along z | 7.0 W/m² | $7.0\cos^2 35^\circ = 4.7$ W/m² |
> | (c) polarized along y | 0 (axis at 90° to y) | $7.0\cos^2 55^\circ = 2.3$ W/m² |
>
> In (c), turning the axis 35° away from z leaves it 90° − 35° = 55° from y.

#### Tutorial 2, Q5
> [!question] T2-Q5 · Calculation (Tutorial 2, Q5)
> A parallel beam of unpolarized light in air is incident at an angle of 54.5° (with respect to the normal) on a plane glass surface. The reflected beam is completely linearly polarized.
> a) What is the refractive index of the glass?
> b) What is the angle of refraction of the transmitted beam?

*Think first: name the special angle this describes.*

> [!tip]- Hint
> Completely polarized reflected light means the angle of incidence is the polarizing (Brewster) angle. Stuck? Revisit [[L3a Polarization#Light reflected from glass|L3a, polarization by reflection]].

> [!success]- Answer
> (a) From air, $\tan\theta_p = n$: $n = \tan 54.5^\circ = $ **1.40**.
> (b) At the polarizing angle the reflected and refracted rays are perpendicular: $\theta_r = 90^\circ - 54.5^\circ = $ **35.5°**.
>
> Check with Snell's law: $\sin 54.5^\circ = 0.814$, and $1.40\sin 35.5^\circ = 0.814$.

#### Assignment 1, Q2
> [!question] A1-Q2 · Calculation (Assignment 1, Q2)
> Three polarizing filters are stacked, with the polarizing axes of the second and third filters at 23.0° and 62.0°, respectively, to that of the first. If unpolarized light is incident on the stack, the light has intensity 55.0 W/cm² after it passes through the stack. If the incident intensity is kept constant but the second polarizer is removed, what is the intensity of the light after it has passed through the stack?

*Think first: decide whether you need the incident intensity.*

> [!tip]- Hint
> You don't need the incident intensity. Write the chain with and without the middle filter, then divide one by the other. Use angles between consecutive axes: 62.0° − 23.0° = 39.0°. Stuck? Revisit [[L3a Polarization#Stacks of polarizers|L3a, stacks of polarizers]].

> [!success]- Answer
> 1. With all three filters: $\dfrac{I_0}{2}\cos^2 23.0^\circ\cos^2 39.0^\circ = 55.0$ W/cm².
> 2. Without the second filter: $I' = \dfrac{I_0}{2}\cos^2 62.0^\circ$.
> 3. Divide: $I' = 55.0 \times \dfrac{\cos^2 62.0^\circ}{\cos^2 23.0^\circ\cos^2 39.0^\circ} = 55.0 \times \dfrac{0.2204}{0.8473 \times 0.6040} = 55.0 \times 0.4307$
>
> **Answer: I′ = 23.7 W/cm².** The incident intensity works out to $I_0 = 215$ W/cm², though the question doesn't ask for it.

#### Assignment 1, Q3
> [!question] A1-Q3 · Calculation (Assignment 1, Q3)
> The refractive index of a certain glass is 1.66. For what incident angle is light reflected from the surface of this glass completely polarized if the glass is immersed in (a) air and (b) water (n = 1.33)?

*Think first: decide which index goes on the bottom of the ratio.*

> [!tip]- Hint
> $\tan\theta_p = n_2/n_1$, where $n_1$ is the medium the light comes from. Stuck? Revisit [[L3a Polarization#Deriving Brewster's law|L3a, Brewster's law]].

> [!success]- Answer
> (a) In air: $\theta_p = \tan^{-1}(1.66) = $ **58.9°**.
> (b) In water: $\theta_p = \tan^{-1}\left(\dfrac{1.66}{1.33}\right) = \tan^{-1}(1.248) = $ **51.3°**.

## Errata
> [!bug]- Slide 6, electromagnetic spectrum
> The second arrow line says that as λ increases, f decreases and energy increases. Energy **decreases**: $E = hf = hc/\lambda$ (L1 slide 7). For example, a 400 nm photon carries $4.97\times10^{-19}$ J and a 700 nm photon $2.84\times10^{-19}$ J.

> [!bug]- Slide 15, L3a-Ex7 middle step
> The slide writes $I_3 = \frac38 I_b\cos^2 45^\circ = \frac{I_b}{2}\cos^2 30^\circ = \frac{3}{16}I_b$. The middle expression, $\frac{I_b}{2}\cos^2 30^\circ$, equals $\frac38 I_b$: that is the intensity entering the third polarizer, not the answer. It is missing the factor $\cos^2 45^\circ = \frac12$. Correct chain: $I_3 = \frac38 I_b\cos^2 45^\circ = \frac{I_b}{2}\cos^2 30^\circ\cos^2 45^\circ = \frac{3}{16}I_b$. The final answer is right.

> [!bug]- Slide 14, L3a-Ex6
> Use $\cos\theta = 1/\sqrt5 = 0.447$, which gives θ = 63.4°. Taking $\cos\theta = 1/5$ gives 78.5°, which is wrong. The slide as displayed shows $\sqrt{1/5}$, which is correct; the PDF's hidden text layer drops the square root, so text copied from the PDF reads "1/5".

> [!bug]- Slide 8, statement (b)
> It says a polarized wave passes easily through a slit perpendicular to its direction of polarization. It **cannot** pass; the slide's own figure (b) shows the wave blocked.

> [!bug]- Slide 8, rope figure labels
> The rope vibrating up and down is labelled "Horizontally polarized", and the side-to-side rope "Vertically polarized". The labels are swapped: polarization is named after the direction of vibration, as the slide's text says.

> [!bug]- Slide 5, speed of light
> It says light in any medium is slower than its speed "in air, c". The constant c is the speed in vacuum; air itself has n = 1.000293 (textbook p. 907). Calculations still use n = 1 for air.

> [!bug]- Slide 18, spelling
> "Brewester law" should read Brewster's law.

> [!bug]- Notation across slides 10 to 15
> $I_0$ means the intensity of light that is already polarized on slides 10 to 12, but the intensity of the unpolarized beam in L3a-Ex5 to L3a-Ex7. Read each problem to see which one it means.

## Self-check
Timed run: about 5 minutes, no notes.

> [!question] L3a-S1 · Calculation (L3a slide 13)
> Unpolarized light of 1.6 W/m² passes a polarizer and then an analyzer at 60°. Find the final intensity.

> [!success]- Answer
> (1.6/2) cos² 60° = 0.8 × 0.25 = **0.20 W/m²**.

> [!question] L3a-S2 · Calculation (L3a slide 18)
> Find the polarizing angle for light in air reflecting from water (n = 1.33).

> [!success]- Answer
> tan⁻¹(1.33) = **53.1°**.

> [!question] L3a-S3 · Calculation (L3a slide 3)
> A pool is 2.00 m deep. How deep does it look from directly above?

> [!success]- Answer
> 2.00/1.33 = **1.50 m**.

## Review
Spaced questions from earlier lectures.

> [!question] L3a-R1 · Calculation (from L2, slide 11)
> Find the critical angle for flint glass (n = 1.66) in air.

> [!success]- Answer
> sin⁻¹(1/1.66) = **37.0°**.

> [!question] L3a-R2 · Explanation (from L1, slide 15)
> Two mirrors meet at 90°. Why does light leave them travelling opposite to the way it came, whatever its angle of incidence?

> [!success]- Answer
> The two reflections turn the ray by (180° − 2θ) + (180° − 2(90° − θ)) = 180°, which does not depend on θ.

> [!question] L3a-R3 · Calculation (from L2, slide 6)
> Light in air meets crown glass (n = 1.52) at 60.0°. Find the angle of refraction.

> [!success]- Answer
> sin θ₂ = sin 60.0°/1.52 = 0.570, so θ₂ = **34.7°**.

> [!question] L3a-R4 · Comparison (from L1, slide 7)
> Compare the photon energies of ultraviolet light at 1.0 × 10¹⁵ Hz and red light at 4.0 × 10¹⁴ Hz.

> [!success]- Answer
> E ∝ f, so the ultraviolet photon carries (1.0 × 10¹⁵)/(4.0 × 10¹⁴) = **2.5 times** as much energy.
