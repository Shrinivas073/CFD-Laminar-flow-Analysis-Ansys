# 🌊 CFD Analysis of Laminar Flow through a Circular Pipe  | ANSYS Fluent

#### *A 2D Steady-State Laminar Internal Flow Simulation using ANSYS Fluent 2026 R1*

<p align="center">

![ANSYS Fluent](https://img.shields.io/badge/Software-ANSYS%20Fluent%202026%20R1-red?style=for-the-badge)

![CFD](https://img.shields.io/badge/Domain-Computational%20Fluid%20Dynamics-blue?style=for-the-badge)

![Fluid Mechanics](https://img.shields.io/badge/Physics-Fluid%20Mechanics-00A6FF?style=for-the-badge)

![Laminar Flow](https://img.shields.io/badge/Flow-Laminar-green?style=for-the-badge)

![Internal Flow](https://img.shields.io/badge/Application-Internal%20Flow-orange?style=for-the-badge)


</p>

---

## 📖 Repository Overview

This repository presents a **2D steady-state Computational Fluid Dynamics (CFD)** simulation of **laminar flow through a circular pipe** performed using **ANSYS Fluent 2026 R1**.

The objective of this project is to investigate how viscous effects and wall shear influence the development of the velocity profile inside an internal flow domain. As fluid enters the pipe with a nearly uniform velocity distribution, the no-slip condition at the walls initiates boundary layer growth, gradually transforming the flow into a fully developed laminar profile.

Although laminar pipe flow is one of the most fundamental problems in fluid mechanics, it forms the basis for understanding momentum diffusion, pressure losses, and boundary layer development in internal flow systems.

This project serves as a foundational study in **internal flow analysis, viscous fluid behaviour, Reynolds number characterization, numerical simulation, and CFD post-processing using ANSYS Fluent.**

---

> **Engineering Focus**
>
> Understanding boundary layer growth, viscous effects, and velocity profile development in laminar internal flow using Computational Fluid Dynamics.

---

# 📑 Table of Contents

- [📖 Repository Overview](#-repository-overview)

- [🎯 Project Objectives](#-project-objectives)

- [📚 Engineering Background](#-engineering-background)

- [🌊 Governing Physics](#-governing-physics)

- [🧩 Geometry Creation](#-geometry-creation)

- [🕸️ Mesh Generation](#️-mesh-generation)

- [⚙️ Solver Setup](#️-solver-setup)

- [💧 Material Properties](#-material-properties)

- [🚪 Boundary Conditions](#-boundary-conditions)

- [💧Reynolds Number & Inlet Velocity Calculation](#-reynolds-number--inlet-velocity-calculation)

- [📉 Solution & Convergence](#-solution--convergence)

- [📊 Results & Post-Processing](#-results--post-processing)

- [🧠 Engineering Discussion](#-engineering-discussion)

- [✅ Validation](#-validation)

- [💡 Key Learnings](#-key-learnings)

- [🛠️ Skills Demonstrated](#️-skills-demonstrated)

- [📂 Repository Structure](#-repository-structure)

- [🚀 Future Improvements](#-future-improvements)


---

## 📷 Repository Preview


<p align="center">

<img src="Velocity Magnitude.png" width="900">

</p>

---

## 📌 About This Repository

This repository is part of my Computational Fluid Dynamics learning portfolio, where I document simulation projects with a strong emphasis on understanding the underlying engineering principles rather than simply presenting software outputs.

Each project is developed to strengthen my understanding of **fluid mechanics, CFD, numerical methods, heat transfer, and engineering analysis** while following professional documentation practices.

I welcome constructive feedback, discussions, and suggestions from the engineering community.

# 🎯 Project Objectives

This project was undertaken to develop a numerical understanding of **steady-state laminar flow** through a circular pipe using Computational Fluid Dynamics (CFD). While analytical solutions accurately describe fully developed laminar flow, CFD provides deeper insight into how the flow evolves from the inlet, how boundary layers develop, and how viscosity influences the velocity distribution.

The primary objectives of this study are:

- Investigate the development of laminar flow inside a circular pipe at **Re = 100**.

- Visualize the evolution of the velocity profile along the pipe length.

- Study the influence of viscous effects and wall shear on boundary layer growth.

- Understand pressure variation and momentum transport in internal flows.

- Gain practical experience in geometry creation, meshing, solver setup, and post-processing using **ANSYS Fluent 2026 R1**.

- Validate the numerical results against the expected behaviour of fully developed laminar pipe flow.

---

# 📚 Engineering Background

Internal flows are among the most frequently encountered fluid flow problems in engineering, forming the basis for the design and analysis of piping systems, heat exchangers, hydraulic circuits, cooling channels, and process equipment.

When a fluid enters a pipe, the velocity profile is initially almost uniform. As the fluid travels downstream, the **no-slip condition** causes the velocity at the wall to become zero, creating boundary layers that progressively grow toward the pipe centreline. Once these boundary layers merge, the flow becomes **hydrodynamically fully developed**, exhibiting the classical **parabolic velocity profile** characteristic of laminar flow.

Although this behaviour can be described analytically, CFD provides engineers with the ability to visualize the complete flow development, pressure distribution, and velocity gradients throughout the computational domain.

This project therefore serves as a fundamental study in **internal flow physics**, bridging classical fluid mechanics with modern numerical simulation techniques.

---

# 🌊 Governing Physics

The present analysis considers **steady-state, incompressible, Newtonian laminar flow** through a circular pipe.

The simulation is based on the following assumptions:

- Two-dimensional planar analysis
- Steady-state flow
- Incompressible fluid
- Newtonian fluid behaviour
- Laminar flow regime (Re = 100)
- Constant fluid properties
- No-slip wall condition
- Negligible gravitational effects

Under these assumptions, the flow behaviour is governed by the conservation of **mass** and **momentum**.

The simulation solves the **Continuity Equation** together with the **Navier–Stokes Equations**, allowing the development of the velocity field and pressure distribution to be predicted throughout the pipe.

As the solution converges, the flow gradually transitions from a nearly uniform inlet profile to a fully developed parabolic velocity profile due to viscous momentum diffusion and wall shear.

---

# 💡 Engineering Significance

Although laminar pipe flow is considered one of the fundamental problems in fluid mechanics, it forms the basis for understanding far more complex internal flow applications.

The concepts explored in this project are directly applicable to:

- Industrial piping systems
- Heat exchangers
- Cooling channels
- Hydraulic circuits
- Chemical process equipment
- Medical flow devices
- Microfluidic systems
- Aerospace fuel and cooling lines

Developing a strong understanding of laminar internal flow provides the foundation for advanced CFD studies involving turbulent flows, multiphase systems, conjugate heat transfer, and complex fluid transport phenomena.












