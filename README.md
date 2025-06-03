## **Autism Brain Imaging Data Exchange Downloader and Preprocessor (CPAC Pipeline)**

This project provides Python scripts designed to run in Google Colab or locally

## Features
 **1. ABIDE Downloader (CPAC Pipeline - Colab ready)**
Automatically:
- Downloads a subset of 250 subjects from the ABIDE dataset using the CPAC pipeline.
- Extracts preprocessed functional MRI images (func_preproc).
- Generates a clean .CSV file with subject-level phenotypic data :   
      - Diagnosis (Autism / Control)
      - Sex
      - Age
- Site of data acquisition
- Compresses images and metadata into a .zip file for direct download from Colab.

 **2. NIfTI to PNG Converter (Colab/Local)**
Includes a second script that:
- Converts .nii / .nii.gz brain MRI files to 2D PNG slices.
- Handles 2D, 3D, or 4D NIfTI images.
- Automatically extracts the central slice from each image volume.
- Applies min-max normalization and image rotation for proper orientation.
- Saves output images in a structured folder for downstream deep learning or visualization tasks.



## References
- [ABIDE Preprocessed Project](http://preprocessed-connectomes-project.org/abide/)
- [Nilearn – fetch_abide_pcp Documentation](https://nilearn.github.io/stable/modules/generated/nilearn.datasets.fetch_abide_pcp.html)

## About
This project was developed as part of a research study focused on brain MRI analysis for autism spectrum disorder (ASD) detection using preprocessed neuroimaging data and advanced machine learning pipelines.
