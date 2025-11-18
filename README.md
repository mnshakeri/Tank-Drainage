# 🌀 Analytical Drainage Model for Tanks with Deviated Walls

This repository contains a simple analytical model and accompanying code for predicting the **draining behavior of a tank with deviated (non-vertical) walls**.  
The work was motivated by a fluid-mechanics puzzle shared on LinkedIn, where two tanks with identical volume and orifice size drained at different rates due solely to geometry.

The goal of this project is to provide a clean analytical solution and a small piece of code that demonstrates how geometry controls draining dynamics.

---

## 📘 Problem Description

We analyze a tank defined by:

- **Top diameter:** `d2`  
- **Bottom diameter:** `d1`  
- **Tank height:** `h`  
- **Orifice diameter:** `d0`  
- **Instantaneous water height:** `z`

The cross-sectional area changes with height because the walls are not vertical.

A schematic of the geometry is shown below:

![Tank-Drainage](Schematic.jpeg)
---
