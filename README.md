CFD Analysis of Material Flow in an Extruder Screw

Overview

This project presents a computational fluid dynamics (CFD) analysis of material flow in a single-screw extruder using ANSYS Fluent. The simulation focuses on the pressure and temperature fields within the modeled extrusion domain.

The screw geometry was selected with reference to a published master's thesis. The CFD model was set up and simulated independently in ANSYS Fluent. Selected results were then compared with results reported in the reference study.

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

These parameters describe the current simulation setup. Further material properties, boundary conditions, and numerical settings may be documented as additional details become available.

Results

Screw Geometry

"Screw Geometry" (screw_geometry.png)

Pressure Contour

"Pressure Contour" (pressure_contour.png)

Temperature Contour

"Temperature Contour" (tempreture_contour.png)

Reference Comparison

"Reference Comparison" (refrence-comparision.png)

The comparison presents selected results from the reference study. Differences in software, numerical methods, model assumptions, and operating conditions should be considered when interpreting the results.

Reference

D’Intinosante, N. (2020). Computational Fluid Dynamics Investigation of a Single Screw Extruder: A Flow and Heat Transfer Analysis. Master's thesis, Politecnico di Torino.

Official thesis record: https://webthesis.biblio.polito.it/16311/

The reference study uses ANSYS Polyflow, whereas the present simulation was performed using ANSYS Fluent.

Limitations

This repository contains selected simulation figures and a description of the modeled case. The complete ANSYS project files are not included. The available figures alone do not establish mesh independence, numerical convergence, or quantitative validation.

Software

ANSYS Fluent
