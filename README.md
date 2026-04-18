# Quadrant-Based Longitudinal Analysis of Football Movement

This repository contains the Python/Jupyter Notebook code developed for an MSci Mathematics thesis on football tracking data. The project develops a quadrant-based framework for analysing sprint-associated movement and directional loading using STATSports GPS data.

## Overview

The notebook implements a full analytical pipeline for:

- importing and preprocessing tracking data
- transforming latitude/longitude coordinates into a local planar system
- filtering positional and speed signals
- extracting sprint windows
- deriving forward and lateral acceleration quantities
- constructing quadrant-based movement summaries
- generating force-, impulse-, and longitudinal comparison plots

The main aim of the project is to produce an interpretable framework for describing sprint-associated movement and directional loading over time.

## Repository contents

- `MSci Project.ipynb` — main Jupyter notebook containing the full analysis
- supporting figures / outputs — plots generated from the pipeline

## Using the notebook

The notebook includes exploratory sections as well as a final end-to-end pipeline designed to be easy to use. In particular, the last section of the notebook provides a structured workflow that allows users to:

1. input their own raw tracking data
2. adjust key parameters such as filtering and sprint thresholds
3. generate the corresponding quadrant-based movement and loading outputs

This makes the framework straightforward to adapt to other datasets.

## Notes on confidentiality

To avoid disclosing potentially confidential information, file names and related identifiers have been removed from the shared version of the notebook. The locations where these substitutions are required have been clearly marked in the notebook comments.

## Reproducibility

The full analytical pipeline used in the thesis is included in this repository, and the final section of the notebook provides a clear end-to-end workflow for reproducing the analysis structure. However, the results are not immediately reproducible from the shared notebook alone, because confidential file names and related identifiers have been removed. To rerun the analysis, these redacted file-path entries must be replaced with the user's own data sources. Once those substitutions have been made, the same pipeline can be used with the existing code and adjustable parameters to generate equivalent outputs on new datasets.
