---
marp: true
theme: ssc
paginate: true
title: SSC Project Overview 2026.07.21
---

<!-- _class: title -->
<!-- _paginate: false -->

# SSC Project Overview

## 2026.07.21

---

# Format

For each project we have two slides

- one slide with a fixed format for every project
- another slide with anything the presenter wants to present

Then questions / comments / discussion.

---

<!-- _class: subtitle -->

# Current SSC Projects

---

# SEVN

- *Project type:* Open Call
- *Description:* Astrophysics simulation code for binary stars
- *Developer time:* 4 PM
- *People:* Liam
- *Techstack:* C++ / Python / wasm
- *Topic:* Performance Engineering

---

# SEVN Performance Engineering

![width:900px](sevn.png)

---

# body-eye-sync

- *Project type:* Open Call
- *Description:* GUI to synchronise video and audio inputs and track mutual gaze of participants
- *Developer time:* 4 PM
- *People:* Tuyen, James, Liam
- *Techstack:* Python
- *Topic:* Feature development

---

# body-eye-sync object tracking

![width:600px](body-eye-sync.jpg)

---


# Bio-Structure Hub

- *Project type:* Externally Funded (KTS)
- *Description:* Establish a hub for structure prediction of biomolecules
- *Developer time:* 15/36 months
- *People:* Christine, Inga, Johannes, Rebecca Wade (HITS)
- *Techstack:* Python 
- *Topic:* HPC infrastructure access, consultation, training

---

![bg left:40% contain](bsh_map.png)

- over 20 requests / projects
- new tutorials / notebooks:
    - antibody / protein generation
    - molecular dynamics
    - protein-protein interaction
    - bwVisu to Helix transition
    - AlphaFold mapping

- MCB course, HD-MA symposium, science slam, ELIXIR TTT

---
# ndtbl

- *Project type:* bwRSE4HPC
- *Description:* Fast and memory-efficient lookup in high-dimensional tables
- *Developer time:* 3 PM
- *People:* Thomas
- *Techstack:* C++ / Python
- *Topic:* Feature development

---
# ndtbl: shared-memory
<style scoped>
.figure-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 16px;
  height: 550px;
  align-items: center;
}

.figure-grid img {
  width: 65%;
  height: 100%;
  object-fit: contain;
}

.figure-grid .right {
  grid-column: 2;
  grid-row: 1 / 3;
}
</style>

<div class="figure-grid">
  <img src="ndtbl-2.png">
  <img class="right" src="ndtbl-1.svg">
  <img src="ndtbl-3.png">
</div>

---

# Turbine Design System

- *Project type:* bwRSE4HPC
- *Description:* Provide a reusable Python orchestration layer for their workflows
- *Developer time:* 1.5 PM
- *People:* Thomas
- *Techstack:* Python (some C++)
- *Topic:* Python packaging, best practices, reproducibility

---

# Turbine Design System
Left: not optimized, Right: optimized
![width:750px](tds-1.png)

- Optimization of blade geometry (or any geometry submerged in a flow)
- Island model: launch many candidiates, each with a CFD simulation, exchange information
- Python "code" uses bindings to dtOO, an old-school C++ code
- No reproducible installation (copy paste code), no dependency management, no package

---

# py4dgeo

- *Project type:* Open Call 2021/22, now externally funded
- *Description:* Change analysis of three-dimensional point cloud time series
- *Developer time:* 2 PM / year + extras
- *People:* Dominic, Dimitrii, Thomas + former members Petr, Alex
- *Techstack:* Python / C++ (pybind11)
- *Topic:* Feature development, maintenance

---

# py4dgeo: Change Analysis
- Laser scanning (Lidar) used to acquire point clouds of scenes
- Automated analysis and change quantification of time series of point clouds
- Quantitatively understanding geomorphological processes
![width:550px](py4dgeo-1.png)
