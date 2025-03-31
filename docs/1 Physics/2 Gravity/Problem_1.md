# Problem 1: Orbital Period and Orbital Radius

---

## 1. Theoretical Foundation

Kepler’s Third Law relates the orbital period \( T \) of a satellite or planet to the radius \( r \) of its orbit:

$$
T^2 \propto r^3
$$

This arises from Newton’s Law of Universal Gravitation and centripetal force:

- Gravitational force:  
  $$
  F_g = \frac{G M m}{r^2}
  $$

- Centripetal force for circular motion:  
  $$
  F_c = \frac{m v^2}{r}
  $$

Equating \( F_g = F_c \), we get:

$$
\frac{G M m}{r^2} = \frac{m v^2}{r}
\Rightarrow v^2 = \frac{G M}{r}
$$

Using \( T = \frac{2\pi r}{v} \) and substituting:

$$
T^2 = \frac{4\pi^2}{G M} r^3
$$

---

## 2. Real-World Implications

- **Calculating planetary masses** from orbital period and radius
- **Moon–Earth system**: Determining the mass of Earth using the Moon's orbit
- **Artificial satellites**: Determining the height needed for a satellite to maintain geostationary orbit

---

## 3. Python Simulation

We can simulate a circular orbit and numerically verify Kepler’s law.

### 📊 Verifying Kepler's Third Law

The following plot confirms the proportional relationship between the square of the orbital period \( T^2 \) and the cube of the orbital radius \( r^3 \):

![Kepler's Third Law](https://i.imgur.com/cRQ3q1N.png)


---

## 4. Extension to Elliptical Orbits

Although this derivation is for circular motion, Kepler's Third Law also applies to elliptical orbits when using the semi-major axis instead of radius:

$$
T^2 \propto a^3
$$

Where \( a \) is the semi-major axis of the ellipse.

---

