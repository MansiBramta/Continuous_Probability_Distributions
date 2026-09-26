# Continuous Probability Distributions: From Curves to Probability #

> Understanding Uniform, Normal, Exponential, Gamma, and Beta distributions through intuition, mathematics, and real-world examples

This repository contains the Python examples, mathematical explanations, and visualizations used in my article on **Continuous Probability Distributions**.

The goal is not just to memorize formulas, but to understand **what each distribution represents, why its formula looks the way it does, and when we use it**.

---

## What You'll Learn

This article explores five commonly used continuous probability distributions:

* **Uniform Distribution**
* **Normal Distribution**
* **Exponential Distribution**
* **Gamma Distribution**
* **Beta Distribution**

For each distribution, the article focuses on:

* Intuition behind the distribution
* Probability Density Function (PDF)
* Parameters and their meaning
* Mean and variance
* Mathematical derivations and interpretations
* Real-world examples
* Python implementation
* Visualizations
* How to interpret the resulting distribution

---

## Distributions Covered

| Distribution    | Main Idea                                        | Support                  |
| --------------- | ------------------------------------------------ | ------------------------ |
| **Uniform**     | Every value within an interval has equal density | $(a \leq X \leq b)$      |
| **Normal**      | Values tend to cluster around a mean             | $(-\infty < X < \infty)$ |
| **Exponential** | Models waiting time until an event occurs        | $(X \geq 0)$             |
| **Gamma**       | Models waiting time for multiple events          | $(X \geq 0)$             |
| **Beta**        | Models continuous values between 0 and 1         | $(0 \leq X \leq 1)$      |

---

## Key Concepts

The article builds on the ideas of **random variables, PDFs, probability, mean, and variance** to understand continuous distributions.

A major focus is learning how to read a probability distribution rather than treating its equation as something to memorize.

For example:

$$
X \sim \text{Normal}(\mu,\sigma^2)
$$

means that the random variable \(X\) follows a Normal distribution with mean $(\mu)$ and variance $(\sigma^2)$.

Similarly:

$$
X \sim \text{Exponential}(\lambda)
$$

$$
X \sim \text{Gamma}(k,\lambda)
$$

$$
X \sim \text{Beta}(\alpha,\beta)
$$

The parameters are not just symbols in the formula—they determine the **shape and behavior of the distribution**.

---

## Python

The examples in this repository use Python to calculate probabilities and visualize distributions.

### Libraries Used

* **NumPy** — numerical calculations
* **Matplotlib** — data visualization
* **SciPy** — probability distributions and statistical calculations

---

## Visualizations

Each distribution is visualized to make it easier to understand how changing its parameters affects its shape.

The visualizations help connect:

**Formula → Parameters → Shape → Interpretation**

rather than looking at the mathematical formula in isolation.

---

## Repository Structure

```text
Continuous_Probability_Distributions/
│
├── Continuous_Probability_Distributions.md
│
├── notebooks/
│   └── code_fle.ipynb
│
├── other_images/
│   └── 68-95-99.png
    └── exponential.png
    └── normal_distribution.png
    └── PMF_VS_PDF.png
    └── summary.png
├── python_images/
│   └── beta_distribution.png
    └── exponential.png
    └── gamma_distribution.png
    └── normal_distribution.png
    └── uniform_distribution.png
│
└── README.md
```

---

## Why This Repository?

Probability distributions are everywhere in statistics and machine learning.

Understanding them helps build the foundation for concepts such as:

* Statistical inference
* Hypothesis testing
* Confidence intervals
* A/B testing
* Machine learning
* Statistical modeling

This repository is part of my ongoing journey of understanding **Data Science through mathematics and intuition**.

---

## About Me

I'm **Mansi Bramta**, with an MSc in Mathematics and a growing focus on Data Science.

I am documenting my learning journey by breaking mathematical and statistical concepts into intuitive explanations, practical examples, and Python visualizations.

### Connect with me

* **GitHub:** [MansiBramta](https://github.com/MansiBramta)
* **LinkedIn:** [Mansi Bramta](https://www.linkedin.com/in/mansi-bramta-65358741b)
* **Medium:** [@mansibramta12](https://medium.com/@mansibramta12)

---

⭐ If you find this repository useful, consider giving it a star!
