# Automotive Aerodynamics CFD Analysis

## 📌 Project Overview
This repository collects Computational Fluid Dynamics (CFD) studies focused on vehicle external aerodynamics to improve efficiency and reduce drag.

## 📂 Projects

### 1. Full Vehicle CFD (Alfa Romeo MiTo)
* **Goal:** Assessment of Drag ($C_D$) and Lift ($C_L$) coefficients.
* **Setup:** RANS simulations ($k-\epsilon$ turbulence model) using **STAR-CCM+**.
* **Analysis:** Investigated flow separation, pressure distribution, and wake structures. Compared baseline configuration vs. front wheel spats implementation.
* **Outcome:** The addition of spats reduced $C_D$ by 0.004, validating wind tunnel experimental trends.

### 2. Side Mirrors vs. Rear View Cameras
* **Goal:** Evaluate the aerodynamic benefit of replacing traditional side mirrors with camera monitoring systems (CMS).
* **Method:** Comparative CFD analysis on a Mercedes S-Class model.
* **Outcome:** The mirrorless configuration resulted in a drag coefficient reduction of $\Delta C_D \approx -0.027$ and a reduction in frontal area, contributing to improved fuel efficiency and reduced aeroacoustic noise.

## 💻 Tech Stack
* **Software:** STAR-CCM+.
* **Physics:** Steady-state RANS, Moving Reference Frame (MRF) for wheels, Moving Ground.
