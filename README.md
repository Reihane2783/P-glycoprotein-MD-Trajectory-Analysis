
# Molecular Dynamics Trajectory Analysis of P-glycoprotein Under Plasma-Derived Reactive Species

A collection of Python-based post-processing tools for analyzing molecular dynamics (MD) simulation data, with a focus on residue-level energetics, hydrogen-bond interactions, data processing, and visualization.

This project supports the investigation of structural dynamics and potential destabilization of P-glycoprotein (P-gp) under conditions involving plasma-derived reactive species.

## Project Overview

Molecular dynamics simulations provide atomistic trajectories for investigating protein conformational changes and intermolecular interactions. This project brings together analysis scripts and visualization tools to facilitate the examination of simulation outputs at the amino-acid residue level.

The toolkit includes trajectory-related data analysis, hydrogen-bond counting, residue-level energy processing, and graphical representation of extracted results.

## Analysis Modules

### 1. Trajectory and Force Analysis

Tools for processing molecular dynamics outputs and examining residue-level data.

- Parsing simulation-derived data from supported GROMACS output formats and preprocessed files.
- Extracting and comparing force-related quantities across amino-acid residues.
- Generating plots to visualize residue-level force contributions.

**Repository:** [GROMACS Data Analysis](https://github.com/Haniyekzm/Gromacs-Data-Analysis)

### 2. Hydrogen-Bond Analysis

Tools for characterizing hydrogen-bond participation across simulation frames.

- Counting hydrogen bonds associated with individual residues.
- Summarizing residue-level hydrogen-bond counts.
- Examining the distribution of hydrogen-bond participation across the protein.
- Supporting analysis of interaction patterns relevant to structural stability.

**Repository:** [Hydrogen Bond Counting](https://github.com/Haniyekzm/Hydrogen-Bond-Counting-)

### 3. Residue-Level Energy Analysis

Scripts for processing amino-acid energy values and identifying residues of interest.

- Filtering residues according to their energy values.
- Extracting residues with negative energy contributions.
- Comparing and organizing residue-level energetic data.
- Preparing processed datasets for further analysis.

**Repository:** [Amino Acid Energy Filtering](https://github.com/Haniyekzm/Amino-Acid-Energy-Filtering)

### 4. Energy Visualization

Visualization tools for examining energy distributions across amino-acid residues.

- Color-coded energy distribution plots.
- Residue-level energy visualization.
- Pie charts separating negative from non-negative energy values.
- Graphical summaries to facilitate interpretation of processed data.

**Repositories:**
- [Amino Acid Energy Visualization](https://github.com/Haniyekzm/Amino-Acid-Energy-Visualization)
- [Pie Chart Visualization](https://github.com/Haniyekzm/Pie-Chart-Visualization)

### 5. Data Processing and Organization

Scripts and notebooks for sorting, organizing, and preparing simulation-derived datasets.

- Processing CSV files containing residue and frame information.
- Organizing hydrogen-bond data across simulation frames.
- Extracting and sorting residue-level information.
- Preparing structured datasets for downstream analysis.

**Repository:** [Data Sorting](https://github.com/Haniyekzm/Data-sorting)

## Tools and Technologies

- **GROMACS** — molecular dynamics simulation data
- **Python** — data processing and analysis
- **VMD** — molecular visualization and trajectory inspection
- **Pandas** — tabular data processing
- **Matplotlib** — scientific visualization
- **CSV and XVG** — supported data formats in relevant analysis workflows

Actual input formats and dependencies vary by script.

## Scientific Scope

The analysis workflow focuses on extracting interpretable, residue-level information from MD simulation data. Energetic profiles, hydrogen-bond participation, and structural observations can be examined together to investigate changes in protein behavior.

These measurements provide complementary indicators of molecular interactions and structural dynamics. However, individual metrics should not be interpreted as conclusive evidence of protein destabilization without considering the simulation setup, appropriate controls, and additional structural analyses.

## Scope and Limitations

This repository documents a collection of analysis tools rather than a single fully automated pipeline. Individual scripts may require preprocessing or adaptation to the structure of the input data.

The availability of a particular metric depends on the source simulation outputs and the corresponding analysis script. Energy values, force components, and hydrogen-bond counts represent distinct quantities and should be interpreted accordingly.
