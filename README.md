# This repository contains the analyses, scripts, and results associated with the development of a computational platform based on molecular dynamics simulations designed to study the interaction between photosensitizers (PSs) and realistic models of the mitochondrial outer membrane.

# The work includes:

* Construction and validation of simple, symmetric, and asymmetric membrane models using the MARTINI 3 Lipidome force field.

* Long-timescale simulations (up to 20 μs) performed with GROMACS 2021, following standardized equilibration and production protocols.

* Structural analyses: density profiles, area per lipid (APL), membrane thickness, lipid enrichment, cholesterol distribution, and flip-flop events.

* Interaction studies of ZnPc and TaZnPc with the mitochondrial membrane, including insertion, preferred localization, and translocation.

* Tools used: MDAnalysis, LiPyphilic, FATSLiM, custom Python scripts, and additional utilities.

The overarching goal of this project is to establish a robust platform to computationally evaluate the behavior of photosensitizers and other bioactive molecules in biologically relevant environments, supporting the rational design of photodynamic therapy agents and other biomedical applications.

## Area per Lipid (APL) of the Asymmetric Membrane

This analysis quantifies the average lateral surface area occupied by each lipid, allowing assessment of membrane packing, stability, and structural uniformity across the simulation trajectory.

<img width="6307" height="3361" alt="APL-out-asim-310k-En" src="https://github.com/user-attachments/assets/8b31a703-e339-42d0-ae07-16ee84348c48" />

## Thickness of the Asymmetric Membrane

This analysis measures the distance between the lipid headgroup peaks along the bilayer normal (z-axis), providing insight into membrane compactness, structural integrity, and temperature-dependent variations.

<img width="6307" height="3300" alt="thickness-out-asim-310k-En" src="https://github.com/user-attachments/assets/d9b549ce-82e6-48a3-8a70-e2bf280518ba" />

## Z-Position of ZnPc Relative to the Membrane

This analysis tracks the vertical (z-axis) position of ZnPc throughout the simulation to determine its insertion depth, translocation events between leaflets, and preferred localization within the asymmetric mitochondrial membrane.

<img width="1000" height="600" alt="Z-poticion-Znpc" src="https://github.com/user-attachments/assets/2c7dd3cc-0de4-45b3-9684-547c4a5539f8" />

## Tilt Angle of TaZnPc Within the Membrane

This analysis quantifies the orientation of TaZnPc relative to the membrane normal (z-axis), revealing how the molecule tilts, aligns, or reorients during insertion and interaction with the asymmetric mitochondrial membrane. It helps characterize its preferred orientation and dynamic stability.

<img width="3479" height="1465" alt="tilt-taznpc" src="https://github.com/user-attachments/assets/6d4549ba-ecfe-4fe5-8aa5-0ed1bab238c3" />

## Snapshot of ZnPc and TaZnPc Inserted in the Membrane

Representative frame from the simulation showing ZnPc (1), and TaZnPc (2) embedded within the mitochondrial outer membrane, illustrating its insertion depth and orientation during the interaction process.

<img width="1290" height="479" alt="znpc-mem-asim" src="https://github.com/user-attachments/assets/0ce18d97-3764-43c9-b934-9118ac2f5040" />

<img width="1289" height="477" alt="taznpc-asim" src="https://github.com/user-attachments/assets/67735ddb-7abb-4491-9cbc-916dec6255d3" />



