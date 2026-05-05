---
layout: page
title: "Research"
subtitle: "Energy-efficient manufacturing, industrial AI, and thermal system design"
permalink: /research/
---

## Overview

My research sits at the intersection of thermal-fluid engineering, machine learning, and industrial energy systems. I develop methods that span the full **design–simulate–operate** cycle of energy-consuming equipment: optimizing component geometry, accelerating the simulations needed to evaluate them, and learning control policies that operate the resulting systems efficiently in the field. The three areas below organize this work by methodological focus rather than by application; in practice, most projects draw on more than one area.

---

## Research Areas

### 1. Thermal-fluid systems engineering

Design and operation of thermal-fluid systems across scales — from individual components to building-scale energy plants. Topology optimization is used to generate non-intuitive geometries for heat sinks and heat exchangers; digital-twin models reproduce system dynamics under realistic boundary conditions; and AI-based controllers search for energy-optimal operating points without violating product-quality or safety constraints. Current work emphasizes the **co-design of equipment and supervisory control** for HVAC and paint-booth air-conditioning systems, where component- and system-level decisions are tightly coupled.

**Keywords:** topology optimization · heat sinks · heat exchangers · HVAC · paint-booth air-conditioning · digital twin · AI-based control · natural and forced convection.

### 2. AI/ML for engineering simulation

Machine-learning methods that accelerate or replace conventional engineering simulations. The work covers neural operators that learn solution maps over function spaces (**GINO**, **PIGANO**), graph neural networks that accelerate convergence of iterative topology-optimization solvers, deep-learned finite elements that embed learned shape functions, surrogate models for expensive multi-physics analyses, and reinforcement-learning agents that explore large design spaces. The ongoing focus is on **operator-learning approaches that generalize across geometries and boundary conditions**, enabling design and control loops that were previously computationally infeasible.

**Keywords:** neural operators · GINO · PIGANO · graph neural networks · deep-learned finite elements · surrogate modeling · deep reinforcement learning · convergence acceleration.

### 3. Industrial energy efficiency

Energy analysis, modeling, and optimization for energy-intensive manufacturing processes and building energy systems. Measurement-driven energy simulations are constructed for processes such as **electrode drying, steel casting, and food/dairy spray drying**, as well as for HVAC systems at the building scale; from these models, energy-based key performance indicators are derived so that process designs and operating strategies can be compared on a consistent basis. Current efforts target battery-electrode drying lines and industrial HVAC, where transient behavior and load coupling dominate the achievable savings.

**Keywords:** electrode drying · steel casting · spray drying · HVAC energy modeling · life-cycle energy analysis · energy-based KPIs · manufacturing process simulation.

---

For the full publication record, see the [Publications page]({{ '/publications/' | relative_url }}) or my [Google Scholar profile](https://scholar.google.com/citations?user=2lOiXO4AAAAJ&hl=ko).
