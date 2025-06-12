---
title: 🎉 A Pseudo-Time Stepping and Parameterized Physics-Informed Neural Network Framework for Navier-Stokes Equations
summary: Take full control of your personal brand and privacy by migrating away from the big tech platforms!
date: 2023-10-27

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.

## Summary & Overview

---

This poster introduces **P2PINN: A Pseudo-Time Stepping and Parameterized Physics-Informed Neural Network Framework for Navier-Stokes Equations**. Our work addresses two major limitations of traditional Physics-Informed Neural Networks (PINNs): unstable training and the necessity for retraining when PDE parameters change.

P2PINN tackles these issues by:
* Integrating a **pseudo-time stepping method** to significantly stabilize training, even for complex problems like the Navier-Stokes equations.
* Employing a dedicated **encoder network** that extracts hidden representations of PDE parameters. This enables the network to learn a generalized solution across a wide parameter range by training on just **two** PDE parameters.

The key benefits of P2PINN are enhanced training stability and remarkable computational efficiency. Our framework achieves a **2–4 orders of magnitude speedup** compared to standard PINNs, all while maintaining high accuracy. This allows for rapid interpolation and extrapolation to unseen parameter sets.

This research is a collaborative effort with **Dr. Xiong Xiong from Northwestern Polytechnical University**. We wish him the very best for a successful and early graduation!

---

### Article Website

You can find the article published here:
* [A pseudo-time stepping and parameterized physics-informed neural network framework for Navier–Stokes equations](https://pubs.aip.org/aip/pof/article-abstract/37/3/033612/3338823/A-pseudo-time-stepping-and-parameterized-physics)
