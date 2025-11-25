# This repository contains the analyses, scripts, and results associated with the development of a computational platform based on molecular dynamics simulations designed to study the interaction between photosensitizers (FSs) and realistic models of the mitochondrial outer membrane.

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


