# Problem 2: Investigating the Dynamics of a Forced Damped Pendulum

---

## 🎯 Motivation

The forced damped pendulum is a fascinating example of nonlinear dynamics where damping, restoring force, and external driving force interact to produce a rich variety of behaviors — from regular oscillations to chaos. This system models many real-world phenomena, such as driven oscillators in electronics, energy harvesting devices, or even weather systems.

---

## 🧠 1. Theoretical Foundation

The general equation of motion for a forced damped pendulum is:

$$
\frac{d^2\theta}{dt^2} + \beta \frac{d\theta}{dt} + \omega_0^2 \sin(\theta) = A \cos(\omega t)
$$

Where:

- \( \theta(t) \): angular displacement
- \( \beta \): damping coefficient
- \( \omega_0 \): natural frequency \( \sqrt{\frac{g}{L}} \)
- \( A \): amplitude of the driving force
- \( \omega \): driving frequency

### 🔹 Small Angle Approximation:

For small angles \( \theta \ll 1 \), we can linearize the equation:

$$
\frac{d^2\theta}{dt^2} + \beta \frac{d\theta}{dt} + \omega_0^2 \theta = A \cos(\omega t)
$$

This has an analytical solution involving resonance. But for larger angles or general behavior, **numerical simulation** is necessary.

---

## 📊 2. Analysis of Dynamics

We will analyze how the system's behavior changes as we vary:

- Damping coefficient \( \beta \)
- Driving amplitude \( A \)
- Driving frequency \( \omega \)

The system transitions between:

- **Periodic motion**
- **Quasiperiodic motion**
- **Chaotic motion**

We'll illustrate this using phase portraits, time series, and Poincaré sections.

---

## 🛠️ 3. Python Simulation

We will use `scipy` to solve the nonlinear differential equation numerically using Runge-Kutta methods.

### Example features:

- θ(t) vs t (angle over time)
- Phase portrait: \( \theta \) vs \( \dot{\theta} \)
- Poincaré sections
- (Optional) Bifurcation diagrams

**Graph previews will be inserted below.**

---

## 🌍 4. Applications

- Energy harvesting devices
- Suspension bridge oscillations
- Driven RLC circuits
- Human biomechanics (gait modeling)

---

## ⚠️ 5. Limitations and Extensions

This model assumes:

- Ideal point mass
- Rigid rod
- Sinusoidal forcing

Possible extensions:

- Nonlinear damping
- Noise-driven forcing
- Coupled pendula

---

> _This problem bridges theoretical physics and computational modeling, highlighting how simple equations can lead to complex behavior._
