# GROMACS Data Analysis – Per-Residue Force Visualization

This repository provides a collection of Python scripts designed for the **analysis and visualization of amino acid energetics and hydrogen bonding** in molecular dynamics (MD) simulations.  
The toolkit includes multiple scripts that allow researchers to calculate, compare, and visualize amino acid energy profiles and H-bond participation in different ways.

---

##  Overview of Available Scripts

###  Total Energy per Amino Acid over Time
- Computes the **total energy of each amino acid** across all frames (time steps).  
- Plots:  
  - Line chart for each amino acid showing its energy profile vs. time.  
  - Combined chart displaying all amino acids with **different colors** for easier comparison.  
  - Bar chart showing the total energy of all amino acids side by side.  

---


###  Average Energy & Binding Energy Difference
- Calculates the **average total energy** of each amino acid across all frames.  
- Plots:  
  - A chart showing the mean energy values.  
  - A comparison plot that highlights the **difference in energy for each amino acid during binding events**.  

---

###  H-Bond Counting (per Residue)
- Counts the **number of hydrogen bonds (H-bonds)** formed by each amino acid across the trajectory.  
- Plots: A grouped bar chart displaying the H-bond counts for all amino acids side by side.  

---

###  Binding Time Analysis
- Calculates the **total time (frames)** each amino acid spends forming H-bonds.  
- Plots: A bar chart showing the total binding duration for each residue.  

---

###  H-Bond Position Distribution
- Computes the **distribution of H-bond counts per residue position**.  
- Plots: A chart showing H-bond frequencies as a function of residue position.  

---

##  Features
- CSV-based input for easy integration with MD post-processing pipelines.  
- Automated counting, averaging, and comparison of energetic properties.  
- Clean and publication-ready visualizations (line charts, bar charts, grouped plots).  
- Lightweight and extensible codebase for further customization.nts.
- Parsing and extracting force data from GROMACS output files (e.g., `.xvg`, `.edr`, or pre-processed CSV files).  
- Computing the average value of each force component for every residue.  
- Plotting grouped or stacked bar charts where:  
  - Each residue corresponds to a group on the x-axis.  
  - Each force component is represented by a different color.  
- Customizable visualization options: labels, titles, legends, and color palette.  
- Saving results both as figures (PNG/SVG) and processed data tables (CSV).
