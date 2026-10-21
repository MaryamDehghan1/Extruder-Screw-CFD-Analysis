CFD Analysis of Material Flow in an Extruder Screw

Overview

This project presents a computational fluid dynamics (CFD) simulation of material flow in a single-screw extruder using ANSYS Fluent.

The main objective is to investigate the pressure and temperature fields within the modeled extrusion domain. The screw geometry was selected with reference to a published master's thesis, while the simulation setup and analysis were carried out independently in ANSYS Fluent.

Selected results are presented alongside a reference study for qualitative comparison. Similarities in geometry or operating conditions do not, by themselves, establish quantitative validation.

Model Setup

- Software: ANSYS Fluent
- Application: Single-screw extrusion
- Geometry: Extruder screw and surrounding flow domain
- Viscosity model: Power-law
- Density: 1170 kg/m³
- Screw rotational speed: 30 rpm
- Inlet normal velocity: 0.01 m/s
- Outlet boundary condition: Outflow
- Barrel wall condition: Zero wall velocity

These parameters describe the current simulation setup. They should be interpreted in the context of the model assumptions and boundary conditions used in ANSYS Fluent.

Simulation Results

1. Screw Geometry

"Screw Geometry" (screw_geometry.png)

Geometry used in the CFD simulation.

2. Pressure Contour

"Pressure Contour" (pressure_contour.png)

Pressure field obtained from the simulation.

3. Temperature Contour

"Temperature Contour" (tempreture_contour.png)

Temperature field obtained from the simulation.

4. Reference Comparison

"Reference Comparison" (refrence-comparision.png)

Selected results compared with the published reference study.

5. Mesh Visualization

"Mesh Visualization" (mesh_visualization.png)

Computational mesh used for discretizing the simulation domain.

Reference

D’Intinosante, N. (2020). Computational Fluid Dynamics Investigation of a Single Screw Extruder: A Flow and Heat Transfer Analysis. Master's thesis, Politecnico di Torino.

Official thesis record: https://webthesis.biblio.polito.it/16311/

The reference study uses ANSYS Polyflow, whereas the present simulation was performed using ANSYS Fluent.

Limitations

This repository presents selected simulation figures and a description of the modeled case. The complete ANSYS project files are not included.

The available figures alone do not establish mesh independence, numerical convergence, or quantitative validation against experimental data.

Software

ANSYS Fluent
