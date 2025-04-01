# Problem 1: Simulating the Effects of the Lorentz Force

---

## 🎯 Motivation

The **Lorentz force** governs the motion of charged particles in the presence of electric and magnetic fields. It plays a central role in:

- Particle accelerators  
- Mass spectrometers  
- Plasma confinement  
- Magnetic traps and cyclotrons

Understanding how electric \( \vec{E} \) and magnetic \( \vec{B} \) fields influence charged particles allows us to design and control complex systems in physics and engineering.

---

## 🧠 Theoretical Background

The Lorentz force equation is:

$$
\vec{F} = q (\vec{E} + \vec{v} \times \vec{B})
$$

Where:
- \( q \): Charge of the particle  
- \( \vec{v} \): Velocity vector  
- \( \vec{E} \): Electric field  
- \( \vec{B} \): Magnetic field  

Depending on the configuration, the motion can be:
- Circular (uniform \( \vec{B} \))  
- Helical (uniform \( \vec{B} \) + parallel \( \vec{v} \))  
- Drifting (crossed \( \vec{E} \) and \( \vec{B} \))

---

## 🧪 Simulation Task

Implement a Python simulation that computes the trajectory of a charged particle in:

1. **Uniform magnetic field**  
2. **Uniform electric and magnetic fields**  
3. **Crossed electric and magnetic fields**

Use numerical integration (Euler or Runge-Kutta) to solve the motion equations.

---

## 🔁 Parameter Exploration

Allow variation of the following parameters:
- \( \vec{E} \), \( \vec{B} \) field vectors  
- Initial velocity \( \vec{v}_0 \)  
- Charge \( q \) and mass \( m \)

Explore how these changes affect:
- Larmor radius  
- Helix pitch  
- Drift velocity

---

## 📊 Visualization

Create 2D and 3D plots of particle motion:
- Show path shapes (circle, helix, drift)
- Highlight physical quantities like radius and direction

---

## 📦 Deliverables

- Python script or notebook
- Visualizations for each field configuration
- Summary of physical insights gained from simulation
- Optional: Extend to **non-uniform fields** or multiple particles

---

## 🧮 Python Simulation 

### 🧲 Charged Particle in a Uniform Magnetic Field

This plot shows the trajectory of a charged particle under the influence of a uniform magnetic field:

- **Initial velocity** has components both perpendicular and parallel to the field
- Resulting motion is a **helix** around the magnetic field lines
- This is a typical motion seen in cyclotrons and plasma traps

![Lorentz Trajectory](https://i.imgur.com/9HAXnGR.png)
