# ELWallFoam

OpenFOAM solver for pore-scale Eulerian-Lagrangian simulation of nanoparticle transport and deposition in porous media.

---

## Overview

This repository provides a custom OpenFOAM solver (`ELWallFoam`) for simulating nanoparticle transport and deposition in porous media using an Eulerian–Lagrangian (EL) approach.

The solver resolves:
- Fluid flow using Eulerian framework
- Particle tracking using Lagrangian approach
- Coupled particle-fluid interactions

Key physics included:
- Drag force
- Brownian motion
- Saffman lift
- Buoyancy and gravity
- Van der Waals (VDW) forces
- Electrostatic double-layer (EDL) forces

---

## Repository Structure

```
solver/
    ELWallFoam/
tutorials/
related_papers/
figures/
README.md
CITATION.cff
.gitignore
LICENSE
```

---

## Installation

```bash
source /path/to/OpenFOAM-7/etc/bashrc
cd solver/ELWallFoam
wmake
```

---

## Running Example

```bash
cd tutorials/caseName
ELWallFoam
```

---

## Citation

If you use this solver, please cite:

Ramezanpour, M., Siavashi, M., Khoshtarash, H., & Blunt, M. J. (2024).  
Transport and deposition of nanoparticles in porous media at the pore scale using an Eulerian-Lagrangian method.  
Journal of the Taiwan Institute of Chemical Engineers, 161, 105536.

---

## Author

Hamidreza Khoshtarash  
PhD Student – UC Davis
