# Hydrogen Bond Counting per Residue

This repository contains a Python script that processes **CSV input files** containing
hydrogen bond (H-bond) information for residues across multiple frames in a molecular
dynamics (MD) simulation.
The script counts the **total number of H-bonds formed by each residue** throughout
the entire trajectory.

##  Motivation
In molecular dynamics simulations, analyzing hydrogen bond formation is a key step in
understanding:
- Structural stability
- Interaction patterns between residues
- Binding or folding behavior

This script provides a straightforward way to count and summarize H-bond participation
for each residue across all frames.

##  Features
- Input: CSV file with columns for **residue name** and **frame number**
- Output: total H-bond counts per residue
- Simple, fast, and easy to integrate into analysis workflows
- Outputs both terminal display and optional CSV summary file.
