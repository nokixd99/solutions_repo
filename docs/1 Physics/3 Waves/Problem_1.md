# Problem 1: Interference Patterns on a Water Surface

---

## 📌 Motivation

Interference occurs when waves from different sources overlap, forming new patterns. On water, this can create striking constructive and destructive patterns. 

By studying interference patterns:
- We gain insight into the **principle of superposition**
- We learn how **wave interactions** behave in real systems
- We apply it to **acoustics, optics, and quantum mechanics**

---

## 🧠 Theoretical Background

A circular wave from a point source at \((x_0, y_0)\) can be modeled as:

$$
\eta(x, y, t) = \frac{A}{r} \cos(kr - \omega t + \phi)
$$

Where:
- \( A \): Amplitude  
- \( r = \sqrt{(x - x_0)^2 + (y - y_0)^2} \): Distance from source  
- \( k = \frac{2\pi}{\lambda} \): Wavenumber  
- \( \omega = 2\pi f \): Angular frequency  
- \( \phi \): Initial phase

When multiple sources are present, the resulting displacement is:

$$
\eta_{total}(x, y, t) = \sum_{i=1}^{N} \eta_i(x, y, t)
$$

---

## 🧪 Simulation Task

- Choose a **regular polygon** (e.g., triangle, square, pentagon)
- Place point sources at the **vertices**
- Simulate and **visualize the wave field** formed by superposition

---

## 📝 Steps to Follow

1. Define the positions of the point sources (vertices of polygon)
2. Generate the wave equation for each source
3. Sum all contributions at each point on the surface
4. Plot the **total displacement field** to see interference

---

## 📦 Deliverables

- A Python script or notebook simulating the waves
- Visualizations showing interference regions (constructive & destructive)
- Optional: Animated wave propagation for dynamic understanding

---

## 🧩 Applications

- Acoustic and radio antenna design  
- Light diffraction and optical interference  
- Understanding quantum wave behavior  

---

## 🧮 Python Simulation 

### 🌊 Simulated Interference Pattern (5 Sources)

The following image shows the resulting wave interference pattern formed by five point sources placed at the vertices of a regular pentagon:

- **Bright regions**: constructive interference
- **Dark regions**: destructive interference
- Pattern symmetry matches the geometry of the source layout

![Interference Pattern](https://i.imgur.com/qPE8Erj.png)

