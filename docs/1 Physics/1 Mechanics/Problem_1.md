# Problem 1: Investigating the Range as a Function of the Angle of Projection

---

## 🎯 Motivation

Projectile motion, while seemingly simple, offers a rich playground for exploring fundamental principles of physics. This problem focuses on analyzing how the **range** of a projectile depends on its **angle of projection**. Beneath the surface lies a versatile framework involving linear and quadratic relationships that form the foundation of classical mechanics.

### Parameters:
- Initial velocity (v₀)
- Gravitational acceleration (g)
- Launch angle (θ)
- Launch height (h, optional)

---

## 📘 1. Theoretical Foundation

Using kinematic equations, the position of a projectile at time `t` is:

- Horizontal:  
  $$ x(t) = v_0 \cdot \cos(\\theta) \cdot t $$

- Vertical:  
  $$ y(t) = v_0 \cdot \sin(\\theta) \cdot t - \\frac{1}{2}gt^2 $$

Assuming the projectile lands at the same height it was launched:

### Time of flight:
$$ t = \\frac{2v_0 \sin(\\theta)}{g} $$

### Horizontal range:
$$ R(\\theta) = \\frac{v_0^2 \\cdot \\sin(2\\theta)}{g} $$

This shows the range depends on **sin(2θ)**, which peaks at 45° for maximum distance.

---

## 📊 2. Analysis of the Range

- As θ varies from 0° to 90°, the range follows a **sine curve**.
- For fixed `v₀`, the range is maximum when θ = 45°.
- Different `v₀` values vertically scale the curve.
- If launch height ≠ 0, range increases asymmetrically.

### Python Simulation (Basic Example):

![Range vs Angle](../../_pics/range_vs_angle.png)
