# Diffusion Tensor Imaging (DTI): FA and MD Mapping

## Overview
This project implements a diffusion tensor imaging (DTI) pipeline to estimate
voxel-wise fractional anisotropy (FA) and mean diffusivity (MD) from diffusion
MRI data. The project demonstrates fundamental diffusion MRI concepts and
tensor-based microstructural modelling.

## Dataset
Diffusion MRI data were obtained from the SCA2 Diffusion Tensor Imaging dataset
hosted on OpenNeuro. Only a single subject and the raw diffusion-weighted images
were used for demonstration purposes. Raw data are not included in this
repository.

Dataset reference:
https://openneuro.org

## Methods
- Loaded diffusion-weighted MRI (DWI) data
- Read diffusion gradient directions (b-vectors) and b-values
- Constructed a diffusion gradient table
- Fitted the diffusion tensor model voxel-wise
- Computed fractional anisotropy (FA) and mean diffusivity (MD)
- Visualised central slices of FA and MD maps

## Tools
- Python (NumPy, Matplotlib)
- nibabel for NIfTI I/O
- DIPY for diffusion MRI modelling
- Conda environment (Python 3.10)

## Example Results
![FA and MD maps](figures/FA_MD_maps.png)

## Author
Rajeev
