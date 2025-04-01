# Problem 1: Measuring Earth’s Gravitational Acceleration with a Pendulum

---

## 🎯 Motivation

The gravitational acceleration \( g \) is a universal constant influencing nearly all physical motion. Using a simple pendulum provides a classic way to experimentally determine \( g \), while also emphasizing error analysis, measurement uncertainty, and scientific precision.

---

## 🧪 Task

Use a pendulum to measure the local gravitational acceleration \( g \), and quantify uncertainties in:

- Timing measurements
- Length measurements
- Final calculation of \( g \)

---

## 🛠️ Materials

- String (0.5–1.5 m)
- Small mass (e.g., metal nut, coin)
- Stopwatch or timer
- Ruler or measuring tape

---

## 🧰 Procedure

### 1. Setup

- Attach the mass to the string and fix the other end
- Measure the length \( L \) of the pendulum from pivot to center of mass
- Determine uncertainty:  
  \( \Delta L = \frac{\text{Ruler Resolution}}{2} \)

---

### 2. Data Collection

- Displace pendulum (~15°), release gently
- Time 10 oscillations: repeat 10 times  
- Calculate mean time:  
  \( \overline{T_{10}} \), then  
  \( \overline{T} = \frac{\overline{T_{10}}}{10} \)

- Uncertainty in \( \overline{T} \):  
  \( \Delta \overline{T} = \frac{s}{\sqrt{n}} \)

---

## 🧮 Calculations

### 1. Compute Period

\[
T = \frac{\overline{T_{10}}}{10}
\]

### 2. Determine \( g \)

\[
g = \frac{4\pi^2 L}{T^2}
\]

### 3. Propagate Uncertainty

\[
\Delta g = g \sqrt{ \left( \frac{\Delta T}{T} \right)^2 + \left( \frac{\Delta L}{L} \right)^2 }
\]

---

## 📊 Analysis

- Compare with accepted \( g = 9.81 \, \text{m/s}^2 \)
- Discuss:
  - Impact of timing and length uncertainties
  - Accuracy of stopwatch, ruler resolution
  - Sources of error (e.g., air drag, angle, string stiffness)

---

## ✅ Deliverables

- Table of \( L \), \( T \), \( \overline{T} \), \( s \), \( g \), \( \Delta g \)
- Final value of \( g \pm \Delta g \)
- Discussion of uncertainty and how it impacts conclusions

### 📈 Comparing Measurement with Theoretical Curve

The plot below compares the **measured pendulum period** (with uncertainty) to the theoretical relationship:

\[
T = 2\pi \sqrt{\frac{L}{g}}
\]

- ✅ The green curve is the theoretical prediction assuming \( g = 9.81 \, \text{m/s}^2 \)
- 🔴 The red point is the student's measured value with error bars

This visual helps verify the consistency of the experiment with Newtonian gravity.

![Pendulum Period Plot](https://i.imgur.com/6n27XHK.png)
