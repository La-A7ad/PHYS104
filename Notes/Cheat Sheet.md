---
tags: [PHYS104, quiz-prep]
---
# PHYS 104 Quiz Cheat Sheet: Ch. 35 Light and Ray Optics

> [!info] Key
> **L1**, **L2** = Lectures 1, 2. **L3-Pol** = file "Lecture 3" (polarization, mirage). **L3-Disp** = file "Lecture 4", also titled Lecture 3 (dispersion, rainbow). s. = slide, **S1**, **S2** = tutorials, **A1** = Assignment 1, text = textbook 10th ed. Ch. 34. Quiz rules not given; assumed calculator, no formula sheet, about 30 min [Guessing]. Practice: [[Drills]], [[Mock Quiz]].

## Quiz weight ranking
Points = how many of the 15 questions in S1, S2, A1 need the topic; ties go to more slide examples. That this predicts the quiz is assumed; L3-Disp has no sheet yet, so may be underweighted [Guessing].

1. **Snell's law** (L2) 6: S1 Q3 to Q6, A1 Q1, Q4. [[Drills#1 Snell's law|Drills]]
2. **Malus's law** (L3-Pol) 5: S2 Q1 to Q4, A1 Q2. [[Drills#2 Malus's law|Drills]]
3. **Total internal reflection** (L2) 4: S1 Q4b, Q5, Q6, A1 Q1. [[Drills#3 Total internal reflection|Drills]]
4. **Brewster angle** (L3-Pol) 3: S1 Q3, S2 Q5, A1 Q3. [[Drills#4 Brewster angle|Drills]]
5. **Prism deviation, dispersion** (L3-Disp) 2: S1 Q6, A1 Q4. [[Drills#5 Prism deviation and dispersion|Drills]]
6. **Mirrors** (L1) 1: S1 Q1, plus one slide example. [[Drills#6 Reflection and mirrors|Drills]]
7. **v, λ, f in a medium** (L2) 1: S1 Q2, no slide example. [[Drills#7 Speed wavelength frequency|Drills]]
8. **Min deviation, ω, Abbe V** (L3-Disp) 0: two slide examples. [[Drills#8 Minimum deviation and dispersive power|Drills]]
9. **Apparent depth** (L3-Pol) 0: one slide example. [[Drills#9 Apparent depth|Drills]]
10. **Concepts** (photons, ray model, Huygens, spectrum, mirage, rainbow) 0. [[Drills#10 Concept checks|Drills]]

## Formulas
Angles from the **normal**, in degrees; $n$ has no unit.

- **L1** $E = hf = hc/\lambda$: $h = 6.63\times10^{-34}$ J·s, $E$ in J, $f$ in Hz; energy per photon (s.7)
- $\theta_1' = \theta_1$: both rays and the normal in one plane; every reflection (s.10)
- Ray model valid if $\lambda \ll d$ ($d$ = opening size); otherwise diffraction (s.9)
- Two mirrors at angle $\phi$ turn a ray by $360^\circ - 2\phi$; at 90° it goes straight back (s.15, text p. 903)
- **L2** $n = c/v$, ${}_1n_2 = n_2/n_1$: $c = 3\times10^{8}$ m/s, $n_{air} = 1$, other media $n > 1$ (s.4, s.5)
- $n_1\sin\theta_1 = n_2\sin\theta_2$, or $\sin\theta_1/\sin\theta_2 = v_1/v_2$: 1 = incident side (s.3, s.6)
- $\beta = \lvert\theta_1 - \theta_2\rvert$: deviation at one surface only (s.4)
- $v = \lambda f$, $n_1/n_2 = v_2/v_1 = \lambda_2/\lambda_1$, $\lambda_m = \lambda_{air}/n_m$: $f$ never changes (s.6, s.8)
- $\sin\theta_c = n_2/n_1$: only if $n_1 > n_2$; TIR when $\theta_1 > \theta_c$ (s.11)
- Huygens: $\sin\theta_1 = v_1\Delta t/AC$, $\sin\theta_2 = v_2\Delta t/AC$, $AC$ along the surface (s.20, s.21)
- **L3-Pol** $d' = d\,n_2/n_1$: $n_1$ object side, $n_2$ viewer side; viewed from straight above (s.3)
- $I_1 = I_0/2$ (unpolarized in), then $I = I_0\cos^2\theta$, $E = E_0\cos\theta$: θ between consecutive axes, W/m² (s.9 to 11)
- $\tan\theta_p = n_2/n_1$ (air: $\tan\theta_p = n$): $n_1$ incident side; $\theta_p + \theta_r = 90^\circ$ (s.17, s.18)
- **L3-Disp** $n_V > n_B > n_G > n_Y > n_R$, $v = c/n(\lambda)$: violet slows and bends most (s.4, s.5)
- Prism in air: $\sin i_1 = n\sin r_1$, $n\sin r_2 = \sin i_2$, $r_1 + r_2 = A$, $\delta = i_1 + i_2 - A$ (s.7)
- Exits always if $A \le \theta_c$, never if $A > 2\theta_c$; between, $\sin i_{1,min} = n\sin(A - \theta_c)$ (s.8)
- Minimum deviation ($i_1 = i_2$, $r = A/2$): $n = \sin[(A+\delta_{min})/2]\,/\,\sin(A/2)$ (s.10)
- Thin prism ($A \lesssim 10^\circ$): $\delta = (n-1)A$ (s.11)
- $\theta = \delta_V - \delta_R$, $\omega = \theta/\delta_Y$, $V = 1/\omega$; thin: $\theta = (n_V - n_R)A$, $\omega = \frac{n_V - n_R}{n_Y - 1}$; $V > 50$ crown (s.13, s.14)

## Method per topic
1. **Snell**: normal first, $n_1$ = incident side; layers keep $n\sin\theta$. Check: higher $n$ bends toward normal.
2. **Malus**: ½ only if unpolarized; then $\cos^2$ per consecutive angle. Check: never rises; 90° gives 0.
3. **TIR**: is $n_1 > n_2$? Compare $\theta_1$ with $\theta_c$. Check: past $\theta_c$, no refracted ray.
4. **Brewster**: "fully polarized" or "reflected ⊥ refracted": $\tan\theta_p = n_2/n_1$. Check: $\theta_r = 90^\circ - \theta_p$.
5. **Prism**: Snell at face 1, $r_2 = A - r_1$, is $r_2 < \theta_c$?, Snell at face 2, $\delta$. Check: $\delta_V > \delta_R$.
6. **Mirrors**: normals, then triangle angles sum to 180°. Check: turn $= 360^\circ - 2\phi$.
7. **v, λ, f**: $f$ fixed; divide $v$ and $\lambda$ by $n$. Check: both shrink inside.
8. **Min deviation**: $r = A/2$, $\sin[(A+\delta)/2] = n\sin(A/2)$. Check: bigger $n$, bigger $\delta_{min}$.
9. **Apparent depth**: $d' = d\,n_{viewer}/n_{object}$. Check: seen from air, $d' < d$.

## Top traps
Order = my estimate of points at risk [Guessing].

1. **Radians mode**: every answer is in degrees.
2. **½ rule**: unpolarized input only, at sheet 1 (none in S2 Q2 to Q4). $I_0$: polarized on L3-Pol s.10 to 12, unpolarized in Ex 5 to 7.
3. **Polarizer angle**: consecutive axes (Ex 7: 45°, A1 Q2: 39°); opposite sides of vertical add (S2 Q3).
4. **Angle from the surface** instead of the normal (S1 Q1, A1 Q1).
5. **TIR from low to high $n$**, or $\sin\theta_c$ inverted (S1 Q5b).
6. **Brewster in water**: $\tan\theta_p = 1.66/1.33$, not 1.66 (A1 Q3b).
7. **Prism**: skipping $r_2 = A - r_1$, the face-2 TIR check, or rounding early (A1 Q4).
8. **$\cos^2\theta = k$** means $\theta = \cos^{-1}\sqrt{k}$ (Ex 6, S2 Q2b).

---

## Errata
Checked by recomputing every value and against textbook pp. 898 to 924. This section sits outside the 2-page sheet above.

**Requested items**

1. **L3-Pol s.6, spectrum** (requested as the Lecture 1 spectrum slide, but Lecture 1 has no spectrum slide; this is the only one). The second arrow line says energy rises as $\lambda$ grows. Correct: as $\lambda$ increases, $f$ decreases and photon energy **decreases**, since $E = hf = hc/\lambda$ (L1 s.7). Check: a 400 nm photon carries $4.97\times10^{-19}$ J, a 700 nm photon $2.84\times10^{-19}$ J.
2. **L2 s.21, Huygens refraction, step (4).** It writes $v_1$ twice. Correct: $v_1 = c/n_1$ and $v_2 = c/n_2$, which gives $\frac{\sin\theta_1}{\sin\theta_2} = \frac{n_2}{n_1}$ (textbook p. 912).
3. **L3-Pol s.15, Example 7(b), middle step.** It equates $\frac{3}{8}I_b\cos^2 45^\circ$ with $\frac{I_b}{2}\cos^2 30^\circ$, which is only $\frac{3}{8}I_b$. Correct: $I_3 = \frac{I_b}{2}\cos^2 30^\circ\cos^2 45^\circ = \frac{1}{2}\cdot\frac{3}{4}\cdot\frac{1}{2}I_b = \frac{3}{16}I_b$. The final answer on the slide is right.
4. **L3-Pol s.14, Example 6.** Checked: the slide as displayed already shows $\cos\theta = \sqrt{1/5} = 1/\sqrt5 = 0.447$, giving $\theta = 63.4^\circ$, which is correct. The PDF's hidden text layer drops the square root, so text copied or searched from the PDF reads $\cos\theta = 1/5$, which would give 78.5°. Fix any notes made from copied text.
5. **L3-Disp s.17, rainbow.** The fourth bullet says red reaches the observer because it is deviated most and violet passes over because it is deviated least. This is reversed. Violet is turned through $180^\circ - 40^\circ = 140^\circ$ and red through $180^\circ - 42^\circ = 138^\circ$, so violet is deviated **more**. What sends red to your eye from a high drop is that it leaves at the larger angle (42°) to the sunlight, so it heads down more steeply; the 40° violet ray passes overhead. Textbook p. 913 says red is deviated least and violet most.

**Additional items found**

6. **L3-Pol s.8, statement (b).** It says a polarized wave passes easily through a slit perpendicular to its polarization. Correct: it **cannot** pass; figure (b) on the same slide shows it blocked. Light analog: crossed polarizers give $I = 0$ (s.12).
7. **L3-Pol s.8, rope figure.** The rope vibrating up and down is labeled "Horizontally polarized" and the side-to-side rope "Vertically polarized". The labels are swapped; the slide's own text defines the polarization by the vibration direction.
8. **L3-Disp s.9.** It claims the $\delta$ versus $i_1$ curve is symmetric about the minimum. The slide's own plot is lopsided. For that prism ($n = 1.52$, $A = 60^\circ$, minimum at $i_1 = 49.5^\circ$), $\delta = 44.3^\circ$ at 15° below the minimum but $41.9^\circ$ at 15° above it. Reversibility only means each $\delta$ above $\delta_{min}$ occurs at two incidence angles ($i_1$ and the matching $i_2$), which is why the minimum sits at $i_1 = i_2$.
9. **L3-Disp s.16, Example 2.** (a) First line drops the sine. Correct: $\sin\frac{A+\delta_{min}}{2} = n\sin 30^\circ = n/2$. (b) The red line writes $\delta_V$ where it means $\delta_R$, and rounds 49.214° up to 49.22°. Correct: $\frac{60^\circ+\delta_R}{2} = 49.21^\circ$, $\delta_R = 38.43^\circ$. (c) $\theta = 39.14^\circ - 38.43^\circ = 0.71^\circ$, not 0.70°. (d) $\omega = 0.0081/0.517 = 0.0157$, not 0.0156. (e) $V$ is written as $1/0.015 = 64.1$, but $1/0.015 = 66.7$; correct $V = 1/0.01567 = 63.8$. The conclusion ($V > 50$, low dispersion) does not change.
10. **L3-Pol s.5.** It says light in any medium is slower than its speed "in air c". $c$ is the vacuum speed; air itself has $n = 1.000293$ (textbook p. 907). For quiz numbers keep the course convention $n_{air} = 1$ (L2 s.4).
11. **S1 Q4(a).** Asks for "the angle $\theta_1$ of the emerging beam". It should be $\theta_2$, as labeled in the figure and in textbook problem 34.45.
12. **Minor.** L3-Pol s.18 "Brewester" should be Brewster. L3-Disp s.4 "$n_{yello}$" should be $n_{yellow}$. L2 s.10 refers to "Figure c", which is on s.11.
