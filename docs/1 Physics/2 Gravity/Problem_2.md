# Problem 2: Escape Velocities and Cosmic Velocities

---

## 1. Motivation

Escape velocity is the minimum speed required to break free from the gravitational field of a celestial body without further propulsion. Expanding this concept, we define the:

- **First Cosmic Velocity**: Orbital velocity (e.g. low Earth orbit)
- **Second Cosmic Velocity**: Escape velocity (leave the planet)
- **Third Cosmic Velocity**: Interstellar escape velocity (leave the solar system)

These thresholds are vital in space exploration, satellite deployment, and mission planning for interplanetary and interstellar travel.

---

## 2. Theoretical Background

Using conservation of energy and Newton’s law of gravitation, we can derive:

### Second Cosmic Velocity (Escape Velocity):

$$
v_{esc} = \sqrt{\frac{2GM}{R}}
$$

### First Cosmic Velocity (Orbital velocity near the surface):

$$
v_{orb} = \sqrt{\frac{GM}{R}}
$$

### Third Cosmic Velocity (escape from solar gravity at Earth’s orbit):

$$
v_{3rd} = \sqrt{\frac{2GM_{sun}}{R_{orbit}}}
$$

Where:
- \( G \): Gravitational constant
- \( M \): Mass of the planet/star
- \( R \): Radius from the center of mass
- \( v \): Resulting velocity

---

## 3. Python Calculations

### 🚀 Visualizing Cosmic Velocities

The following bar chart compares the first, second, and third cosmic velocities for Earth, Mars, and Jupiter. These values represent the thresholds for orbital motion, escape from the planet, and solar system departure:

![Cosmic Velocities](https://i.imgur.com/SdlCnsg.png)


---

## 4. Real-World Examples

We'll compute and visualize escape and orbital velocities for:
- Earth 🌍
- Mars 🔴
- Jupiter 🪐

And discuss what it means for rockets and probes.

---

## 5. Applications in Space Exploration

These calculations are critical when designing:
- Launch systems for satellites
- Manned missions to the Moon or Mars
- Deep space missions leaving the Solar System
