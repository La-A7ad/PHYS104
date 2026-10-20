---
tags: [PHYS104, quiz-prep]
---
# PHYS 104 Drills: Ch. 35 Light and Ray Optics

Formulas and methods: [[Cheat Sheet]]. Timed practice: [[Mock Quiz]].
Topics follow the [[Cheat Sheet#Quiz weight ranking|quiz weight ranking]]. Each question names the source it mirrors (codes as in the [[Cheat Sheet]] header: L3-Pol = polarization file, L3-Disp = dispersion file). Work it first, then open the answer. All answers use $c = 3.00\times10^8$ m/s and $n_{air} = 1.00$, as the slides do.

## 1 Snell's law
Method: [[Cheat Sheet#Method per topic|Method 1]].

**1.1** *(mirrors L2 Ex 2, s.9)* A beam of light of wavelength 600 nm traveling in air is incident on a slab of transparent material. The incident beam makes an angle of 35.0° with the normal, and the refracted beam makes an angle of 22.0° with the normal. Find the index of refraction of the material.

> [!question]- Answer 1.1
> **Key step:** $n_1 = 1$, so $n_2 = \dfrac{\sin 35.0^\circ}{\sin 22.0^\circ} = \dfrac{0.5736}{0.3746}$.
> **Answer:** $n = 1.53$. The wavelength is extra information.

**1.2** *(mirrors S1 Q4)* A light beam passes through three parallel slabs, $n = 1.50$ (top), $n = 1.33$, $n = 1.20$, and then into air ($n = 1.00$) below. (a) If the angle of incidence in the top slab is $\theta_1 = 25.0^\circ$, what is the angle $\theta_2$ of the emerging beam? (b) What must $\theta_1$ be to have total internal reflection at the surface between the $n = 1.20$ slab and the air?

> [!question]- Answer 1.2
> **Key step:** Snell at every parallel boundary gives $1.50\sin\theta_1 = 1.33\sin\theta_a = 1.20\sin\theta_b = 1.00\sin\theta_2$, so the middle slabs drop out.
> **(a)** $\sin\theta_2 = 1.50\sin 25.0^\circ = 0.634$, so $\theta_2 = 39.3^\circ$.
> **(b)** TIR at the last surface needs $1.20\sin\theta_b \ge 1.00$, that is $1.50\sin\theta_1 \ge 1.00$: $\theta_1 \ge 41.8^\circ$. No earlier boundary reflects first: TIR there would need $\theta_1 \ge 62.5^\circ$ (1.50 to 1.33) or $\theta_1 \ge 53.1^\circ$ (1.33 to 1.20).

**1.3** *(mirrors L2 s.4, deviation angle)* A ray of light in air strikes a calm water surface ($n = 1.33$) at 45.0° to the normal. Find the angle of refraction and the angle of deviation $\beta$.

> [!question]- Answer 1.3
> **Key step:** $\sin\theta_2 = \dfrac{\sin 45.0^\circ}{1.33} = 0.532$, so $\theta_2 = 32.1^\circ$.
> **Answer:** $\beta = \lvert\theta_1 - \theta_2\rvert = 45.0^\circ - 32.1^\circ = 12.9^\circ$.

**1.4** *(mirrors L2 s.5 figure b and S1 Q5a)* Light travels from glass ($n = 1.52$) into water ($n = 1.33$), meeting the boundary at 30.0°. Find the angle of refraction. Does the ray bend toward or away from the normal, and why?

> [!question]- Answer 1.4
> **Key step:** $\sin\theta_2 = \dfrac{1.52\sin 30.0^\circ}{1.33} = 0.571$, so $\theta_2 = 34.8^\circ$.
> **Answer:** 34.8° > 30.0°, so it bends **away** from the normal: light speeds up when it enters the lower-index medium ($v = c/n$).

## 2 Malus's law
Method: [[Cheat Sheet#Method per topic|Method 2]].

**2.1** *(mirrors S2 Q1)* Unpolarized light with intensity $I_o$ is incident on two polarizing filters. The axis of the first filter makes an angle of 40° with the vertical, and the axis of the second filter is horizontal. What is the intensity of the light after it has passed through the second filter?

> [!question]- Answer 2.1
> **Key step:** the angle between the two axes is $90^\circ - 40^\circ = 50^\circ$ (not 40°).
> **Answer:** $I = \dfrac{I_o}{2}\cos^2 50^\circ = 0.5 \times 0.413\,I_o = 0.207\,I_o$.

**2.2** *(mirrors S2 Q2 and L3-Pol Ex 6)* Light of intensity $I_o$, polarized parallel to the transmission axis of a polarizer, is incident on an analyzer. (a) If the analyzer's axis makes 60° with the polarizer's axis, what is the transmitted intensity? (b) What angle between the axes gives $I/I_o = 2/3$? (c) If unpolarized light of intensity $I_o$ enters the same polarizer-analyzer pair instead, what angle makes the final intensity $I_o/8$?

> [!question]- Answer 2.2
> **Key step:** in (a) and (b) the light is already polarized, so there is no factor ½. In (c) it is unpolarized, so halve first.
> **(a)** $I = I_o\cos^2 60^\circ = 0.250\,I_o$.
> **(b)** $\cos^2\theta = 2/3$, $\cos\theta = 0.816$, $\theta = 35.3^\circ$.
> **(c)** $\frac{I_o}{2}\cos^2\theta = \frac{I_o}{8}$, so $\cos^2\theta = \frac14$, $\cos\theta = \frac12$, $\theta = 60.0^\circ$.

**2.3** *(mirrors A1 Q2 and L3-Pol Ex 7)* Three polarizing filters are stacked, with the polarizing axes of the second and third filters at 20.0° and 65.0°, respectively, to that of the first. If unpolarized light is incident on the stack, the light has intensity 40.0 W/m² after it passes through the stack. If the incident intensity is kept constant but the second polarizer is removed, what is the intensity of the light after it has passed through the stack?

> [!question]- Answer 2.3
> **Key step:** use angles between consecutive axes: 20.0°, then $65.0^\circ - 20.0^\circ = 45.0^\circ$. So $40.0 = \frac{I_0}{2}\cos^2 20.0^\circ\cos^2 45.0^\circ$, giving $\frac{I_0}{2} = \frac{40.0}{0.8830 \times 0.500} = 90.6$ W/m².
> **Answer:** without the second filter, $I = 90.6\cos^2 65.0^\circ = 90.6 \times 0.1786 = 16.2$ W/m².

**2.4** *(mirrors S2 Q3)* Four polarizing sheets are lined up: A has a vertical axis, B is rotated 45° counterclockwise from vertical, C is horizontal, and D is rotated 30° clockwise from vertical. Light polarized in the vertical direction, with average intensity 20 W/m², enters from the A side. Find the emerging intensity when sheet A alone is removed, when B alone is removed, when C alone is removed, and when D alone is removed.

> [!question]- Answer 2.4
> **Key step:** the incoming light is already polarized, so no ½. B and D lie on opposite sides of vertical, so they are $45^\circ + 30^\circ = 75^\circ$ apart.
> **A removed** (B, C, D): $20\cos^2 45^\circ = 10$, then B to C is 45°: 5.0, then C to D is 60°: $5.0 \times 0.25 = 1.25$ W/m².
> **B removed** (A, C, D): A to C is 90°, so **0**.
> **C removed** (A, B, D): $20 \to 10$, then B to D is 75°: $10\cos^2 75^\circ = 0.67$ W/m².
> **D removed** (A, B, C): $20 \to 10 \to 5.0$ W/m².

## 3 Total internal reflection
Method: [[Cheat Sheet#Method per topic|Method 3]].

**3.1** *(mirrors S1 Q5)* The critical angle for total internal reflection at a liquid-air interface is 48.0°. (a) If a ray of light traveling in the liquid has an angle of incidence at the interface of 30.0°, what angle does the refracted ray in the air make with the normal? (b) If a ray of light traveling in air has an angle of incidence of 30.0°, what angle does the refracted ray in the liquid make with the normal?

> [!question]- Answer 3.1
> **Key step:** get $n$ first: $n = \dfrac{1}{\sin 48.0^\circ} = 1.346$.
> **(a)** $\sin\theta = 1.346\sin 30.0^\circ = 0.673$, $\theta = 42.3^\circ$ (30.0° is below $\theta_c$, so the ray does exit).
> **(b)** $\sin\theta = \dfrac{\sin 30.0^\circ}{1.346} = 0.372$, $\theta = 21.8^\circ$. No TIR question arises: air to liquid is low to high $n$.

**3.2** *(mirrors L2 Ex 3)* A beam of light is propagating through flint glass ($n_1 = 1.66$) and strikes a glass-air interface at an angle of incidence of 40.0°. (a) Will part of the beam enter the air, or will it be totally reflected? (b) Repeat part (a) with the glass surrounded by water ($n_2 = 1.33$).

> [!question]- Answer 3.2
> **Key step:** compare 40.0° with $\theta_c = \sin^{-1}(n_2/n_1)$.
> **(a)** $\theta_c = \sin^{-1}(1/1.66) = 37.0^\circ$. Since $40.0^\circ > 37.0^\circ$, the beam is totally reflected.
> **(b)** $\theta_c = \sin^{-1}(1.33/1.66) = 53.2^\circ$. Since $40.0^\circ < 53.2^\circ$, part refracts into the water (at $\sin^{-1}\frac{1.66\sin 40.0^\circ}{1.33} = 53.3^\circ$) and part reflects.

**3.3** *(mirrors S1 Q6)* A glass prism in air has two faces, surface 1 and surface 2, that meet at 70.0°. A beam enters surface 1 at angle $\theta_1$ and crosses to surface 2 (the same path shape as in the S1 Q6 figure), where it strikes at exactly the critical angle, 40.0°. Determine $\theta_1$.

> [!question]- Answer 3.3
> **Key step:** inside the prism $r_1 + r_2 = A$ (L3-Disp s.7), so $r_1 = 70.0^\circ - 40.0^\circ = 30.0^\circ$; and $n = 1/\sin 40.0^\circ = 1.556$.
> **Answer:** $\sin\theta_1 = 1.556\sin 30.0^\circ = 0.778$, so $\theta_1 = 51.1^\circ$.

**3.4** *(mirrors A1 Q1; use the A1 Q1 figure)* A light ray is incident normal to the vertical face of the same 30°-60°-90° prism, but now the prism has $n_1 = 1.60$ and is immersed in water ($n_2 = 1.33$). (a) Determine the exit angle $\theta_3$. (b) A substance is dissolved in the water to increase $n_2$. At what value of $n_2$ does total internal reflection cease at point P?

> [!question]- Answer 3.4
> **Key step:** normal entry means no bending, so the angle of incidence at P equals the 60.0° prism angle. $\theta_c = \sin^{-1}(1.33/1.60) = 56.2^\circ < 60.0^\circ$, so TIR at P.
> **(a)** The reflected ray meets the bottom face at $\theta_2 = 30.0^\circ$: $1.60\sin 30.0^\circ = 1.33\sin\theta_3$, so $\sin\theta_3 = 0.602$ and $\theta_3 = 37.0^\circ$.
> **(b)** TIR stops when $\theta_c$ reaches 60.0°: $n_2 = 1.60\sin 60.0^\circ = 1.39$.

## 4 Brewster angle
Method: [[Cheat Sheet#Method per topic|Method 4]].

**4.1** *(mirrors S2 Q5)* A parallel beam of unpolarized light in air is incident at an angle of 58.0° (with respect to the normal) on a plane glass surface. The reflected beam is completely linearly polarized. (a) What is the refractive index of the glass? (b) What is the angle of refraction of the transmitted beam?

> [!question]- Answer 4.1
> **Key step:** completely polarized reflection means $\theta_p = 58.0^\circ$, and from air $\tan\theta_p = n$.
> **(a)** $n = \tan 58.0^\circ = 1.60$.
> **(b)** $\theta_r = 90.0^\circ - 58.0^\circ = 32.0^\circ$.

**4.2** *(mirrors A1 Q3)* The refractive index of a certain glass is 1.52. For what incident angle is light reflected from the surface of this glass completely polarized if the glass is immersed in (a) air and (b) water ($n = 1.33$)?

> [!question]- Answer 4.2
> **Key step:** $\tan\theta_p = n_2/n_1$ with $n_1$ = the medium the light comes from.
> **(a)** $\theta_p = \tan^{-1}(1.52) = 56.7^\circ$.
> **(b)** $\theta_p = \tan^{-1}(1.52/1.33) = \tan^{-1}(1.143) = 48.8^\circ$.

**4.3** *(mirrors S1 Q3)* A beam of light both reflects and refracts at the surface between air and glass. If the refractive index of the glass is $n_g$, find the angle of incidence $\theta_1$ that makes the reflected ray and the refracted ray perpendicular to each other. Evaluate it for $n_g = 1.50$.

> [!question]- Answer 4.3
> **Key step:** the reflected ray is at $\theta_1$ from the normal, so perpendicular rays need $\theta_1 + 90^\circ + \theta_2 = 180^\circ$, that is $\theta_2 = 90^\circ - \theta_1$. Snell: $\sin\theta_1 = n_g\sin(90^\circ - \theta_1) = n_g\cos\theta_1$.
> **Answer:** $\tan\theta_1 = n_g$, which is Brewster's law (L3-Pol s.18). For $n_g = 1.50$: $\theta_1 = 56.3^\circ$.

**4.4** *(trap check on L3-Pol s.18)* Light traveling inside water ($n = 1.33$) reflects from the water-air surface. At what angle of incidence is the reflected light completely polarized?

> [!question]- Answer 4.4
> **Key step:** the light starts in water, so $n_1 = 1.33$, $n_2 = 1.00$: $\tan\theta_p = 1.00/1.33 = 0.752$.
> **Answer:** $\theta_p = 36.9^\circ$. This is below water's critical angle (48.8°), so a refracted ray exists, at $90^\circ - 36.9^\circ = 53.1^\circ$.

## 5 Prism deviation and dispersion
Method: [[Cheat Sheet#Method per topic|Method 5]].

**5.1** *(mirrors A1 Q4)* The index of refraction for violet light in a certain glass is 1.54 and that for red light is 1.51. What is the angular separation of visible light passing through an equilateral prism of apex angle 60.0° if the angle of incidence is 55.0°?

> [!question]- Answer 5.1
> **Key step:** trace each colour separately with $\sin r_1 = \sin i_1/n$, $r_2 = 60.0^\circ - r_1$, $\sin i_2 = n\sin r_2$.
> Violet: $r_1 = 32.14^\circ$, $r_2 = 27.86^\circ$, $i_2 = 46.04^\circ$.
> Red: $r_1 = 32.85^\circ$, $r_2 = 27.15^\circ$, $i_2 = 43.55^\circ$.
> **Answer:** separation $= 46.04^\circ - 43.55^\circ = 2.49^\circ$ (same as $\delta_V - \delta_R = 41.04^\circ - 38.55^\circ$).

**5.2** *(mirrors L3-Disp s.6 to 7)* A ray strikes a 60.0° glass prism ($n = 1.50$) at $i_1 = 40.0^\circ$. Find $r_1$, $r_2$, $i_2$ and the angle of deviation $\delta$.

> [!question]- Answer 5.2
> **Key step:** $\sin r_1 = \sin 40.0^\circ/1.50$, so $r_1 = 25.4^\circ$; $r_2 = 60.0^\circ - 25.4^\circ = 34.6^\circ$, below $\theta_c = 41.8^\circ$, so the ray exits.
> **Answer:** $\sin i_2 = 1.50\sin 34.6^\circ$, so $i_2 = 58.5^\circ$; $\delta = 40.0^\circ + 58.5^\circ - 60.0^\circ = 38.5^\circ$.

**5.3** *(mirrors L3-Disp s.8)* A prism has apex angle 75.0° and $n = 1.50$. (a) Can any ray pass through it? (b) Find the smallest angle of incidence that lets the ray emerge from the second face.

> [!question]- Answer 5.3
> **Key step:** $\theta_c = \sin^{-1}(1/1.50) = 41.8^\circ$, so $2\theta_c = 83.6^\circ$.
> **(a)** Yes: $A = 75.0^\circ < 83.6^\circ$. But $A > \theta_c$, so small incidence angles give TIR at face 2.
> **(b)** $\sin i_{1,min} = 1.50\sin(75.0^\circ - 41.8^\circ) = 0.821$, so $i_{1,min} = 55.2^\circ$.

## 6 Reflection and mirrors
Method: [[Cheat Sheet#Method per topic|Method 6]].

**6.1** *(mirrors S1 Q1)* Two plane mirrors intersect at right angles. A laser beam strikes the first of them at a point 9.0 cm from their point of intersection. For what angle of incidence at the first mirror will this ray strike the midpoint of the second mirror (which is 24.0 cm long) after reflecting from the first mirror?

> [!question]- Answer 6.1
> **Key step:** after reflection the ray covers 9.0 cm along the first mirror and 12.0 cm (half of 24.0) along the second. The first mirror's normal is parallel to the second mirror, so $\tan\theta = 9.0/12.0$.
> **Answer:** $\theta = 36.9^\circ$.

**6.2** *(mirrors L1 Ex 1, s.14)* Two mirrors make an angle of 110° with each other. A ray is incident on mirror M1 at 50° to the normal. Find the angle the ray makes with the normal to M2 after it is reflected from both mirrors.

> [!question]- Answer 6.2
> **Key step:** the reflected ray makes $90^\circ - 50^\circ = 40^\circ$ with M1. Triangle: $40^\circ + 110^\circ + x = 180^\circ$, so $x = 30^\circ$ with M2's surface.
> **Answer:** $90^\circ - 30^\circ = 60^\circ$ from M2's normal. Check: total turn $= (180^\circ - 100^\circ) + (180^\circ - 120^\circ) = 140^\circ = 360^\circ - 2(110^\circ)$.

**6.3** *(mirrors L1 s.15, retroreflection)* Two mirrors meet at 90°. A ray hits the first mirror at 25.0° to the normal. Find the angle it makes with the second mirror's normal, and show that it leaves parallel to its original path.

> [!question]- Answer 6.3
> **Key step:** $90^\circ - 25.0^\circ = 65.0^\circ$ from mirror 1; triangle gives $180^\circ - 65.0^\circ - 90^\circ = 25.0^\circ$ from mirror 2, so $65.0^\circ$ from its normal.
> **Answer:** 65.0°. The ray turns $180^\circ - 2(25.0^\circ) = 130^\circ$, then $180^\circ - 2(65.0^\circ) = 50^\circ$: $180^\circ$ in total, so it goes straight back.

## 7 Speed wavelength frequency
Method: [[Cheat Sheet#Method per topic|Method 7]].

**7.1** *(mirrors S1 Q2)* A beam of light has a wavelength of 589 nm in vacuum. (a) What is the speed of this light in a liquid whose index of refraction at this wavelength is 1.36? (b) What is the wavelength of these waves in the liquid? (c) What is their frequency in the liquid?

> [!question]- Answer 7.1
> **Key step:** only $v$ and $\lambda$ change; $f$ is set by the source.
> **(a)** $v = c/n = 3.00\times10^8/1.36 = 2.21\times10^8$ m/s.
> **(b)** $\lambda_n = 589/1.36 = 433$ nm.
> **(c)** $f = c/\lambda_0 = 3.00\times10^8/(589\times10^{-9}) = 5.09\times10^{14}$ Hz, the same as in vacuum.

**7.2** *(mirrors L2 s.8)* Light with a wavelength of 480 nm in water ($n = 1.33$) passes into glass ($n = 1.50$). What is its wavelength in the glass?

> [!question]- Answer 7.2
> **Key step:** $n_1\lambda_1 = n_2\lambda_2$ (both equal the vacuum wavelength, here 638 nm).
> **Answer:** $\lambda_2 = 480 \times 1.33/1.50 = 426$ nm.

## 8 Minimum deviation and dispersive power
Method: [[Cheat Sheet#Method per topic|Method 8]].

**8.1** *(mirrors L3-Disp Ex 1, s.15)* A prism of apex angle 60° gives $\delta_{min} = 40.0^\circ$. Find $n$.

> [!question]- Answer 8.1
> **Key step:** $n = \dfrac{\sin\frac{60^\circ + 40.0^\circ}{2}}{\sin 30^\circ} = \dfrac{\sin 50.0^\circ}{0.500}$.
> **Answer:** $n = 0.766/0.500 = 1.53$.

**8.2** *(mirrors L3-Disp Ex 2, s.16)* A 60.0° glass prism ($n_R = 1.613$, $n_V = 1.632$, $n_Y = 1.620$) is used at minimum deviation. Find $\delta_R$, $\delta_V$, the angle of dispersion $\theta$, $\omega$ and $V$. Is this low or high dispersion glass?

> [!question]- Answer 8.2
> **Key step:** $\sin\frac{60^\circ + \delta}{2} = n\sin 30^\circ = n/2$ for each colour.
> Red: $\sin^{-1}(0.8065) = 53.76^\circ$, so $\delta_R = 47.51^\circ$. Violet: $\sin^{-1}(0.8160) = 54.69^\circ$, so $\delta_V = 49.37^\circ$.
> $\theta = 49.37^\circ - 47.51^\circ = 1.86^\circ$. $\omega = \dfrac{1.632 - 1.613}{1.620 - 1} = 0.0306$, $V = 1/\omega = 32.6$.
> **Answer:** $V < 50$, so high dispersion (flint-type glass).

**8.3** *(mirrors L3-Disp s.11 and s.13 to 14)* A thin prism of apex angle 6.0° is made of glass with $n_V = 1.5230$, $n_R = 1.5140$, $n_Y = 1.5170$. Find the deviation of yellow light, the angular dispersion, $\omega$ and $V$.

> [!question]- Answer 8.3
> **Key step:** thin prism, so $\delta = (n - 1)A$ for every colour.
> $\delta_Y = 0.5170 \times 6.0^\circ = 3.10^\circ$; $\theta = (1.5230 - 1.5140)(6.0^\circ) = 0.054^\circ$.
> **Answer:** $\omega = 0.0090/0.5170 = 0.0174$, $V = 57.4 > 50$: low dispersion (crown-type). Note $\omega$ does not depend on $A$.

## 9 Apparent depth
Method: [[Cheat Sheet#Method per topic|Method 9]].

**9.1** *(mirrors L3-Pol Ex 4)* A swimmer treading water looks straight down at a coin on the bottom of a pool 2.50 m deep ($n = 1.33$). How deep does the coin appear to be?

> [!question]- Answer 9.1
> **Key step:** object in water ($n_1 = 1.33$), observer in air ($n_2 = 1.00$).
> **Answer:** $d' = 2.50 \times \dfrac{1.00}{1.33} = 1.88$ m.

**9.2** *(reverse of L3-Pol Ex 4)* A fish looks straight up at a bird hovering 2.00 m above the water surface. How far above the surface does the bird appear to the fish?

> [!question]- Answer 9.2
> **Key step:** now the object is in air ($n_1 = 1.00$) and the observer in water ($n_2 = 1.33$).
> **Answer:** $d' = 2.00 \times \dfrac{1.33}{1.00} = 2.66$ m, so the bird looks farther away than it is.

**9.3** *(mirrors L3-Pol s.3)* A coin on the bottom of a tank of liquid 2.00 m deep appears to be 1.50 m deep when viewed from directly above. Find the liquid's index of refraction.

> [!question]- Answer 9.3
> **Key step:** $d' = d\,\dfrac{n_{air}}{n}$, so $n = \dfrac{d}{d'}$.
> **Answer:** $n = 2.00/1.50 = 1.33$.

## 10 Concept checks
One block per lecture. Answer in two or three sentences, as on a quiz.

### Lecture 1

**10.1** *(L1 s.5 to 7)* Young's 1801 experiment and the photoelectric effect support different models of light. Which model does each support, and what observation could the wave model not explain?

> [!question]- Answer 10.1
> **Key step:** Young showed light rays interfere, which particles cannot do, so light behaves as a wave. In the photoelectric effect the kinetic energy of ejected electrons does not depend on the light's intensity, which waves could not explain.
> **Answer:** Einstein's photons carry $E = hf$, so each electron's energy depends on frequency, not brightness. Light acts as a wave in some experiments and as particles in others.

**10.2** *(L1 s.7 with L3-Pol s.6)* Which carries more energy per photon, violet light (400 nm) or red light (700 nm)? Compute both energies.

> [!question]- Answer 10.2
> **Key step:** $E = hf = hc/\lambda$.
> Violet: $f = 7.50\times10^{14}$ Hz, $E = 4.97\times10^{-19}$ J. Red: $f = 4.29\times10^{14}$ Hz, $E = 2.84\times10^{-19}$ J.
> **Answer:** violet, by a factor $700/400 = 1.75$. Longer wavelength means lower photon energy.

**10.3** *(L1 s.9)* Light ($\lambda = 500$ nm) passes through a 2 mm hole, and ocean waves ($\lambda = 20$ m) pass through a 5 m gap in a sea wall. Which can be treated with the ray approximation?

> [!question]- Answer 10.3
> **Key step:** compare $\lambda$ with the opening $d$.
> **Answer:** the light: $5\times10^{-7}$ m $\ll 2\times10^{-3}$ m, so it continues in straight lines. The ocean waves have $\lambda > d$, so they spread out behind the gap like waves from a point source (diffraction), and rays do not apply.

**10.4** *(L1 s.12 to 13)* Why can you read a page from any angle, but see a lamp's reflection in a mirror only from one direction?

> [!question]- Answer 10.4
> **Answer:** a mirror is smooth, so reflection is specular: parallel rays stay parallel and leave in one direction. Paper is rough, so reflection is diffuse: rays leave in random directions and some reach your eye from anywhere.

### Lecture 2

**10.5** *(L2 s.8)* Why does the frequency of light stay the same when it passes from air into glass, while its wavelength changes?

> [!question]- Answer 10.5
> **Key step:** frequency counts wave crests per second. The crests reaching the boundary each second must equal the crests leaving it, or waves would pile up or vanish at the boundary (textbook p. 907).
> **Answer:** so $f$ is fixed by the source. In glass $v = c/n$ is smaller, so $\lambda = v/f$ must shrink by the same factor $n$.

**10.6** *(L2 s.10 to 11)* Why can total internal reflection happen when light goes from water to air, but never from air to water?

> [!question]- Answer 10.6
> **Key step:** Snell gives $\sin\theta_2 = \frac{n_1}{n_2}\sin\theta_1$.
> **Answer:** from air to water $n_1/n_2 < 1$, so $\sin\theta_2 < 1$ for every angle and a refracted ray always exists. From water to air $n_1/n_2 > 1$, so $\sin\theta_2$ reaches 1 at $\theta_c$ (here 48.8°); beyond it no refracted angle exists and all light reflects. Equivalently, $\sin\theta_c = n_2/n_1$ is only less than 1 when $n_1 > n_2$ (textbook p. 915).

**10.7** *(L2 s.20 to 21)* In the Huygens construction for refraction, which distance is $v_1\Delta t$ and which is $v_2\Delta t$? Use them to explain why light entering a slower medium bends toward the normal.

> [!question]- Answer 10.7
> **Key step:** ray 2 travels $A'C = v_1\Delta t$ in medium 1 while the wavelet from A grows to $AB = v_2\Delta t$ in medium 2. Both triangles share hypotenuse $AC$, so $\sin\theta_1 = v_1\Delta t/AC$ and $\sin\theta_2 = v_2\Delta t/AC$.
> **Answer:** if $v_2 < v_1$ then $\sin\theta_2 < \sin\theta_1$, so $\theta_2 < \theta_1$. With $v = c/n$ this becomes $n_1\sin\theta_1 = n_2\sin\theta_2$.

**10.8** *(L2 s.16)* Why must the cladding of an optical fiber have a lower index than the core?

> [!question]- Answer 10.8
> **Answer:** TIR only happens going from higher to lower $n$. Light in the core that hits the cladding beyond $\theta_c$ is totally reflected back into the core and zigzags along it. With a higher-index cladding the light would simply refract out.

### Lecture 3, polarization file (L3-Pol)

**10.9** *(L3-Pol s.6)* Put radio waves, visible light and X-rays in order of increasing frequency and photon energy. Then correct this statement: "As $\lambda$ increases, $f$ decreases and energy increases."

> [!question]- Answer 10.9
> **Answer:** radio, then visible, then X-rays, for both frequency and photon energy. Corrected: as $\lambda$ increases, $f$ decreases and photon energy decreases ($E = hc/\lambda$). See [[Cheat Sheet#Errata|Errata]] item 1.

**10.10** *(L3-Pol s.8 and s.12)* A rope vibrating up and down passes through a vertical slit. What happens at a horizontal slit, and what is the light version of this?

> [!question]- Answer 10.10
> **Answer:** the horizontal slit blocks it, because the rope's vibration is perpendicular to the slit (the slide says the opposite; see Errata item 6). For light: polarized light passes a polarizer parallel to its polarization and is blocked by one at 90°, since $I = I_0\cos^2 90^\circ = 0$.

**10.11** *(L3-Pol s.2)* On a hot day a dry road far ahead seems to have a puddle on it. Explain.

> [!question]- Answer 10.11
> **Answer:** hot air near the road has a smaller $n$ than the cooler air above, so light travels fastest near the ground and its wave fronts tilt. Light from the sky heading down at a shallow angle curves back upward and reaches your eye from below, so you see an image of the sky on the road that looks like water (textbook p. 914).

**10.12** *(L3-Pol s.16 to 18)* At the polarizing angle, what is the angle between the reflected and refracted rays, and which of the two beams is completely polarized?

> [!question]- Answer 10.12
> **Answer:** 90°, since $\theta_p + \theta_r = 90^\circ$. The reflected beam is completely polarized (perpendicular to the plane of incidence); the refracted beam is only partly polarized. Putting $\theta_r = 90^\circ - \theta_p$ into Snell gives $\tan\theta_p = n_2/n_1$.

### Lecture 3, dispersion file (L3-Disp)

**10.13** *(L3-Disp s.5)* Explain step by step why violet light is deviated more than red light by a glass prism.

> [!question]- Answer 10.13
> **Answer:** $\lambda_V < \lambda_R$, so $n_V > n_R$, so $v_V < v_R$. Violet therefore bends more at each face (smaller refraction angle inside), so $\delta_V > \delta_R$.

**10.14** *(L3-Disp s.17)* A raindrop high in the sky looks red to you, while a lower drop looks violet. Explain using the 40° and 42° angles. Which colour does the drop deviate more?

> [!question]- Answer 10.14
> **Key step:** violet leaves the drop at 40° to the incoming sunlight and red at 42°.
> **Answer:** from a high drop the 42° red ray heads down steeply enough to reach your eye, while the 40° violet ray passes over your head; a lower drop sends you its violet. Violet is deviated **more**: turned through 140° against red's 138° (textbook p. 913). The slide's wording is reversed; see [[Cheat Sheet#Errata|Errata]] item 5.

**10.15** *(L3-Disp s.10)* Why is the minimum deviation position used to measure $n$ with a spectrometer?

> [!question]- Answer 10.15
> **Answer:** $\delta$ changes very little near its minimum, so a small error in setting the angle of incidence barely changes the measured $\delta_{min}$. Then $n = \sin\frac{A+\delta_{min}}{2}\big/\sin\frac{A}{2}$ needs only $A$ and $\delta_{min}$.

**10.16** *(L3-Disp s.13 to 14)* Why does the angle of dispersion $\theta$ not describe a glass on its own, while the dispersive power $\omega$ does?

> [!question]- Answer 10.16
> **Answer:** for a thin prism $\theta = (n_V - n_R)A$ depends on the prism angle, so two prisms of the same glass give different $\theta$. In $\omega = \frac{n_V - n_R}{n_Y - 1}$ the $A$ cancels, leaving only material properties, and $V = 1/\omega$ classifies the glass (crown $V > 50$, flint $V < 50$).
