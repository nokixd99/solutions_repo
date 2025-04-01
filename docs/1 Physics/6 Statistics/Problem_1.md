# Problem 1: Exploring the Central Limit Theorem through Simulations

---

## 🎯 Motivation

The **Central Limit Theorem (CLT)** is a fundamental concept in probability theory and statistics. It states that the distribution of the sample mean of a sufficiently large number of independent, identically distributed random variables approaches a normal distribution, regardless of the population’s original distribution.

This principle is essential in:
- Estimating population parameters  
- Statistical inference  
- Quality control  
- Finance and engineering applications  

---

## 🧠 Theoretical Background

CLT states that if \( X_1, X_2, ..., X_n \) are i.i.d. random variables with mean \( \mu \) and variance \( \sigma^2 \), then:

$$
\bar{X}_n = \frac{1}{n} \sum_{i=1}^n X_i \to \mathcal{N}(\mu, \frac{\sigma^2}{n})
$$

as \( n \to \infty \)

---

## 🧪 Simulation Task

1. Choose population distributions:
   - Uniform
   - Exponential
   - Binomial

2. Generate a large population dataset for each

3. Sample from the population:
   - Use sample sizes \( n = 5, 10, 30, 50 \)
   - Repeat 1000+ times to build a sampling distribution of the sample mean

4. Plot the histograms of sample means and observe the convergence to normality

---

## 🔬 Parameter Exploration

- How does sample size affect convergence to the normal distribution?
- How does the shape of the original distribution influence this behavior?
- What role does variance play?

---

## 📊 Practical Applications

- Quality control (e.g. product testing)
- Risk modeling in finance
- Estimating population characteristics from samples

---

## 📦 Deliverables

- Python script simulating the CLT
- Visualizations showing sampling distribution convergence
- Short analysis summarizing observations

---

## 💻 Python Simulation 

### 🧪 Sampling from a Uniform Distribution

The following histograms show how the sampling distribution of the sample mean becomes more **normal** as the sample size increases:

- Population: Uniform distribution on [0, 1]
- Each subplot shows sample means from 1000 samples
- As \( n \) increases, the histogram approaches a normal distribution

![CLT Uniform](https://i.imgur.com/cy42HzZ.png)
