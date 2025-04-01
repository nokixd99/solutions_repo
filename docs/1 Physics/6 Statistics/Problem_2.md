# Problem 2: Estimating \( \pi \) Using Monte Carlo Methods

---

## 🎯 Motivation

Monte Carlo methods use randomness to approximate mathematical quantities. One elegant example is estimating \( \pi \) through geometric probability — either by generating random points in a circle or simulating the classic Buffon’s Needle problem.

These approaches not only demonstrate the power of probabilistic thinking but also introduce key concepts in simulation, convergence, and computational estimation.

---

## 🧠 Part 1: Estimating \( \pi \) Using a Circle

### 1. Theoretical Background

The area of a unit circle is \( \pi r^2 = \pi \), and the area of the bounding square is \( 4 \). So the probability of a randomly thrown dart landing inside the circle is:

$$
\frac{\text{Points inside circle}}{\text{Total points}} \approx \frac{\pi}{4} \Rightarrow \pi \approx 4 \cdot \frac{\text{inside}}{\text{total}}
$$

### 2. Simulation

- Randomly generate (x, y) points in the square \([-1, 1] \times [-1, 1]\)
- Count how many fall inside the unit circle
- Use this to estimate \( \pi \)

### 3. Visualization

- Show points inside (blue) vs outside (red) the circle

### 4. Analysis

- Vary the number of points
- Observe how the estimate of \( \pi \) improves as iterations increase

### 🎯 Monte Carlo Estimation of \( \pi \) Using Random Points

The plot below shows randomly generated points inside a square bounding a unit circle:

- **Blue points**: inside the circle  
- **Red points**: outside the circle  
- \( \pi \) is estimated using the ratio of blue points to the total  

![Monte Carlo π](https://i.imgur.com/qYsqVVM.png)

---

## 🪡 Part 2: Estimating \( \pi \) Using Buffon’s Needle

### 1. Theoretical Background

Buffon’s Needle estimates \( \pi \) by simulating a needle of length \( l \) dropped onto a floor with parallel lines spaced distance \( d \) apart:

$$
P(\text{cross}) = \frac{2l}{d\pi} \Rightarrow \pi \approx \frac{2l \cdot N}{d \cdot H}
$$

Where:
- \( N \): Total drops  
- \( H \): Hits (crossing a line)

### 2. Simulation

- Drop a virtual needle at random angles and positions
- Check if it crosses a line

### 3. Visualization

- Plot the needles and parallel lines

### 4. Analysis

- Study how \( \pi \) estimation converges with more drops
- Compare accuracy vs the circle method

---

## 📦 Deliverables

- Python code for both methods
- Visual outputs (plots of dart throws and needle drops)
- Convergence plots
- Discussion on the efficiency and accuracy of both approaches
