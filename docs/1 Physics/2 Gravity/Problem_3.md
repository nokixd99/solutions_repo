# Problem 3: Trajectories of a Freely Released Payload Near Earth

---

## 1. Motivation

When a payload is released from a moving spacecraft near Earth, its resulting trajectory can vary depending on its initial speed and direction. This includes:

- Suborbital paths (returns to Earth)
- Stable orbits (elliptical or circular)
- Escape trajectories (parabolic or hyperbolic)

Understanding these trajectories is critical in satellite deployment, interplanetary missions, and re-entry planning.

---

## 2. Theoretical Background

### Newton’s Law of Universal Gravitation:

$$
F = \frac{GMm}{r^2}
$$

Combining this with Newton’s Second Law gives us the equation of motion:

$$
\vec{a} = -\frac{GM}{r^3} \vec{r}
$$

Where:
- \( G \): Gravitational constant
- \( M \): Mass of the Earth
- \( \vec{r} \): Position vector from Earth’s center
- \( \vec{a} \): Gravitational acceleration acting on the payload

---

### Energy-based Classification of Trajectories:

- If total mechanical energy \( E < 0 \): Elliptical orbit
- If \( E = 0 \): Parabolic escape
- If \( E > 0 \): Hyperbolic escape

---

## 3. Python Simulation (coming next...)

### 🛰️ Simulated Trajectories of a Freely Released Payload

The following plot shows three possible trajectories of a payload released from a spacecraft near Earth:

- **Suborbital:** falls back to Earth
- **Circular Orbit:** remains in orbit
- **Escape:** exceeds escape velocity and leaves Earth’s gravity

![Payload Trajectories](https://i.imgur.com/dB2lIda.png)


---

## 4. Applications

This analysis helps:
- Design satellite releases from orbit
- Plan re-entry paths for capsules
- Simulate slingshot and escape maneuvers

---
