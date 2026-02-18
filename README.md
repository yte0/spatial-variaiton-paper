
# Spatial Variation in Uncertain Onset of Symptom Time in Stroke Patients

## Overview

This repository contains the analysis code and documentation for a research paper investigating geographic variation in uncertain onset of symptom time among stroke patients in Norway. The study uses data from the Norwegian Stroke Registry.

## Research Focus

This project examines spatial patterns and variations in symptom onset uncertainty across different geographic regions in Norway for stroke patients, utilizing advanced spatial statistical modeling.

## Main Tools

- **R**: Primary programming language for data analysis and visualization
- **INLA** (Integrated Nested Laplace Approximation): Main statistical tool for spatial modeling and Bayesian inference



## Project Structure

- `code/`: R scripts for analysis and modeling
- `output/`: Generated results, figures, and tables
- `doc/`: Paper drafts and documentation

## Getting Started

Ensure you have R and the INLA package installed. The INLA package can be installed via:

```R
install.packages("INLA", repos=c(getOption("repos"), INLA="https://inla.r-inla-download.org/R/stable"), dep=TRUE)
```