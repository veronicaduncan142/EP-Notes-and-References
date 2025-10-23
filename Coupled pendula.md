# COUPLED PENDULUM EXPERIMENT REPORT

## AIM
To study the normal modes and resonance of coupled pendula and to determine the degree of coupling.

---

## THEORY

### Basic Concept
Two identical pendulums of length \( l \) and mass \( m \) are coupled by a spring of stiffness \( k \). When one pendulum oscillates, energy is transferred to the other through the coupling spring, demonstrating energy exchange and normal mode oscillations.

### Key Formulae

**Natural frequency of each pendulum:**
\[
\omega_0^2 = \frac{g}{l}
\]

**Normal mode frequencies:**
- In-phase mode: \( \omega_0 = \sqrt{\frac{g}{l}} \)
- Out-of-phase mode: \( \omega_1 = \sqrt{\omega_0^2 + \frac{2k}{m}} \)

**Time periods:**
- In-phase: \( T_0 = \frac{2\pi}{\omega_0} \)
- Out-of-phase: \( T_1 = \frac{2\pi}{\omega_1} \)
- Coupled oscillation: \( T_c = 2\frac{T_0 T_1}{T_0 + T_1} \)
- Beat period: \( T_B = 2\frac{T_0 T_1}{T_0 - T_1} \)

**Degree of coupling:**
\[
\chi = \frac{\omega_1^2 - \omega_0^2}{\omega_1^2 + \omega_0^2} = \frac{T_0^2 - T_1^2}{T_0^2 + T_1^2}
\]

### Normal Modes

**Case I – In-phase mode:** Both pendula oscillate together in the same direction with equal displacement. The spring remains at its natural length (neither stretched nor compressed), so it exerts no force. Frequency equals the natural frequency \( \omega_0 \).

**Case II – Out-of-phase mode:** Pendula oscillate in opposite directions with equal amplitude. The spring is alternately stretched and compressed, providing additional restoring force. Frequency \( \omega_1 > \omega_0 \).

**Case III – Resonance (Beat mode):** When one pendulum is displaced and the other is at rest initially, energy transfers completely from one to the other and back. This demonstrates the phenomenon of beats, where the amplitude envelope varies with beat frequency \( \omega_B = \frac{\omega_1 - \omega_0}{2} \).

---

## APPARATUS
1. Coupled pendulum setup with two identical pendula
2. Two springs of different stiffness
3. Stopwatch (least count: _____ s)
4. Adjustable masses and screws for balancing
5. Meter scale

---

## EXPERIMENTAL SETUP

The apparatus consists of two identical pendulums suspended from a common horizontal support. Each pendulum has an adjustable mass at the bottom and a fine adjustment screw at the top for balancing. The pendula are coupled by attaching a spring horizontally at a fixed height on both pendulum rods. The spring should be positioned such that it remains horizontal and at its natural length when both pendula are at rest.

**Important:** The spring attachment height affects the coupling strength. Higher attachment increases the coupling torque (proportional to \( l^2 \)), while lower attachment reduces it.

---

## PROCEDURE

1. **Initial balancing (uncoupled):** Remove the spring. Adjust the masses and screws on both pendula until they have equal time periods. Measure this by timing 50-100 oscillations for each pendulum separately.

2. **In-phase mode (\( T_0 \)):** Couple the pendula with spring 1. Displace both equally in the same direction and release. Measure time for 100 oscillations and calculate \( T_0 \).

3. **Out-of-phase mode (\( T_1 \)):** Displace both pendula equally in opposite directions and release. Measure time for 100 oscillations and calculate \( T_1 \).

4. **Coupled oscillation (\( T_c \)):** Keep one pendulum at rest and displace the other. Measure time for 100 oscillations to determine \( T_c \).

5. **Beat period (\( T_B \)):** Starting from step 4, observe when the initially displaced pendulum comes to complete rest. Record time for 5-6 such complete energy transfers and calculate \( T_B \).

6. **Calculations:** Calculate theoretical values of \( T_c \) and \( T_B \) using formulae. Compare with measured values. Calculate degree of coupling \( \chi \).

7. **Repetition:** Repeat steps 2-6 with spring 2 (different stiffness).

---

## PRECAUTIONS

1. **Equal pendulum adjustment:** Before coupling, carefully adjust both pendula to have identical time periods by fine-tuning masses and adjustment screws. This ensures the theoretical model applies accurately.

2. **Small amplitude:** Keep angular amplitude below 10° to ensure the small angle approximation \( \sin\theta \approx \theta \) remains valid. Large amplitudes introduce nonlinear effects and increase error.

3. **Multiple oscillations:** Time at least 100 oscillations for \( T_0 \), \( T_1 \), and \( T_c \) to minimize random timing errors and improve precision.

4. **Spring natural length:** Ensure the spring is at its natural length when both pendula are at rest. If too tight, it introduces pre-stress; if too loose, sagging occurs and the effective coupling changes.

5. **Parallel oscillation plane:** Both pendula must oscillate in the same vertical plane. Any perpendicular motion introduces additional degrees of freedom and complicates the analysis.

6. **Reduce air resistance:** Perform the experiment in a draft-free environment. Use compact masses to reduce air drag.

7. **Stable support:** Ensure the support frame is rigid and doesn't vibrate. Any movement of the support introduces errors in time period measurements.

8. **Consistent starting:** Start timing at well-defined positions (e.g., extreme displacement) and count oscillations carefully to avoid counting errors.

---

## DISCUSSION POINTS

### 1. **Effect of Spring Position**

**Question:** How does the height at which the spring is attached affect the coupled system?

**Answer:** The spring position significantly affects the coupling strength. The coupling torque on each pendulum is given by \( M_f = -kl^2(\theta_1 - \theta_2) \), where \( l \) is the distance of the spring attachment from the pivot. 

