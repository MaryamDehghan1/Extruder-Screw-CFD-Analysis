CFD Analysis of Material Flow in an Extruder Screw

Project Overview

This project presents a computational fluid dynamics (CFD) analysis of material flow in a single-screw extruder using ANSYS Fluent. The study examines the pressure and temperature fields and selected flow characteristics within the modeled extrusion domain.

The simulation was independently set up and performed by the author. A previously published master's thesis was consulted as a technical reference for the screw configuration and for comparing selected results under approximately similar operating conditions. The reference study was not used as a source of simulation images or as a substitute for the present numerical analysis.

This repository contains selected geometry, mesh, and post-processing figures. The complete ANSYS project files are not included.

Numerical Model and Operating Conditions

- CFD software: ANSYS Fluent
- Application: Single-screw extrusion
- Geometry: Screw and surrounding flow domain
- Fluid model: Power-law viscosity model
- Density: 1170 kg/m³
- Screw rotational speed: 30 rpm
- Inlet normal velocity: 0.01 m/s
- Outlet boundary condition: Outflow
- Barrel wall condition: Zero wall velocity

These values describe the modeled case. The interpretation of the results depends on the complete material properties, boundary conditions, mesh quality, and numerical solver settings. Additional parameters should be reported where available.

Geometry and Mesh

Screw Geometry

The screw geometry was modeled to correspond to the configuration selected from the reference study.

"Screw geometry" (screw_geometry.png)

Computational Mesh

The following figure presents the computational mesh used in the simulation.

"Computational mesh" (screw_mesh.png)

Simulation Results

Pressure Distribution

The pressure contour illustrates the spatial distribution of pressure in the modeled extrusion domain.

"Pressure contour" (pressure_contour.png)

Temperature Distribution

The temperature contour presents the temperature field obtained from the simulation.

"Temperature contour" (temperature_contour.png)

Comparison with the Reference Study

Selected results from the present simulation were compared with results reported in the reference thesis under approximately similar operating conditions.

"Comparison with the reference study" (reference_comparison.png)

The comparison is intended to assess similarities and differences in selected reported quantities. Differences in geometry details, material properties, boundary conditions, discretization methods, and solver settings may affect the results. Therefore, the comparison should not be interpreted as a complete numerical validation unless the relevant conditions and quantitative metrics have been verified.

Reference

D’Intinosante, N. (2020). Computational Fluid Dynamics Investigation of a Single Screw Extruder: A Flow and Heat Transfer Analysis. Master’s thesis, Politecnico di Torino.

Official thesis record: https://webthesis.biblio.polito.it/16311/

The reference thesis uses ANSYS Polyflow with the finite element method (FEM), whereas the present project uses ANSYS Fluent. The thesis is cited as a technical reference for the modeled configuration and selected result comparisons.

Limitations

- This repository presents selected simulation figures rather than a complete, independently reproducible simulation package.
- The available figures alone do not establish mesh independence or numerical convergence.
- The strength of the comparison with the reference study depends on the consistency of the compared operating conditions and reported quantities.
- No claim of complete validation is made solely on the basis of visual similarity or approximate agreement.

Software

ANSYS Fluent