- **Higher attachment:** Increases \( l \), thus increasing the coupling torque. This leads to:
  - Stronger coupling (larger \( \chi \))
  - Greater difference between \( T_0 \) and \( T_1 \)
  - Faster energy transfer (shorter beat period \( T_B \))

- **Lower attachment:** Decreases coupling strength, making energy transfer slower and the system behave more like two independent pendulums.

- **At the pivot:** No coupling torque at all (\( l = 0 \)), so pendula oscillate independently.

**Practical insight:** Optimal spring position depends on the experiment's goal. For clear beat observation, moderate coupling is best. For studying normal modes, stronger coupling provides clearer distinction.

### 2. **Effect of Varying Pendulum Length**

**Question:** What happens if we increase or decrease the length of the pendula?

**Answer:** Changing pendulum length \( l \) affects the system through the natural frequency \( \omega_0 = \sqrt{g/l} \):

- **Increasing length:**
  - Increases both \( T_0 \) and \( T_1 \) (slower oscillations)
  - Decreases the coupling strength parameter since \( \omega_1^2 - \omega_0^2 = 2k/m \) remains constant while \( \omega_0^2 \) decreases
  - Results in weaker effective coupling
  - Beat period \( T_B \) increases (energy transfer becomes slower)

- **Decreasing length:**
  - Decreases time periods (faster oscillations)
  - Increases effective coupling
  - Beat period decreases (faster energy exchange)

**Physical interpretation:** Longer pendula have larger inertia relative to the coupling force, making the spring's influence less significant.

### 3. **Sources of Experimental Error**

**a) Systematic Errors:**
- **Air resistance:** Causes damping, reducing amplitude over time. The actual oscillation is not perfectly harmonic.
- **Friction at pivot:** Introduces additional damping and may cause asymmetric motion.
- **Spring mass:** Theory assumes massless spring. Real springs have mass, affecting the dynamics.
- **Support vibration:** If the frame is not rigid, it can absorb energy from the pendula.
- **Imperfect length matching:** Even slight differences in pendulum lengths violate the identical pendulum assumption.

**b) Random Errors:**
- **Reaction time:** Human error in starting/stopping the stopwatch (typically ±0.2 s).
- **Counting errors:** Miscounting oscillations, especially for small amplitudes near the end.
- **Amplitude variation:** Difficult to maintain constant initial amplitude across trials.

**Remedies:**
- Use heavier, aerodynamic masses to reduce air resistance
- Lubricate pivot points to minimize friction
- Use lightweight springs
- Secure the support frame firmly
- Time many oscillations (100+) to average out random errors
- Use photogate sensors or video analysis for more accurate timing

### 4. **Real-World Applications**

**a) Structural engineering:** Buildings and bridges have multiple coupled oscillating components. Understanding coupled oscillations helps design structures that avoid destructive resonance during earthquakes or wind loads.

**b) Molecular vibrations:** Atoms in molecules behave like coupled oscillators. Normal mode analysis helps understand molecular spectra and chemical bonding.

**c) Electrical circuits:** Coupled LC circuits in radio transmitters and receivers exhibit similar behavior with energy exchange between circuits.

**d) Quantum mechanics:** Coupled quantum systems (e.g., two-level atoms, quantum dots) exhibit energy splitting analogous to the two normal mode frequencies.

**e) Musical instruments:** Coupled strings in pianos and guitars, or coupled air columns in organ pipes, produce complex tones based on coupled oscillation principles.

**f) Clock synchronization:** Huygens observed that two pendulum clocks mounted on the same wall would synchronize due to weak coupling through the wall.

### 5. **Variation: Unequal Masses or Different Lengths**

**Question:** What would happen if the two pendula had different masses or lengths?

**Answer:** 
- With unequal masses or lengths, the pendula have different natural frequencies
- Complete energy transfer never occurs—neither pendulum comes to complete rest
- The ratio \( \frac{\omega_1 + \omega_0}{\omega_1 - \omega_0} \) must be an integer for complete energy exchange
- The system exhibits more complex beating patterns
- This scenario better models real-world systems where perfect symmetry is rare

**Experimental extension:** One could deliberately create slight asymmetry and observe incomplete energy transfer, demonstrating the importance of resonance conditions.

### 6. **Effect of Spring Stiffness**

By using two different springs, we observe:
- Stiffer spring (larger \( k \)) → larger \( \omega_1 \) → greater frequency splitting → stronger coupling
- Softer spring (smaller \( k \)) → \( \omega_1 \) closer to \( \omega_0 \) → weaker coupling → longer beat period

This demonstrates how the coupling parameter \( k \) controls energy transfer rate.

### 7. **Energy Considerations**

In an ideal system, total mechanical energy is conserved and oscillates between the two pendula. In reality:
- Damping causes total energy to decrease exponentially
- Energy is lost to air resistance (proportional to velocity) and friction
- The beats gradually decay in amplitude
- Eventually, both pendula come to rest

**Enhancement:** Using a low-friction, low-resistance setup (e.g., in vacuum with magnetic bearings) would demonstrate nearly perfect energy conservation and long-lasting beats.

---

## CONCLUSION

The coupled pendulum experiment demonstrates fundamental concepts of normal modes, resonance, and energy transfer in coupled oscillating systems. The two normal modes (in-phase and out-of-phase) have distinct frequencies, and their superposition creates the beat phenomenon. The degree of coupling quantifies the strength of interaction and depends on spring stiffness and attachment position. This experiment provides insight into coupled oscillators encountered throughout physics and engineering.

---

## REFERENCES
1. H.J. Pain, *The Physics of Vibrations and Waves*
2. Laboratory manual and experimental guidelines
